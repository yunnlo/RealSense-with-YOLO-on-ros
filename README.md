# RealSense-with-YOLO-on-ros
utilizing realsense435 + YOLO on ROS 
Realsense Camera on Ubuntu
https://www.ybliu.com/2020/04/realsense-camera-on-ubuntu.html

ROS-realsense d435
https://blog.csdn.net/weixin_44600457/article/details/103900544?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromBaidu-2.not_use_machine_learn_pai&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromBaidu-2.not_use_machine_learn_pai

setup openvino
https://docs.openvinotoolkit.org/2019_R3.1/_docs_install_guides_installing_openvino_linux.html#additional-NCS-steps

update to python3.7 no more on 2.7
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
point to python 3.7
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.7 1
check the python3 --version
update pip and install numpy
pip3 install --upgrade pip
keep openvino ./install_prerequisites.sh
then demo
