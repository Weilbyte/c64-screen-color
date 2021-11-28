# c64-screen-color
Color in a 40x25 Commodore 64 screen and export as ACME instructions.

![image](https://user-images.githubusercontent.com/43392677/143787674-3a7e6f03-ab32-4de0-8ba6-e5b4c4e686af.png)

Currently only colors are supported, but when exporting, a reverse space character (`0xA0`) character is also placed so you can see the color. No tricks are used to lower the amount of space the code takes, so this is not very efficient. 
