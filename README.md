# FluidNet-building-problems
Here is some problems I met when try to build FluidNet (Paper: Accelerating Eulerian Fluid Simulation With Convolutional Networks, Jonathan Tompson, Kristofer Schlachter, Pablo Sprechmann, Ken Perlin.)

## First is getGitVersion.py Permission Denied. 
When run ./manta xxxx, it shows that ___getGitVersion.py Permission Denied___. After you change the access rights of this or even the whole folder, (using command like chmod 777 xxxxxx.py. ), you get another problem, ___xxxxx.py Not Found___. I think it shows that gcc cannot find this file. So I need to install gcc 4.8.5 instead of keeping using gcc 9 on Ubuntu 20.04. (Here you can view my another article, ___How to install (downgrade) gcc without sudo___.  其中isl需要放在gcc文件夹中
