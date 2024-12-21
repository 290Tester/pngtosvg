
# pngtosvg
convert_png_to_svg
本可执行文件需要termux环境有两个版本一个termux一个debian12
都是基于Arm64，需要用到以下软件包
ImageMagick
png转pdf就用它
pdf2svg
pdf转svg就用它
安装
（可选）
sudo apt-get update
安装
sudo apt-get install imagemagick pdf2svg
还有一种方法
su -c apt-get install imagemagick pdf2svg
# pngtosvg English
This executable requires a termux environment with two versions, one termux and one debian12
All are based on Arm64 and require the following packages:
ImageMagick
Use it to convert png to pdf
pdf2svg
Use it to convert PDF to SVG
Installation
(Optional)
sudo apt-get update
Installation
sudo apt-get install imagemagick pdf2svg
There is another way
su -c apt-get install imagemagick pdf2svg
# 使用方法
git clone https://github.com/290Tester/pngtosvg.git
debian的情况下
cd pngtosvg
./png_to_svg[Debian]
Termux
cd pngtosvg
./png_to_svg[Termux]
记得给可执行权限
# How to use
git clone https://github.com/290Tester/pngtosvg.git
Debian case
./png_to_svg[Debian]
Termux
./png_to_svg[Termux]
Remember to give executable permissions

