Linux Kernel Dev
-------------------

1. Download [Ubuntu 18.04](https://releases.ubuntu.com/18.04/)
2. Enable Acceleration in VirtualBox (Page 17)
3. Create a virtual machine with 1 GB of RAM and 2 CPUs and a disk of 50GB dynamically allocated
4. Install Ubuntu with user `llkd`
5. `sudo update-manager`
6. `sudo apt update`
7. `sudo apt install gcc make perl`
8. [Install VirtualBox Guest Additions in Ubuntu](https://www.tecmint.com/install-virtualbox-guest-additions-in-ubuntu/)
9. `sudo apt install git fakeroot build-essential tar ncurses-dev tar xz-utils libssl-dev bc stress python3-distutils libelf-dev linux-headers-$(uname -r) bison flex libncurses5-dev util-linux net-tools linux-tools-$(uname -r) exuberant-ctags cscope sysfsutils gnome-system-monitor curl perf-tools-unstable gnuplot rt-tests indent tree pstree smem libnuma-dev numactl hwloc bpfcc-tools sparse flawfinder cppcheck tuna hexdump openjdk-14-jre trace-cmd virt-what`
10. `sudo apt install nodejs npm && sudo npm install -g tldr`

Install Tracing Tool

1. `sudo apt install openjdk-14-jre`
2. TODO: install lttng
3. TODO: install 'trace compas' gui

Install procmap

1. https://github.com/kaiwan/procmap
2. 







