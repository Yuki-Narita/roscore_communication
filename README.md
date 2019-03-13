# roscore_communication

# For labolatory members

## This package is used to share independent rosmasters topics


* share topics between masters
```
$ roslaunch roscore_communication roscore_communication.launch
```
* command list
```
$ sudo apt install ros-kinetic-multimaster-fkie  ※ “kinetic”の部分はrosのバージョンによって変える
$ git clone https://github.com/Yuki-Narita/roscore_communication.git

$ sudo sh -c "echo 0 >/proc/sys/net/ipv4/icmp_echo_ignore_broadcasts"
$ echo 'net.ipv4.icmp_echo_ignore_broadcasts=0' | sudo tee -a /etc/sysctl.conf > /dev/null
$ sudo service procps restart

$ roslaunch roscore_communication roscore_communication.launch
```
