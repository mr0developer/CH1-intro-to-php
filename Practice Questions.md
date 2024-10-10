# Write steps of xampp installation or setup process

STEP 1- Open any web browser and visit https://www.apachefriends.org/index.html. On the home page, you can find the option to download XAMPP for three platforms- Windows, MAC, and Linux. Click on XAMPP for Windows. The latest version available on the website is 7.4.5.

As soon as you click on it, a message displaying the automatic start of download appears on the screen.
![image](https://github.com/user-attachments/assets/268bc56a-6f15-4486-97eb-0fa2a52d59c3)
STEP 2- After the download is completed, double click the .exe extension file to start the process of installation.
![image](https://github.com/user-attachments/assets/050ccfb3-d953-46a5-9b9e-5663f979ca64)
STEP 3- A pop-up screen with the message asking you to allow to make changes on your desktop appears. Click "YES" to continue the process.
![image](https://github.com/user-attachments/assets/8961c6f0-9e9b-4e00-bfd5-a831aaa81866)
STEP 4- Click to Allow access or deactivate the firewall and any other antivirus software because it can hamper the process of installation. Thus, it is required to temporarily disable any antivirus software or security firewall till the time all the XAMPP components have been installed completely.
STEP 5- Just before the installation, a pop-up window appears with a warning to disable UAC. User Account Control (UAC) interrupts the XAMPP installation because it restricts the access to write to the C: drive. Therefore, it is suggested to disable it for the period of installation.
![image](https://github.com/user-attachments/assets/feea7af8-f698-41d5-bd90-32f32551051c)
STEP 6- After clicking the .exe extension file, the XAMPP setup wizard opens spontaneously. Click on "NEXT" to start the configuration of the settings.
STEP 7- After that, a 'Select Components' panel appears, which gives you the liberty to choose amongst the separate components of the XAMPP software stack for the installation. To get a complete localhost server, it is recommended to install using the default options of containing all available components. Click "NEXT" to proceed further.
![image](https://github.com/user-attachments/assets/32de7661-14b2-4646-b3b9-96c19698260b)
STEP 8- The setup is now ready to install, and a pop-up window showing the same appears on the screen. Click "NEXT" to take the process forward.
STEP 9- Select the location where the XAMPP software packet needs to be installed. The original setup creates a folder titled XAMPP under C:\ for you. After choosing a location, click "NEXT".
STEP 10- After choosing from all the previously mentioned preferences (like language and learn more bitnami dialogue box) click to start the installation. The setup wizard will unpack and install the components to your system. The components are saved to the assigned directory. This process may takes a few minutes to complete. The progress of the installation in terms of percentage is visible on the screen.
STEP 11- After the successful installation of the XAMPP setup on your desktop, press the "FINISH" button.
![image](https://github.com/user-attachments/assets/b6c1e87b-881f-4baa-aed2-6d62af8239b0)
On clicking the FINISH button, the software automatically launches, and the CONTROL PANEL is visible. The image below shows the appearance of the final result.
![image](https://github.com/user-attachments/assets/437207d1-5777-4acb-a27c-0e6ae8ad5c30)

# Write PHP code to display your Roll Number, Course Name and Technology Name on the browser. 
```
<?php
// Define variables
$rollNumber = "cit 227-054/2022";
$courseName = "BSE";
$technologyName = "PHP";

// Display the values
echo "<h1>Student Information</h1>";
echo "<p><strong>Roll Number:</strong> $rollNumber</p>";
echo "<p><strong>Course Name:</strong> $courseName</p>";
echo "<p><strong>Technology Name:</strong> $technologyName</p>";
?>
```

