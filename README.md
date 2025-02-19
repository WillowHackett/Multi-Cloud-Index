# Multi Cloud Index
<b>A Powerful Project to make Index of any Cloud Service using RCLONE CONFIG FILE and cross all download limits or even stream!🔥</b>
<!---Features--->
<h2>🆕What's New?🆕</h2>
<h4><b>1.Unlimited Download or Stream.😍</b></h4>
<h4><b>2.Faster Login using RCLONE CONFIG FILE.😉</b></h4>
<h4><b>3.Added Dark theme.😎</b></h4>
<h4><b>4.Added Index Authorization.🔒</b></h4>
<h4><b>5.Add as many cloud services (Multiple Times) as much you want.🔥</b></h4>
<h4><b>6.Permanent Direct Download.😆</b></h4>
<!---Introduction--->
<h2><b>📑 Introduction</b></h2>
<h4><b>Are you frustrated from Download or stream limits? Not any more!😊.This project helps you to create and deploy your own Multi Cloud Index using which you can download files or even stream them without any limits.To make your Work more simple, you can use RCLONE CONFIG FILE with this project to directly add your Cloud Service account in your Index.And for hosting your Index, you can either use Heroku or Railway app for best experience.You can also switch between Light and Dark theme to make it more comfortable and add Index Authorization for protecting your data against unauthorized access.🔒The file link which you will get from this Index is a permanent link (24*7) and will work until your Cloud Account and can also be used in large number of CLI(s).You can deploy your own index from any device including Phone,Laptop and PC or anything which have a simple Browser! <i>Now if you are worried about creating RCLONE CONFIG FILE,😎 then don't worry, I already got you covered, I made a totally Cloud based setup which can be used in any device have a Browser for that.</i> You will get its details below in this Guide.</b></h4>
<!---RCLONE CONFIG FILE GUIDE--->
<h2><b>📦 Creating Rclone Config file</b></h2>
<h4><b>Now if you think that this is a rocket science,then relax! I have created a super easy RCLONE CLOUD SETUP and now you don't need to download anything.You can create it in any device which have a simple browser.I have created a complete simple guide, just click on the below given Button to start creating your RCLONE CONFIG FILE online.In this project you just have to copy the code of RCLONE CONFIG FILE after opening it in any simple Text Editor app and paste it during the Setup of your Index.</b></h4>
<!---RCLONE CREATION GUIDE BUTTON--->
<h5><b><a href="https://www.caduceus.ml/Rclone-Setup-on-Google-Colab/" alt="RCLONE-SETUP">Create Rclone Config File Online</a></b></h5>
<h4><b>1.First Click on the Above Button and Read the instruction.</b></h4>
<h4><b>2.After Successfully Downloading the RCLONE CONFIG FILE, open it in any simple text Editor and copy its code</b></h4>
<h4><b>3.Now after copying the RCLONE CONFIG FILE code. Go to gist.github.com and paste the code and save it with name "rclone.conf" and click "Create secret gist".</b></h4>
<img src="Img/1.png" alt="1">
<h4><b>4.After that! Now click the "Raw" button to get the direct link to your gist.</b></h4>
<img src="Img/2.png" alt="2">
<h4><b>5.Once it opens your code in a new tab just copy the URL of that page which will look like this:</b></h4>
<img src="Img/3.png" alt="3">
<h4><b>6.Now you are ready to read the Next section!</b></h4>
<!---Before you Proceed--->
<h2><b>🪧 Before you Proceed!</b></h2>
<h4><b>1.You can add custom Domain in your Index if you deploy it using Railway App.</b></h4>
<h4><b>2.Railway App can take time larger than Heroku to make Index working but difference is too small.</b></h4>
<h4><b>3.If you add Cloud Account which have large data which was uploaded unofficially beyond the max Storage limit plan that Service provide then it may not open, however in most cases it works!</b></h4>
<h4><b>4.Some Cloud Services do not allow you to stream without downloading the Video even using this Index! to fix it, there is a Trick in this Guide.</b></h4>
<!---How to use Guide---> 
<h2><b>⚙️ How to use?</b></h2>
<h3><b><i>Deploy on Heroku:</i></b></h3>
<h4><b>1.First open the app deployment page on Heroku: <a href="https://heroku.com/deploy?template=https://github.com/TheCaduceus/Multi-Cloud-Index" alt="Deploy on Heroku">Open it</a></b></h4>
<h4><b>2.Now if you don't have a Heroku account then create once or just login!</b></h4>
<h4><b>3.After opening the Deployment page, Enter the following Values</b></h4>
<!---Heroku Values--->
<p><b>
	1.App name - Give a Nice name to your Index.<br>
	2.CONFIG_IN_URL - Paste the URL which you copied from STEP 5 written in above section.<br>
        3.indexauthentication - If you want to add password protection to prevent unauthorized access then change the value to "true" and change the below two values otherwise keep it "false" and ignore the following two values<br>
        4.INDEXpassword - If you set authentication to "true" then change its value! This value will be your Index Password<br>
        5.INDEXusername - If you set the password then change this value! This value will be your Index Username to login<br>
        6.template - You can turn Dark mode on and off! Just type "light" to turn it off and "dark" to turn it on.
