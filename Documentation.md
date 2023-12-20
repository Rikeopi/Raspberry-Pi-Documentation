<div align="center">
   
>### FINAL PROJECT IN INFORMATION ASSURANCE AND SECURITY
>Mirandilla, Johnlery | Morata, Marri Grace | Nobleza, Uriel Miguel | Pizzaro, Jesrel
# RASPBERRY PI INSTALLATION GUIDE



</div>

1. Prepare and Install Headless Raspbian OS in Raspberry Pi
   1. Insert a micro SD card that is 8GB or larger into your computer.
   
   2. Visit the [official Raspberry Pi website](https://www.raspberrypi.com/software/) then download, install, and run Raspberry Pi Imager.

       ![img 1](images/img1.png)
      
   4. Choose which device, OS, and storage you are going to use.

      ![img 2](images/img2.png)

      Upon clicking **CHOOSE DEVICE/OS/STORAGE**, a menu should appear. The picture below is an example.

      ![img 3](images/img3.png)

   5. When done making your selection, proceed by clicking **NEXT**.

      ![img_4](images/img4.png)

      _(Image credit: Tom's Hardware)_

   6. Click Edit Settings from the pop-up.

      ![img_5](images/img5.png)

      _(Image credit: Tom's Hardware)_

   7. Fill in all the fields on the General tab.

      ![img_6](images/img6.png)

      _(Image credit: CS3B Group 11)_
      
   8. On the Services tab, toggle **Enable SSH** to on and select **Use password authentication."**

      ![img_7](images/img7.png)

      _(Image credit: CS3B Group 11)_

   9. Click **YES** to apply OS customization settings.

      ![img_8](images/img8.png)

      _(Image credit: Tom's Hardware)_

   11. Click **YES** to confirm that you want to your microSD card and wait until the installation is done.

       ![img_9](images/img9.png)
       
       _(Image credit: CS3B Group 11)_
       
       ![img_10](images/img10.png)
       
       _(Image credit: CS3B Group 11)_

   13. Once OS is downloaded and written in your SD card, click **CONTINUE** then reomove your SD Card from your computer.

       ![img_11](images/img11.png)

       _(Image credit: CS3B Group 11)_
   
2. Connecting to Raspberry Pi via SSH using the terminal

   1. Open _terminal_ and enter the following commands consecutively:
      **_ssh <username>@<hostname>_**

      ![img_12](images/img12.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt update_**

      ![img_13](images/img13.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt upgrade_**

      ![img_14](images/img14.png)

      _(Image credit: CS3B Group 11)_


4. Deploying LAMP (Linux Apache MySQL PHP) Stack in raspberry Pi
   1. In the terminal, enter the following commands:
      **_sudo apt install apache2_**

      ![img_15](images/img15.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt install mariadb-server_**

      ![img_16](images/img16.png)
      
      _(Image credit: CS3B Group 11)_
      
      **_sudo mysql_secure_installation_**

      ![img_17](images/img17.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt install php libapache2-mod-php php-mysql_**

      ![img_18](images/img18.png)

      _(Image credit: CS3B Group 11)_
      
      **_sudo apt-get install php\*_**

      ![img_19](images/img19.png)

      _(Image credit: CS3B Group 11)_
      
   2. You will be prompted to choose a web server. Select **apache2** using the spacebar, then press "Tab" to highlight **OK** and press Enter to continue.
      
      ![img_20](images/img20.png)
      
      _(Image credit: CS3B Group 11)_
      
   3. Finally, enter this command on the terminal and wait until the process is complete: **_sudo apt install phpmyadmin_**

      ![img_21](images/img21.png)
      
4. Enabling and controlling Rapberry Pi using VNC
   


(_**NOTE:** Images are not ours since we were able to perform the task before the announcement that there is a need for a documentation. Appropriate credits were noted after each photo. Thank you!_)
