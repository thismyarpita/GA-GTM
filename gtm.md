# Google Tag Manager 

## Installation

Google Tag supervisor is a tag control system (TMS) that permits you to easily update measurement codes and related code fragments together referred to as tags to your website or mobile app.
```python
Google Tag supervisor gives powerful features such as:
Tag: Create any advertising Tag and use the various integrations already current.
Trigger: define when your tag ought to get completed.
Versions: define numerous variations and deploy them to special websites.
```



##  Setup Google Tag Manager:-

```python
Create a new Account  https://tagmanager.google.com/ 
Enter an Account Name “ Bitcot”
Set Up Country  “United States”
After Container Setup  
We used our website url which we want to track 
https://wpbitcot.com/jayjinshasan/
Select Target Platform “ Web”
Click on Create


After that Popup Open 
Google Tag Manager Terms of Services Agreement
Scroll down checked checkbox
After click yes
Copy exactly the two pieces of code on the Header file in the <HEAD> section  and in the Body  <BODY> section in your website


----------------------------------------------------------------------------------------------------------------------------

## Paste this code as high in the <head> of the page as possible:

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-M2DQD88');</script>
<!-- End Google Tag Manager →
----------------------------------------------------------------------------------------------------------------------------

Additionally, paste this code immediately after the opening <body> tag:

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-M2DQD88"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) →

----------------------------------------------------------------------------------------------------------------------------

Right click on website 
Open View Page Source 
Like below image and Url      view-source:https://wpbitcot.com/jayjinshasan/
Search this GTM Id  :-             GTM-M2DQD88

The Below enclosed image shows that the code is Implemented in Head Section in  the website

The Below enclosed image shows that the code is Implemented in Body Section in  the website

Setup done after open Account 


```

## Install and set up Google Analytics with Google Tag Manager :-
```python
1. Open Google Tag Manager
2. Click on Add new a tag, and a new window will popup
3 . Fill a name, as an example “GA all pages”
4.  Click on the tag configuration area, and chose the type of Tag Google Analytics Universal Analytics
5.   Leave the Track type on Page view
6. Then added a setting Variable. (If it is a brand new container, you should have no variable. )
	Google Analytics Settings  Click (Rightside i icon)
            Create a new Variable  and name it “Ga tracking id“
            Click Variable Configuration select “Google Analytics Settings”
            Enter the Tracking ID of Google Analytics (UA-227563349-1)
            Select Cookie Domain {{Page URL}}

7.  Leave the rest as it is and save
8.  After that Trigger Created  Click this new
Choose trigger type ->Page view
In this screen select the page view tigger inside this GA all pages 
After that click submit
Then publish 
```

## Test Google Tag Manager installation:-
```python
To test Google Analytics and Google Tag Manager installation in website 

## We need to install this Chrome Extension:-
Tag Assistant Legacy (by Google) Extension       
After Refresh website URL to enable this Chrome Extension
After successful implementation of this extension the below mentioned result will be displayed on the screen

```