</b></p>
<img src="Img/4.png" alt="4">
<h4><b>4.Now click on the Deploy button and wait patiently and once it got successful deployed, click View App button</b></h4>
<img src="Img/5.png" alt="5">
<h4><b>5.Clicking "View App" button will open a new website which is your index! Just remember the URL of your Index and access it anytime and anywhere.</b></h4>
<img src="Img/6.png" alt="Preview/6">
<h4><b>6.If you deploy your Index through Heroku then its URL should be like this: https://{appname}.herokuapp.com/</b></h4>
<h4><b>7.Sometimes after deploying the Index! It may take max 10 Minutes to start working.</b></h4>
<h3><b><i>Deploy on Railway app:</i></b></h3>
<h4><b>1.First fork this Repository to your GitHub Profile and go to https://railway.app/dashboard.</b></h4>
<h4><b>2.Now Login or Create a new Account on it using only GitHub.</b></h4>
<img src="Img/7.png" alt="7">
<h4><b>3.After logging into Railway, Click on "New Project".</b></h4>
<img src="Img/8.png" alt="8">
<h4><b>4.Choose "Deploy from Repo" to deploy your forked repository.</b></h4>
<img src="Img/9.png" alt="9">
<h4><b>5.Then select "Multi-Cloud-Index" Repository from the list.</b></h4>
<img src="Img/10.png" alt="10">
<h4><b>6.Click "Add Variables" and enter the following Values to configure your Index.</b></h4>
<!---Railway App Values--->
<!---There is no need for App Name as a Value in Railway App--->
<p><b>
	1.CONFIG_IN_URL - Paste the URL which you copied from STEP 5 written in above section.<br>
        2.indexauthentication - If you want to add password protection to prevent unauthorized access then change the value to "true" and change the below two values otherwise keep it "false" and ignore the following two values<br>
        3.INDEXpassword - If you set authentication to "true" then change its value! This value will be your Index Password<br>
        4.INDEXusername - If you set the password then change this value! This value will be your Index Username to login<br>
        5.template - You can turn Dark mode on and off! Just type "light" to turn it off and "dark" to turn it on.
