<h1 align="center">Google Solution Challenge 2023</h1>
<p align="center">
</p>


## Introduction:
As we all know, the health status of many is getting worst due to work stress and anxiety. Poor Mental Health has become the biggest problem for people. Most of the youth responsible for the growth of a country are crippled in the chains of depression and anxiety, thus slowing down developmental activities. Sadly, the problem is suffered by many yet not discussed openly. So here we the team "Ideavengers" bring a caretaker "CARESS" for all of them who suffer from the same but hesitate to tell.
  
## Demo Video Link:
  <a href="">Video Link</a>
  
## Presentation Link:
  <a href="https://docs.google.com/presentation/d/15uNn37Ne1BHc1Ht5Z4X_JvlUu-IsVYAx/edit?usp=sharing&ouid=116795368686984693045&rtpof=true&sd=true">Presentation</a>
  
  
## Table of Contents:

## Technology Stack:
  1) Flutter
  2) Dart
  3) Firebase
  4) Google Fit
  5) NewsAPI
  

## Contributors:

Team Name: Ideavengers

* [Pranjal Dubey](https://github.com/dubey2709)
* [Manjeet Pathak](https://github.com/IIITManjeet)
* [Vinay Kumar](https://github.com/vink08)
* [Shreem Asati](https://github.com/shreem-123)

# Caress
## Theme - Health and Well Being

### Note -
This app is currently in test mode and only users allowed by the admin who have a google account can use the app properly. The two possible publishing modes of the app are given below<br>

Publishing Status ( Important )<br>
<li>In Production:
Once you set your app status as "In production," your app will be available to anyone with a Google Account. Depending on how you configure your OAuth screen, you may have to submit your app for verification .<br>
<li>Testing:
If your app is still being tested and built, you can set your status to "testing". In this state, you can test your app with a limited number of users.<br>
Courtesy - https://console.cloud.google.com/apis


## Functioning and User Flow
1. Firstly the user sign up and login in the application.<br>
2. Basic Information of user, his friend/well wisher/guardian or any specialist doctor is taken for future use and profile display.<br>
3. Instructions are given to connect the app with the smart watch.<br>
4. After submitting the details and setting up the watch with app, the application ask for various permissions such as track activity, phone usage and personalized    google account permissions<br>
5. As soon as you give your google account access, data of your current vitals is shown on the screen which is updated after every 2 minutes.<br>
6. If there is a spike in the heart rate(>100), user recieves an alert notification.The alert notification suggests you to stop using an particular app(correctly 70% of the time) and provides you the facility to call your friend on a single tap. Also an email about the same is delivered to the friend/well wisher or specialist whose information was collected previously.Emails are sent after a duration of 3 hours only.<br>
7. Application also consists of articles page(contains articles related to mental health) and profile page which consits the data of user which can be updated frequently.<br>
8. Application also provides you with facility of self assessment of various mental health disorders such as Depression, PTSD, schizophrenia, addiction and anxiety. After taking the self assessment tests the results are shared with the specialist/doctor via an email.
9. Helpline page is there in the application which includes helpline numbers and website links of 11 mental health healing websites for support. Call to any organisation can be just made by a single tap on the contact tile.



# App Screenshots

<img src = "https://user-images.githubusercontent.com/110723566/227720701-55bf16ab-92ee-417f-85ee-d0f18c8e4116.jpeg" width = 200 ></img>&nbsp;
<img src = "https://user-images.githubusercontent.com/110723566/227720705-1889b381-0c0a-4f79-9a25-55b83cc706b2.jpeg" width = 200></img>&nbsp;
<img src = "https://user-images.githubusercontent.com/110723566/227720728-9167660a-c6bf-4a01-b3f9-7a481b4a476b.jpeg" width = 200></img>&nbsp;
<img src = "https://user-images.githubusercontent.com/110723566/227720713-f7f345d9-4997-46dc-99f1-2a1f54bed3e6.jpeg" width = 200></img>&nbsp;



## Flutter dependecies used :
  cupertino_icons: ^1.0.2<br>
  permission_handler: ^10.2.0<br>
  health: ">=4.4.0 <5.0.0"<br>
  firebase_auth: ">=4.2.8 <4.2.9"<br>
  firebase_core: ^2.7.0<br>
  cloud_firestore: ^4.4.3<br>
  shared_preferences: ^2.0.18<br>
  flutter_local_notifications: ^13.0.0<br>
  firebase_messaging: ^14.2.5<br>
  timezone: ^0.9.1<br>
  persistent_bottom_nav_bar: ^5.0.2<br>
  image_picker: ^0.8.7<br>
  firebase_storage: ^11.0.16<br>
  http: ^0.13.5<br>
  url_launcher: ^6.1.10<br>
  usage_stats: ^1.2.0<br>
  flutter_phone_direct_caller: ^2.1.1<br>
  email_validator: '^2.1.16'<br>
  intro_screen_onboarding_flutter: ^1.0.0<br>
  intl: ^0.17.0<br>
  percent_indicator: ^4.2.3<br>
  font_awesome_flutter: ^10.4.0<br>

## Future Scope - 
<li>Social Media Segmentation- To fetch one’s Social Media Posts, Messages and Screen Time. For example we can use Twitter Developer API’s to fetch one past tweets to judge one’s mental state.

<li>Introducing ML Model for mental health analysis- To introduce and train a better ML model with better data which we get from the app. More data can help us predict with better accuracy and hence the model will be more reliable.

<li>Embedded Training and support Videos – Integrate Mental Health Training videos for members which would suggest them various exercises to boost mental health. Simultaneously we’ll provide a peer to peer interaction of mental health experts in support of the same.

<li>Live Mental health webinars and sessions –We could also integrate live webinars like feature in our app where special guests and renowned specialist will share their view and suggestions over mental illness.

<li>Scalable the app for production purpose-  As we are using the health package in flutter application which requires certain google verifications, So due to some reasons our app is currently in testing mode and we want it to run in production mode later. 





 

