# helmetvest
# helmetvest
# git clone https://github.com/MeijunZhu/helmetvest.git
1.把best.pt复制到yolov5的文件夹中
2.修改gen_wts.py文件中的pt文件名
3.python gen_wts.py
4.生成的.wts文件copy到tensorrtx/yolov5_1/build文件夹中
5.cd ..\tensorrtx\yolov5_1\build
6.cmake ..
7.make
8.sudo ./yolov5 -s best.wts helmetvest.engine s
