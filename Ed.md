# Computer build
Ed's computer, built on 2-Nov-2024
## Components
* **Case:** Corsair 2000D Airflow
* **Power supply:** Thermaltake Toughpower SFX-550W Gold
* **Mobo:** Gigabyte B650i AX mITX
* **CPU:** Ryzen 7 8700g
* **RAM:** Corsair Vengeance DDR5 C36 6000MHz, 2x16GB
* **SSD:** Samsung SSD 980 PCIe Gen3 NVMe M.2, 1TB

## Notes
Started building in the office on Friday afternoon, need to bring tools from home.
CPU is upgrade from previous computers (5700g -> 8700g). CPU socket is AM5 so also had to upgrade the mobo.
First problem was to figure out how to install the SSD in the mobo
Problem #2 is how to install the fan

Build was pretty much same as for the first 3 computers, except:
1. Computer case didn't come with fans. Setup was done without case fans then added fans later. CPU temp without fans seems OK, at least without running anything demanding
2. Computer case didn't come with power supply, bought separately
3. Computer case didn't come with CPU fan, used the one that came with the CPU instead
4. Computer was built at the office so no access to wired ethernet. Wifi driver must be installed in order to complete Windows setup.
    * Download driver on another computer and put it on USB
    * Make sure to get correct driver revision, based on Rev number on mobo box (1.3 in this case)
    * Install on the new computer using command prompt (SHIFT +F10)
    * Command is "C:\start D:\driver_filename.exe"
