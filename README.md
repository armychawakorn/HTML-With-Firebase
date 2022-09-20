# HTML Tutorial with Firebase in Introduction to computer science

This is an example HTML Project deploy with firebase


# [Step 1]
## First thing you need to do is replace your information on this line
  ```sh
<h2>ข้อมูลส่วนตัว</h2>
  <div class="content1 content-details">
      <h3 style="margin-top: 5px;">
          รหัสนักศึกษา: xxxxxxxxx-x
      </h3>
  </div>
  <div class="content2 content-details">
      <h3 style="margin-top: 5px;">
          ชื่อ: Mr.Edward Newgate
      </h3>
  </div>
  <div class="content3 content-details">
      <h4 style="margin-top: 5px;">
          จบจากโรงเรียน: New World High School
      </h4>
  </div>
  <div class="content4 content-details">
      <h4 style="margin-top: 5px;">
          คติประจำใจ: ชายผู้ที่แข็งแกร่งที่สุดในโลก
      </h4>
</div>
  ```
# [Step 2]
## insert your image url here | src="xxxxxx"
  ```sh
<div class="img-content" style="padding: 0 0 20px 0;">
    <h1>รูปภาพ</h1>
    <img style="border-radius: 10px;" width="240" height="256" src="img/Edward_Newgate.webp" alt="">
</div>
  ```
# [Step 3]
## your website ready to deploy to firebase!!. before that you need to download and install nodejs first
Download Nodejs: [Nodejs](https://nodejs.org/en/)

### now you need to open terminal in vscode | press ( Ctrl + shift + ` )
### [Step 3.1 Setup firebase cli to your project]
```
 Command: npm i firebase-tools
```
### [Step 3.2 Login firebase on firebase cli]
```
 Command: firebase login
 if you get error code on this process you can type this command to fix it: Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
 after that you can continue to next process
```
### [Step 3.3 Setup firebase tools on your project]
```
 Command: firebase init
 
     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

  C:\Users\armyc\Documents\HTML With Firebase

? Are you ready to proceed? (Y/n) Type: Y
```
### Select Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys
```
 ( ) Realtime Database: Configure a security rules file for Realtime Database and (optionally) provision default instance
 ( ) Firestore: Configure security rules and indexes files for Firestore
 ( ) Functions: Configure a Cloud Functions directory and its files
>(*) Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys
 ( ) Hosting: Set up GitHub Action deploys
 ( ) Storage: Configure a security rules file for Cloud Storage
 ( ) Emulators: Set up local emulators for Firebase products
```
### Select use an existing project
```
=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add, 
but for now we'll just set up a default project.

? Please select an option: (Use arrow keys)
> Use an existing project
  Create a new project
  Add Firebase to an existing Google Cloud Platform project
  Don't set up a default project
```
### Select your project on firebase
```
? Please select an option: Use an existing project
? Select a default Firebase project for this directory: (Use arrow keys)
> chawakorn-dev (Chawakorn Dev) 
  natithorn-website (Natithorn-website)
```

### Type name of public folder to deploy to firebase hosting ex. Deploy
```
=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? (public) Deploy
```

### On this process type Y
```
=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? Deploy
? Configure as a single-page app (rewrite all urls to /index.html)? (y/N) 
```

### On this process type N
```
? What do you want to use as your public directory? Deploy
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? Set up automatic builds and deploys with GitHub? (y/N) 
```

## Now your project almost to online
### Next step is deploy your project to firebase
### Move all files of your website to Deploy folder. after that
```
  type: firebase deploy
```

# Deployment is finish!! your website is online now
```
Project Console: https://console.firebase.google.com/project/chawakorn-dev/overview
Hosting URL: https://chawakorn-dev.web.app
```
## this is a url of your website Hosting URL: [https://chawakorn-dev.web.app](https://chawakorn-dev.web.app)

## Contact me

Email: Chawakorn.n@kkumail.com
Discord: ♥ E = 𝓡𝓸𝓼𝓲𝓷𝓪𝓷𝓽𝓮² ♥:7038
Line id: [https://line.me/ti/p/8REPWwkOuM](https://line.me/ti/p/8REPWwkOuM)