</b></p>
<h4><b>7.Finally! Click on the "Deploy" button and let it get deployed! Index can take maximum 10 Minutes to start working after successfully getting deployed.</b></h4>
<img src="Img/11.png" alt="11">
<h4><b>8.After waiting for 10 Minutes click on the Name under "Deployment" Tab to open your Index as shown in the Image.</b></h4>
<img src="Img/12.png" alt="12">
<!---Adding Custom Domain--->
<h2><b>🖍️ Adding Custom Domain</b></h2>
<h3><b><i>On Railway App:</i></b></h3>
<p><b>As I already said! That you can add custom domain to your Index,much more easily on Railway and it does not requires adding any special information or verification like adding Card or Phone Number if you deploy it on Railway app. Just click on the "Domain" tab to get all settings about it, as shown in the given Image.</b></p>
<img src="Img/13.png" alt="13">
<p><b>The Railway will ask you to just set a new CNAME Record in your Domain by going into the Domain Registrar's Website<br>Record Details:<br>Name:@ TYPE:CNAME Value/Target: Should be the subdomain of Railway for your Project</b></p>
<h3><b><i>On Heroku:</i></b></h3>
<p><b>You can also add custom domain for the Index deployed on Heroku! For it just add Credit Card in your Account by going into:<br>Account Settings>Billings>Add Credit Card<br>And then you can add Custom domain by going back into<br>App>Settings>Add Domain.</b></p>
<p><b>Tip: If we look on both Options,then adding custom domain using Railway is much easier than Heroku.</b></p>
<h2><b>🔗 Using Direct Link!</b></h2>
<p><b>This Project provides you permanent direct download link of any file (In any Cloud) to use it in any Internet Download Manager (IDM) or in large number of CLI(s).To Copy the Direct Download link! Follow the below steps:</b></p>
<h3><b><i>On Mobile:</i></b></h3>
<p><b>1.Just Hold down on a file name in your Index and click "Copy link address" in pop-up.</b></p>
<img src="Img/14.jpg" height="50%" width="40%" align="center" alt="14/Mobile-Preview">
<p><b>2.And you have successfully Copied your Direct Download Link.</b></p>
<h3><b><i>On PC:</i></b></h3>
<p><b>1.Just right click on the File Name and click "Copy Link".</b></p>
<img src="Img/15.png" alt="15/PC-Preview">
<!---Streaming Videos--->
<h2><b>📽️ Streaming Videos</b></h2>
<p><b>You can use VLC Media App for both Phone/PC/Laptop and Tablet.Lets learn how to do that!</b></p>
<h3><b><i>For Mobile Phone:</i></b></h3>
<h4><b>1.First Download VLC Media App for <a href="https://play.google.com/store/apps/details?id=org.videolan.vlc" alt="VLC For Android">Android</a> or <a href="https://apps.apple.com/us/app/vlc-for-mobile/id650377962" alt="VLC For iOS">iOS</a>.</b></h4>
<h4><b>2.Now open it and click "More" option then "New Stream" option as shown in the given image.</b></h4>
<img src="Img/16.jpg" height="50%" width="40%" align="center" alt="16/Mobile-Preview">
<h4><b>3.Then Enter your Direct Link which you get from above "Using Direct Link" Section! And then click Continue Button.</b></h4>
<img src="Img/17.jpg" height="50%" width="40%" align="center" alt="17/Mobile-Preview">
<h4><b>4.Finally wait for maximum 5 Minutes, (Don't touch screen) to let VLC to Establish a connection with your Index. The Video will start playing automatically!</b></h4>
<h3><b><i>For PC:</i></b></h3>
<h4><b>1.First Download the VLC App for <a href="https://www.videolan.org/vlc/download-windows.html" alt="For Windows">Windows</a> or <a href="https://www.videolan.org/vlc/download-macosx.html" alt="For MacOS">MacOS</a> or <a href="https://www.videolan.org/vlc/#download" alt="For Linux">Linux</a></b></h4>
<h4><b>2.Now Click "Media" Tab and choose "Open Network Stream" from the list or Simply press CTRL+N Keys.</b></h4>
<img src="Img/18.png" alt="18/PC-Preview">
<h4><b>3.It will open a Dialog Box as shown in the Image! Enter your Link which you got from "Using Direct Link" Section and click "Play" button.</b></h4>
<img src="Img/19.png" alt="19/PC-Preview">
<h4><b>4.Finally wait for maximum 5 Minutes, (Don't touch screen) to let VLC to Establish a connection with your Index. The Video will start playing automatically!</b></h4>
<!---Index Preview--->
<h2><b>📃 Index Preview</b></h2>
<img src="Img/20.png" name="With Dark Mode">
<img src="Img/21.png" name="With Light Mode">
<!---Quick Links--->
<h2><b>🖇️ Quick Links</b></h2>
<h4><b>Text Editor Download:</b></h4>
<h4><b><a href="https://play.google.com/store/apps/details?id=com.maxistar.textpad" alt="For Android">Text Editor for Android</a></b></h4>
<h4><b><a href="https://apps.apple.com/us/app/text-editor/id1483790257" alt="For iOS">Text Editor for iOS</a></b></h4>
<h4><b>VLC Media Player Download:</b></h4>
<h4><b><a href="https://play.google.com/store/apps/details?id=org.videolan.vlc">VLC For Android</a></b></h4>
<h4><b><a href="https://apps.apple.com/us/app/vlc-for-mobile/id650377962">VLC For iOS</a></b></h4>
<h4><b><a href="https://www.videolan.org/vlc/download-windows.html" alt="For Windows">VLC For Windows</a></b></h4>
<h4><b><a href="https://www.videolan.org/vlc/download-macosx.html">VLC For MacOS</a></b></h4>
<h4><b><a href="https://www.videolan.org/vlc/#download">VLC For Linux</a></b></h4>
<h2><b>⛑Contact Us!</b></h2>
<h4><b>Join our Update Channel at Telegram:<a href="https://telegram.me/TheCaduceusUPDATE"> Join Now!</a></b></h4>
<h4><b>Directly Contact the Developer using Telegram <a href="https://telegram.me/HelpAutomatted_Bot">@HelpAutomatted_Bot</a></b></h4>
<h2><b>❤️Credits & Thanks</b></h2>
<p><b><a href="https://github.com/TheCaduceus">Dr.Caduceus</a>: For creating this Powerful Project and this All-in-one Guide.</b></p>
<p><b><a href="https://hub.docker.com/u/developeranaz">DevAnaZ</a>: For Project on Docker Hub.</b></p>
