要查询 Linux 系统的详细信息，你可以使用一系列命令来获取不同方面的信息。以下是一些常用的命令：

1. **uname**：显示系统信息，如内核版本、主机名等。
   ```bash
   uname -a
   ```

2. **lsb_release**：显示 Linux 发行版信息。
   ```bash
   lsb_release -a
   ```

3. **cat /etc/os-release**：显示 Linux 发行版信息。
   ```bash
   cat /etc/os-release
   ```

4. **hostname**：显示主机名。
   ```bash
   hostname
   ```

5. **df**：显示文件系统使用情况。
   ```bash
   df -h
   ```

6. **free**：显示内存使用情况。
   ```bash
   free -h
   ```

7. **lscpu**：显示 CPU 信息。
   ```bash
   lscpu
   ```

8. **lspci**：显示 PCI 设备信息。
   ```bash
   lspci
   ```

9. **lsusb**：显示 USB 设备信息。
   ```bash
   lsusb
   ```

10. **ifconfig** 或 **ip addr**：显示网络接口信息。
    ```bash
    ifconfig
    ```
    或
    ```bash
    ip addr
    ```

这些命令可以帮助你获得系统的基本信息，包括硬件、内核、发行版等方面的详细信息。
