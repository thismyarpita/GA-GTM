# GA implementation steps

WebsiteUrl:-  https://wpbitcot.com/jayjinshasan/

## Installation

I have implemented  Google Analytics and Google tag manager on this website
https://wpbitcot.com/jayjinshasan/  using my mail arpitajain@bitcot.com



## Google Analytics :-

```python
Google Analytics includes capabilities that can help users identify developments and patterns in how traffic interacts with their websites. These capabilities allow for facts series, analysis, monitoring, visualization, reporting and integration with different programs.

It will assist you to analyze the traffic of your website and the behavior of your traffic.
The important functions of Google Analytics are revolve around:
Your Target market: - understand who are your internet site visitors
Acquisition: From where the visits are coming
Behavior: How do the visitors behave to your internet site, how is their go with the flow via the pages
Conversion: The degree of effect of your moves

```

## Setup Google Analytics:-

This is a URL to create a Google Analytics Account. We are required with a gmail id to sign in the below mentioned URL.

 https://analytics.google.com/analytics/web/provision/#/provision

Sign in account with your gmail 
Create new account 
Added account name

The following settings are required to access your account:-


## To set up a Universal Analytics property :-

```python

Click the Setting icon in the Admin area 
Property created 
Property Setup 
Set Up Reporting time zone
Set Up Currency
Click Show advanced options link 
Enable this Create a Universal Analytics property

```
### About  Your Business:-

```python

Added these details
Select Industry category 
Select Business Size
There are multple options we can select according to our business requrement. 
               How do you intend to use Google Analytics with your Business?
After Create
After Click Terms of Services

Next step is creating Data Streams:-
This traffic analysis tool can be implemented in the three platforms as mentioned in the enclosed image.

Select the Web 
Web can be  selected by the users in the WordPress and can also  edit website URL as in the image attached below

Set up your web stream like this 
To fill in your website’s URL and name
After enable Enhanced Measurement
After that, the tracking code or Id is provided to us.

Add the Analytics tag to your website to begin seeing data in your property.
Copy the global site tag into the <head> section of your HTML.
However, if you use a website builder (such as GoDaddy, Shopify, or others), tag your website using
------------------------------------------------------------------------------------------------------------
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-V72RB277Z9"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-V72RB277Z9');
</script>

------------------------------------------------------------------------------------------------------------
GA Id:-  G-V72RB277Z9


Tracking info-> Tracking Code              Tracking ID  UA-227563349-1
Below image dispaly this 
The Below enclosed image shows that the code is Implemented in head section in the website

Setup done after open Account 

```
