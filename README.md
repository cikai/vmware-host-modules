
#### checkout 到对应 workstation 版本的分支，sudo make & sudo make install．

---

#### 解决　ubuntu 16.04 安装 VMware-Workstation-Full-12.5.9-7535481.x86_64.bundle 启动后，提示 

#### Before you can run Vmware, several modules must be compiled and loaded into the running kernel.

---

#### 然后点了 install 又报 

#### Unable to start services. See log file /tmp/vmware-root/vmware-27309.log for details.

#### 这个问题！

---

#### 查了下说是 ubuntu  网络的什么更新了，vmvare 老版本没支持，编译的时候找不到系统的一些库文件了．

---

#### 下载这个源码切到对应分支，重新编译下依赖就可以了．
