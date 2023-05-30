# biostar-b550mh-5600-6650xt-hackintosh
The EFI folder of biostar b550mh platform.
The specific information of the desktop:
- CPU: AMD 5600
- GPU: AMD RX6650XT
- Motherboard: Biostar b550mh
- SSD: MX500 1TB
- WIFI&Bluetooth: Intel AX210
- Memory: Seiwhale 16GB(3200hz)*2
- MacOS: Ventura 13.3
- 
![system info](https://www.tonymacx86.com/attachments/1683709674489-png.566555/)


### What's not working?
The Airdrop and sidecar did not work because of Ax210.

### What's work?
Everything works well except airdrop and sidecar.

### Tips
- ```SSDT-6x50_FakeID``` file is used to spoof GPU device id, if your GPU is not 6x50 series, you should delete or not load it in ACPI folder.

----------------
If you have some trouble while installing macOS with this EFI, you can see the [post](https://www.tonymacx86.com/threads/record-a-series-of-troubles-while-installing-ventura-on-biostar-b550mh.325562/) which I recorded a series of troubles while installing Ventura.
