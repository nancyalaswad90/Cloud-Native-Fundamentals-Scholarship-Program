Hello this is a quick tip on how to install and run Docker without any unusual error on Windows10 64bits:
Download docker https://docs.docker.com/docker-for-windows/install/
2. Download WSL from Windows Store https://www.microsoft.com/store/productId/9NBLGGH4MSV6
3. After installing Step 1, Step 2, and rebooting the System you need to update the WSL into WSL2 so you can make it compatible with Docker (right now it's normal to get an error from docker about WSL), here's the update link : https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
4. Reboot the system after updating, normally Docker should run just fine
Hoping that will be helpful for you
