# private-cloud-deployment
Hey guys, we're going to take a look at setting up our own cloud using Next Cloud. I'm going to show you guys how to install this on Ubuntu Server, but you can install it on any other linux distro you choose to install it on or you can choose to install it on another server distro.if u have any doubt contact me in Linkedin https://www.linkedin.com/in/mageshwaran-k-b441781b8/ So let's jump into the desktop and I'll show you guys how to get started. Okay, so now that we're in Ubuntu Server, you can pretty much install Next Cloud using a snap, and that's how we're going to do it in this video. You can also go the manual routes and basically install all the patchy servers and all that stuff, but i just want to make this a lot quicker and it's a lot easier to get up and running, 

Step 1:- sudo snap install Next Cloud

press enter, type in your password, you're going to see a progress bar on the right hand side, just give it about five to ten minutes.let it get up and running so once next cloud has been successfully installed you should see that on the terminal there'll be a green check showing you installed now we need to know the IP address to log in to Nextcloud

Step 2:- sudo ifconfig

press enter, it will show your IP number if it shows any error/ command not found. follow step 3 

Step 3:- sudo apt install net-tools

press enter, it will install networking tools and follow step 2

now all we need to do is open up a new window for our web browser and we want to type in 

Step 4:- http://your ip number 

Now you should come to the create an admin account page so first up let's create a username and a password and you can see you can install recommended apps which include calendar contacts, talk mail, and collaborative editing so i'm gonna leave that ticked and i'm gonna click on finish setup. Now at this step guys it does take a few minutes depending on how fast your system is and next cloud will download a bunch of stuff so be patient give it some time maybe grab a cup of coffee and you should be up and running soon all right. So once all that went through, you should come to the screen right here. It's basically like a presentation of what Next Cloud is about, so I'm going to click on this next arrow and you can see it'll give you some information, and so on click on next again, you also get the ability to access more than 100 apps in the Next Cloud app store, which is quite a lot.

Cool, you can go through that whenever you want to, so this is how your default web interface will look on Next Cloud.Now if you want to head over to the file section you'll see all your tabs are right here on the left hand side. Give that a few seconds; it is going to be a bit slow guys on the first install and all that stuff. You're going to want to give it a few minutes to properly sync and get everything all up and running but none the less, you guys can see a quick breakdown on how Next Cloud will look on your system or once you install it on your server side. So now that we're done with the server end Now Let's install our desktop client so we can basically start syncing our files back and forth.

Step 5:- https://nextcloud.com/install/#install-clients 

go to linux app image download that. linux doesn't automatically execute for you, you need to right-click, head over to properties, and go under permissions. You need to tick this option right here once you're done with that, then you can pretty much just double-click, and you should see the app image installed right now. We just need to log into our next cloud system. First up, we need to put the server ip address in, give your IP address . Click on Next and it should open up the browser for us. Click on Log in and Grant Access and there you have it guys, so now you should be connected to your next cloud installation. You'll be able to see the folders that come up and how much space you have given to next cloud. You can also choose when to sync and so on. Click on Ok and Next. 

for installing it in mobile app .it's pretty much the same process you're going to go into the Google Play Store.search for next cloud, put your ip address in, and your username and password, and you should be up and running Once you install the Android app on your phone, you can pretty much sync your photos and stuff back and forth and have a good backup. So thank you all for Reading, and I hope you found this Repo to be helpful or useful.

