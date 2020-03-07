+++
author = "Fr. Jim"
categories = ["articles"]
tags = ["2020"]
date = "2020-03-07"
description = "Protect Your Family From Inappropriate Websites"
searchdesc = "In this article, I outline a quick and easy way to protect your family from inappropriate websites and internet content by using OpenDNS Family Shield DNS servers."
image = "/img/articles/family-shield/opendns.jpg"
featured = "familyaroundcomputer.jpg"
featuredpath = "/img/articles/family-shield"
featuredalt = "OpenDNS Family Shield"
linktitle = ""
title = "Open-DNS Family Shield"
type = "post"

+++

The internet is great. It makes everything we do easier. If I want to look something up real quick, I pull up my favorite search engine and BOOM, it's there! If I want to book a trip to the Holy Land, I just pull up my favorite travel app, and BOOM, I'm on my way. If I want to buy something cool, same thing, just hit up the right website, and I got what I need. The internet is pretty great, but it also has its drawbacks, which is the reason for this article.

There is a lot of content online that no one should ever have to see. This is particularly important for Christians, but especially important for families that want what's best for their children. Right now, there are entirely too many inappropriate websites, images, and videos online that can have a serious impact on us. Fortunately, there are tools available to help us filter out the bad stuff so we can have piece of mind while surfing the web in style. And I'm going to show you just how simple it is.

Grace to you and peace from God our Father and the Lord Jesus Christ. I'm Fr. Jim Smith and I'm so happy you decided to check out this topic. If you're a parent that cares about the safety of your children, I'm especially glad you're here. As the Catechism of the Catholic Church teaches, **_"Parents have the first responsibility for the education of their children" (CCC 2223)"_** And part of that education is in the moral life--teaching them how to discern what is good or bad, right or wrong. We all know there is an endless amount of inappropriate content online. We also know that it's super easy to stumble across it, even in a simple list of search results. So, what can we do about it?

![Image -size75](/img/articles/family-shield/opendns.jpg#center)  

OpenDNS Family Shield is an open source DNS provider that automatically blocks domains that are categorized as: Tasteless, Proxy/Anonymizer, Sexuality and Pornography. A DNS is a Domain Name System, which basically connects the simple names we use for websites like google.com with an IP address. Whenever we type in the website name, our computer connects to the DNS server to get the IP address, then forwards us to the site.

Why might we want to change our DNS server to something like OpenDNS? Well, most ISPs (Internet Service Providers) use their own DNS servers that pretty much allow full access to the internet. This is often preconfigured in the modem/router that we get from our ISP. Basically, if we are using our modem/router with the factory default settings, chances are the internet connection for the whole house is wide open. That means anyone connected to the router can access all kinds of content, and if you have small children at home, there is a ton of content you would not want them to see.

Fortunately, OpenDNS Family Shield allows us to use their DNS servers to filter some of the riff-raff. Obviously, this is only one step in a whole regimine of best practices for protecting yourself and family from inappropriate content, but it's a good first line of defense--especially if you can't afford a more robust subscription service. Of course, there is no better governor for the avoidance of inappropriate content than education. An informed mind helps to keep the heart pure.

So, let me show you just how easy it is to set this up on your home router.

The following has been adapted from the OpenDNS Family Shiled Guide at: https://support.opendns.com/hc/en-us/articles/228006487-FamilyShield-Router-Configuration-Instructions

---

# OpenDNS Family Shield Setup  

### General Router Configuration  

1. Login to your router's admin page  
Often, the admin page is accessible via web browser, usually a URL with numbers (example: http://192.168.0.1 or http://192.168.1.1 or http://192.168.2.1 or http://10.0.0.1). You will likely need a password.

   If you never set a password for your router, chances are it is still set to the factory default username and password. These are often found on a sticker on the side or bottom of your modem/router. Otherwise, a quick internet search should reveal the default username & password to access your modem/router's admin page.

   ![Image -size50](/img/articles/family-shield/netgear.png)

   If you set the router password a long time ago and cannot remember it now, you can often reset the password to the manufacturer default by pressing and holding the reset button on the router itself. (Keep in mind that resetting the router will also reset your Wi-Fi password for all devices on the network and any port forwarding settings you may have configured.)

*Note: Sometimes, preferences may be set via specific application for your router, which you may have installed on your computer when you set up the router.*

2. Find the DNS server settings.  
Under ISP/WAN settings there will be a field labeled DNS which allows two or three sets of numbers, each broken into four groups of one to three numbers. It might look like this:

   ![Image](/img/articles/family-shield/genericDNSfields.jpg)  
   _**Write down these numbers in case you ever need to revert back to the old settings.**_
3. Now, replace these numbers with the following FamilyShield OpenDNS server addresses and click save/apply.  
`208.67.222.123`  
`208.67.220.123`  
_**Make sure these are the only two addresses (if there is a third one, write it down, but delete it).**_
 
4. Test your Settings  
Browse to https://welcome.opendns.com/.  
If you have successfully set your public DNS to the OpenDNS servers, you will see "Welcome to OpenDNS!".
---
Now that you and your family are better protected online, let's have a pat on the back because you just saved your family from all kinds of evil.

Why might we want to avoid inappropriate 'adult' content online? Well, consider the spiritual effects of exercising the virtue of chastity. The Catechism of the Catholic Church defines _**chastity**_ as the successful integration of sexuality within the person and inner harmony between body and soul (cf. CCC 2337). The virtue of chastity comes under the cardinal virtue of _**temperance**_, which is all about self-mastery, i.e., ruling over our passions with reason, exercising mind over matter. St. Paul says, "Do not conform yourselves to this age but be transformed by the renewal of your mind, that you may discern what is the will of God, what is good and pleasing and perfect" (Rm. 12:2). Obviously, chastity is not something we can master in a day, but when practised daily, can lead to a more healthy sense of well being and comfort in one's own skin. Not only that, but self-denial is the first step to picking up our cross daily and following Christ (see Lk. 9:23ff).

When it comes to adult and pornographic content, the Catechism does not mince words:
> _**Pornography**_ is an offense against chastity because it perverts the conjugal act, the intimate giving of spouses to each other. It does grave injury to the dignity of its participants (actors, vendors, the public), since each one becomes an object of base pleasure and illicit profit for others. It immerses all who are involved in the illusion of a fantasy world. It is a grave offense. Civil authorities should prevent the production and distribution of pornographic materials (CCC 2354).

Psychologists have been researching the connection between pornography and addiction, especially in young men, and some research has shown that the effects on the brain of those who frequently view porn are similar to that of a person who is addicted to drugs or alcohol. In other words, exposure to pornographic content can lead to changes in our physiology and even act as a gateway to even more deviant and disordered affections. [WebMD on Pornography Addiction](https://www.webmd.com/sex/porn-addiction-possible#1)

### How Do I Exercise Chastity Daily?

1. Lock down your internet connection as outlined above.
2. Pray the Rosary. One of the best weapons against evil in our Catholic arsenal is the Rosary. Think about it. The Rosary is a series of prayers to the Blessed Mother, asking _**her**_ to pray for _**us**_. Mary is an excellent model of chastity and prayer. So, whenever your chastity is being tempted, go to Mary. She is always interceeding for us, especially when we ask.
3. Go to confession regurlarly. When we confess our sins, God not only forgives us of those sins, He gives us grace to overcome them in the future.
4. Receive Holy Communion regularly. If you can go to daily Mass during the week, it will really help keep you focused on Christ, who is the perfect model of chastity for everyone.

May the Lord give you His peace.

---