# CrackSleeve4.x
## 说明

CobaltStrike4.x Sleeve解密文件, 搬砖自用。

## 各版本sleeve key

### 4.0

-   1be5be52c6255c33558e8a1cb667cb06
-   sleeve4_0 = {27,-27,-66,82,-58,37,92,51,85,-114,-118,28,-74,103,-53,6};

### 4.1

-   80e32a742060b884419ba0c171c9aa76
-   sleeve4_1 = {-128,-29,42,116,32,96,-72,-124,65,-101,-96,-63,113,-55,-86,118};

### 4.2

-   b20d487addd4713418f2d5a3ae02a7a0
-   sleeve4_2 = {-78,13,72,122,-35,-44,113,52,24,-14,-43,-93,-82,2,-89,-96};

### 4.3

-   3a4425490f389aeec312bdd758ad2b99
-   sleeve4_3 = {58,68,37,73,15,56,-102,-18,-61,18,-67,-41,88,-83,43,-103};

### 4.4

-   5e98194a01c6b48fa582a6a9fcbb92d6
-   sleeve4_4 = {94,-104,25,74,1,-58,-76,-113,-91,-126,-90,-87,-4,-69,-110,-42};

### 4.5

-   f38eb3d1a335b252b58bc2acde81b542
-   sleeve4_5 = {-13,-114,-77,-47,-93,53,-78,82,-75,-117,-62,-84,-34,-127,-75,66};
-   water_hash = {0,0,0,24,66,101,117,100,116,75,103,113,110,108,109,48,82,117,118,102,43,86,89,120,117,119,61,61};

### 4.7

-   sleeve4_7 = {-122, 56, -75, 17, -32, 91, 85, 123, -7, 112, -60, 24, 53, 109, 68, -12};

### 4.8

-   sleeve4_8 = {-118, 9, -22, -51, -53, 27, 95, 70, -99, -54, 53, 124, -9, -7, -26, 74};

## 使用方法

-   将cobaltstrike.jar（原名cobaltstrike-client.jar）和CrackSleeve.java放一起

-   编译( javac -encoding UTF-8 -classpath cobaltstrike.jar CrackSleeve.java)

-   解密文件( java -classpath "cobaltstrike.jar;./" CrackSleeve decode)

-   无需输入Key,加密文件( java -classpath "cobaltstrike.jar;./" CrackSleeve encode)

-   将解密后的sleeve文件夹替换jar包中的文件夹