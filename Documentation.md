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

      **_ssh \<username\>@\<hostname\>_**

      ![img_12](images/img12.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt update_**

      ![img_13](images/img13.png)

      _(Image credit: CS3B Group 11)_

      **_sudo apt upgrade_**

      ![img_14](images/img14.png)

      _(Image credit: CS3B Group 11)_


3. Deploying LAMP (Linux Apache MySQL PHP) Stack in raspberry Pi
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
      
   3. You will be prompted to choose a web server. Select **apache2** using the spacebar, then press "Tab" to highlight **OK** and press Enter to continue.
      
      ![img_20](images/img20.png)
      
      _(Image credit: CS3B Group 11)_
      
   4. Finally, enter this command on the terminal and wait until the process is complete: **_sudo apt install phpmyadmin_**

      ![img_21](images/img21.png)
      
4. Enabling and controlling Rapberry Pi using VNC
   
   1. Download and install RealVNC Viewer through [here](https://www.realvnc.com/en/connect/download/viewer/).
      
      ![img_22](images/img22.png)
      
      _(Image credit: CS3B Group 11)_

   2. After installing, type the following command in the terminal: **_sudo raspi_config_**.

      ![img_23](images/img23.png)

      _(Image credit: CS3B Group 11)_

   4. Select **Interface Options**.

      ![img_24](images/img24.png)

      _(Image credit: CS3B Group 11)_

   5. Enable the VNC.

      ![img_25](images/img25.png)

      _(Image credit: CS3B Group 11)_

   6. Open the RealVNC Viewer app and type the ip address of your raspberry

      ![img_26](images/img26.png)

      _(Image credit: CS3B Group 11)_

   7. Enter the username and the password and click "Ok"

      ![img_27](images/img27.png)
      
      _(Image credit: CS3B Group 11)_

   8. Your Raspberry Pi setup is done!

      ![img_28](images/img28.png)

      _(Image credit: CS3B Group 11)_
   


(_**NOTE:** The images used in this documentation are not our own, as we completed the task before the announcement that documentation was required. Appropriate credits have been given after each photo. Thank you!_)
