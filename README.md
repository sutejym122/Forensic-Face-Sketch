![Test Image 1](https://github.com/imakashsahu/Third-Eye-Final-Year-Project/blob/main/Logo.jpg)


# THIRD EYE
Forensic Face Sketch Construction and Recognition 

## SOURCE CODE
[Download Source Code](https://drive.google.com/file/d/1GG1F90qRMzmUv6REG8gf6yEtxGcuuXpa/view?usp=sharing)
(*Please mention the purpose for which you need the source code in the message box*)

## HOW TO RUN THE PROJECT<br>
  *Note : You need AWS for the recognition part , so you will have to setup AWS S3 bucket and AWS Rekognition*<br><br>
A detailed guide to run the Project is explained below<br><br>
  SETTING UP THE IDE<br>
    1.Download the Source Code from the Repo(https://github.com/sutejym122/Forensic-Face-Sketch)<br>
    2.Download and Install the Java JDK 8 (https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html)<br>
    3.Download the latest NetBeans Installer (https://netbeans.apache.org/download/index.html)<br>
    4.Install and Open NetBeans<br>
    5. GoTo Tools > Plugin > Available Plugin <br>
    6.Search for "Java FX" and check "Gluon Plugin" & "JavaFx implementation for Windows" then click on Install<br>
    7.Now search for "Maven" and check "Gradle" then click on Install<br>
    8.Restart NetBeans<br><br>
  
  SETTING UP FACE SKETCH CONSTRUCTION MODULE<br>
    1.The Face sketch construction module of the project is built using JAVA FX<br>
    2.Download Scene Builder (https://gluonhq.com/products/scene-builder/)<br>
    3.In NetBeans GoTo tools > options > Java > JavaFx<br>
    4.Browse for the Scene Builder Directory and select the directory from C:\ProgramFiles<br>
    5.Now GoTo File > Open Project > ThirdEye v2<br>
    6.Now under projects click on "ThirdEye v2 > Libraries" Right Click and select "Add Jar"<br>
    7.Browse to "ThirdEye v2 > lib" and select all and open<br>
    8.Download and Install SQLite Browser (https://sqlitebrowser.org/dl/)<br>
    9.Open the "login.sqlite" file from the "ThirdEye v2" Folder<br>
    10.Add your Own Credentials this is Important to get the OTP to login<br>
    11.Turn On Less secure for you Gmail (https://myaccount.google.com/lesssecureapps) or use anyother smtp server if this Gmail doesn't work<br>
    12.Now go to NetBeans, under projects click on "ThirdEye v2 > Source Package > thirdeye.v2" Double click on Login_screenController.java<br>
    13.On Line 144, Enter your GMail Creds to send OTP<br>
    14.Run the Project (F6)<br>
    15.Enter the Credential from DB Lite<br>
    16.Enter the OTP received to the email <br>
    17.Select Create Sketch and your are good to go <br>
    18.Change the File Directory on line 508 of file "dashboard_controller.java"!!!!!<br><br>
  SETTING UP FACE RECOGNITION MODULE<br>
    1. The Recognition part of the project is built using JAVA Maven and AWS for Deep learning<br>
    2. This part requires you to have AWS account with Credit Card been added to be activated<br>
    3. Create a AWS Free Tier account by adding in your Credit Card<br>
    4. Create a IAM user profile for the JAVA (https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html)<br>
    5. Add S3 and Rekognition Full Access<br>
    4. Install AWS CLI on Windows (https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html)<br>
    5. Run "aws configure" in CMD<br>
    6. Create a s3 Bucket <br>
    7. Now GoTo File > Open Project > ThirdEye_FaceMatch<br>
    8. Create a S3 Bucket on the AWS console<br>
    9. Create a collection in s3 using the "collection_create.java" file<br>
    10. Add images to the collection using the "collection_add_image.java" file<br>
    11. Enter the S3 Bucket name and collection details in the "collection_search_face.java" file<br>
    12. Run the Project (F6)<br><br>
    



## DESCRIPTION/ABSTRACT
In forensic science, it is seen that hand-drawn face sketches are still very limited and time-consuming when it comes to using them with the latest technologies used for recognition and identification of criminals. In this paper, we present a standalone application which would allow users to create composites face sketch of the suspect without the help of forensic artists using drag and drop feature in the application and can automatically match the drawn composite face sketch with the police database much faster and efficiently using deep learning and cloud infrastructure.



## FOR ANY OTHER QUERY
Email me at ***sutejym122@gmail.com***
(*Please mention the purpose for which you need the source code in the message box*)
