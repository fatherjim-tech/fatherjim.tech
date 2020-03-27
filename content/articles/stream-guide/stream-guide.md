+++
author = "Fr. Jim"
categories = ["articles"]
tags = ["2020", "guides"]
date = "2020-03-24"
description = "Broadcast Liturgies to Your Congregation"
searchdesc = "In this article, I show how to use a smartphone or other mobile device to capture and broadcast streaming video for YouTube and Twitch through Restream.io."
image = "/img/articles/stream-guide/father-jim-tech-live-stream-guide.jpg"
featured = "father-jim-tech-live-stream-guide.jpg"
featuredpath = "/img/articles/stream-guide"
featuredalt = "Father Jim Live Streaming Guide"
linktitle = ""
title = "Live Streaming Guide"
type = "post"
format = "article"

+++

# A Ministry of Digital Presence

It's a digital world. Everywhere you look, we're surrounded by screens. From billboards to checkout counters to living rooms to dashboards to pockets, the virtual world is all around us. Families spend time around the television watching their favorites movies, friends keep in touch by sending each other pictures and snaps, distant relatives stay connected through social media, and much of our news comes to us through similar means. No matter where we are, we're only a screen away from what's happening at any given moment.

But, what if we were only a screen away from what's happening at our local parish, too? What if the pastor could give a special message in real time and reach a broad range of parishioners? What if the parish wanted to stream the Holy Sacrifice of the Mass for the homebound? This can all be done using a simple platform called Restream.io. Restream.io is a streaming service that acts as a hub for all your streaming video content. The best part is once it is configured, a single stream can be sent to multiple platforms including Facebook Live, YouTube, Twitch, and many more.

If you have a tablet, smartphone, or mobile device with a camera and microphone, chances are you can stream video from that device. All that's needed is an app called StreamLabs and a few accounts on popular streaming platforms. The following is a step-by-step guide to showing how to capture video with a mobile device and stream it to YouTube and Twitch with Restream.io.

---

# Table of Contents
*Please use these links to quickly jump to each section. Use the browser's back button to return to this menu.*  

1. [Create Accounts](#create-accounts)

2. [Configure Accounts](#configure-accounts)
    1. [YouTube](#configure-youtube)
    2. [Twitch](#configure-twitch)
    3. [Restream](#configure-restream)

3. [Configure YouTube Stream Now](#youtube-live)

4. [Configure StreamLabs](#configure-streamlabs)

5. [Testing The Stream](#stream-test)

6. [Our First Stream](#first-stream)

7. [Additional Considerations](#additional-considerations)
# <a name="create-accounts"></a>

---

# Step 1 - Create Accounts

## Restream
This is the service we will use to connect our stream to Facebook Live, YouTube, and other platforms.
[{{< img-post-width "/img/articles/stream-guide/" "restream-login.jpg" "text" "" "60%">}}](https://restream.io/signup)

## YouTube
YouTube is one of the most popular video sharing platforms in the world. Most mobile devices come with YouTube pre-installed.
Since this is a Google service, you will need to create a Google account. I would suggest creating a business account so others can be added as account managers.
[{{< img-post-width "/img/articles/stream-guide/" "youtube-create-account.jpg" "text" "" "40%">}}](https://accounts.google.com/signup)
## Twitch
This is one of the most popular streaming platforms. People from all over the world use Twitch to share their video game streams and other content. Twitch was designed for live streaming, so it is one of the best platforms for it.
[{{< img-post-width "/img/articles/stream-guide/" "twitch-login.jpg" "text" "" "35%">}}](https://twitch.tv)
# <a name="configure-accounts"></a>

---
# <a name="configure-youtube"></a>

# Step 2 - Configure Accounts

## YouTube Initial Configuration
After we create our Google account, we will need to login to YouTube and create a new channel. Click the icon on the top right of the screen and then click **Settings**.
{{< img-post-width "/img/articles/stream-guide/" "youtube-menu-settings.jpg" "text" "" "90%">}}

Click the link in the center of the page to **Add or manage your channels**.
{{< img-post-width "/img/articles/stream-guide/" "youtube-add-channel.jpg" "text" "" "90%">}}

Click **Create a new channel** and give the channel a name.
{{< img-post-width "/img/articles/stream-guide/" "youtube-create-channel.jpg" "text" "" "40%">}}

Once our channel has been created, use the dropdown menu and click on **Your channel**, then click the **customize channel** button.
{{< img-post-width "/img/articles/stream-guide/" "youtube-customize-channel.jpg" "text" "" "90%">}}

There is a lot we can do here to enhance the look of the channel. Start by adding channel graphics such as the icon and banner. Then click on the **About** tab and add a description for our organization, e-mail, and website address.
{{< img-post-width "/img/articles/stream-guide/" "youtube-channel-about.jpg" "text" "" "90%">}}
*For more information on image dimensions for channel art, please visit this [YouTube Help](https://support.google.com/youtube/answer/2972003?hl=en) article.*

# <a name="configure-twitch"></a>
## Twitch Initial Configuration
After creating our Twitch account, click the icon on the top right of the screen and then click **Settings**.
{{< img-post-width "/img/articles/stream-guide/" "twitch-menu-settings.jpg" "text" "" "90%">}}

On the **Profile** tab, we can upload channel graphics such as our profile picture and banner (in some cases we can use the same banner art that we uploaded to YouTube). Next, add a bio for the organization and click the check mark to save.
{{< img-post-width "/img/articles/stream-guide/" "twitch-settings-profile.jpg" "text" "" "70%">}}

Next, click the **Channel and Videos** tab and set the option to record past broadcasts. Turning this ***on*** will cause an archived copy of our stream to be stored on Twitch so others can view it again.
{{< img-post-width "/img/articles/stream-guide/" "twitch-settings-channel-store-past-broadcasts.jpg" "text" "" "70%">}}

Also, within the same section, scroll down to **Video Player Banner**. This is an image that will appear on our channel whenever we are not streaming. A 1920x1080 pixel image is recommended so that it fits the aspect ratio of most HD mobile devices.
{{< img-post-width "/img/articles/stream-guide/" "twitch-video-player-banner.jpg" "text" "" "70%">}}

Lastly, we'll add some basic info to the bottom of our channel. Navigate to twitch.tv/YOURCHANNELNAME (where YOURCHANNELNAME is the name you chose for your channel). Under the video window, click the **Edit Panels** switch. Then, click the **+** and **Add a Text or Image Panel**.
{{< img-post-width "/img/articles/stream-guide/" "twitch-edit-panels.jpg" "text" "" "70%">}}

Upload a logo or icon, provide a link to the website, and a brief description.
{{< img-post-width "/img/articles/stream-guide/" "twitch-add-panel-text.jpg" "text" "" "30%">}}
# <a name="configure-restream"></a>
# Restream Initial Configuration

Now that our YouTube and Twich accounts have been configured, it's time to connect them to Restream.io. On the Restream welcome page, click the **Add Channel** button.
{{< img-post-width "/img/articles/stream-guide/" "restream-welcome-add-channel.jpg" "text" "" "70%">}}

This menu is used to connect our accounts to Restream.io. We can connect to multiple platforms from here. To connect our account, we must be logged into that account on the same browser. Let's start with YouTube. Click the **YouTube Stream Now** button.
{{< img-post-width "/img/articles/stream-guide/" "restream-add-channel.jpg" "text" "" "70%">}}

Then click **Connect YouTube Stream Now**.
{{< img-post-width "/img/articles/stream-guide/" "restream-connect-youtube.jpg" "text" "" "60%">}}

Google will ask if we want to allow Restream to access our account. This will allow Restream to stream directly to our account, and update the title text on the live stream. To allow this connection, click **Allow**.
{{< img-post-width "/img/articles/stream-guide/" "youtube-restream-allow-access.jpg" "text" "" "35%">}}

After connecting our YouTube account, Restream will show an error. This is because we have not yet setup the live streaming on YouTube. Simply click **Visit YouTube & Retry** to do so, then follow the instructions for configuring your YouTube livestream below.
{{< img-post-width "/img/articles/stream-guide/" "restream-oops.jpg" "text" "" "50%">}}

The Restream dashboard now shows we have a connection to YouTube.
{{< img-post-width "/img/articles/stream-guide/" "restream-youtube-successfully-added.jpg" "text" "" "70%">}}
From this point, you can click **Add Channel** to add Facebook Live, Twitch, or any other platform offered by Restream. Follow the same steps as above to connect each account.
# <a name="youtube-live"></a>
---
# Step 3 - Configure YouTube Stream Now
Just like Twitch, we can also add text and graphics to our stream. Click [here](https://www.youtube.com/live_dashboard) to visit your Live Dashboard. From here, we can change the thumbnail, title, description, and privacy. YouTube uses our channel banner by default, but we can upload something else, perhaps an image with the word "live" so viewers will know that we're live. It is recommended to set the privacy to **Public** otherwise no one will be able to see the stream live.
{{< img-post-width "/img/articles/stream-guide/" "youtube-live-backend.jpg" "text" "" "90%">}}

Here is an example description including a regular streaming schedule and a link to our website. When finished updating basic information, click on the **Advanced settings** link.
{{< img-post-width "/img/articles/stream-guide/" "youtube-live-description.jpg" "text" "" "60%">}}

There are several items for consideration on the Advanced settings tab. If hundreds of viewers are anticipated, it may be good to enable slow mode under chat. This will reduce the speed at which everyone's chat comments appear. We may also want to set the video language. Under Recording, be sure to check ***Automatically make archive unlisted once the stream has ended***. This will give us an opportunity to edit the video after the stream. Also, set the comment filter accordingly. Then, check **Enable DVR**, which will make it so viewers who come late to the stream can scrub back to the beginning. Finally, set the stream optimization. *Normal latency* will yield the highest quality, but adds a longer delay. *Low-latency* is the default, and works well for live interaction with the audience through chat.
{{< img-post-width "/img/articles/stream-guide/" "youtube-live-backend-advanced.jpg" "text" "" "90%">}}

Lastly, back on the Live Dashboard, scroll down to the bottom to reveal the link to the live stream. This is good for posting on our website or social media sites.
{{< img-post-width "/img/articles/stream-guide/" "youtube-live-backend-link.jpg" "text" "" "50%">}}
# <a name="configure-streamlabs"></a>
---
# Step 4 - Install & Configure StreamLabs
### On Android & iOS Devices
Now it's time to install an app on our mobile device. [StreamLabs](https://streamlabs.com/) is FOSS (Free & Open Source Software) powered by [Open Broadcaster Software](https://obsproject.com/) (OBS for short), which enables us to easily capture video & audio from our mobile device and stream it to any platform. We will use StreamLabs to connect to Restream.io so we can stream to multiple platforms at once.

From the Play Store or App Store, we'll search for StreamLabs and install it on our device.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-install.jpg" "text" "" "30%">}}

Launch Streamlabs and click on the link for **Other Platforms**
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-log-in.jpg" "text" "" "30%">}}

To connect Streamlabs to our Restream account, we will need the URL and stream key from our Restream Dashboard. (To reveal the stream key, just click on the dots.)
{{< img-post-width "/img/articles/stream-guide/" "restream-url-and-stream-key.jpg" "text" "" "90%">}}

On our mobile device, enter the URL and stream key into Streamlabs and tap **continue**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-url-and-stream-key.jpg" "text" "" "60%">}}

Be sure to **Enable Camera & Mic**, otherwise we will not be able to capture from those devices.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-camera-mic-permissions.jpg" "text" "" "60%">}}


This is the main window, but it's not configured to stream anything yet. Let's set that up. Tap the pancake menu to reveal additional settings.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-main.jpg" "text" "" "60%">}}

Next, tap **Editor**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-main-menu-editor.jpg" "text" "" "60%">}}

From here, we will create a new scene (just like the desktop version of OBS). Let's add a camera layer by tapping the **+**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-editor.jpg" "text" "" "60%">}}

Then tap **Add Camera**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-add-camera.jpg" "text" "" "60%">}}

The camera should now display on the screen. Tap the check mark to accept the changes.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-add-camera2.jpg" "text" "" "60%">}}

We can resize the window by dragging the corners as needed. The default is full screen. Once again, tap the check mark to save and retun to the main window.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-add-camera3.jpg" "text" "" "60%">}}

One last setting is to move the StreamLabs watermark to a more reasonable location. From the Main Menu, tap **Settings**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-main-menu-settings.jpg" "text" "" "60%">}}

Scroll down to **Watermark placement**...
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-settings-menu.jpg" "text" "" "60%">}}

...and set it to **Bottom Left**.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-watermark-placement.jpg" "text" "" "60%">}}

We are now ready to test our stream.
# <a name="stream-test"></a>
---
# Step 5 - Testing The Stream

Before testing the stream, go to the Restream Dashboard and flip the switches next to each platform to the off position. This will prevent our test stream from going out to YouTube or Twitch. We will turn them back on when it's time to go live.
{{< img-post-width "/img/articles/stream-guide/" "restream-test-stream.jpg" "text" "" "90%">}}

To begin broadcasting from our mobile device, tap the red record button on the Streamlabs main window.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-ready-to-stream.jpg" "text" "" "60%">}}

Take note of the stream connection health in the bottom right of the screen (this will not appear on the broadcast). This should be as close to full bars as possible. Also, take note of the average frames per second and bitrate. You'll want to ensure your device is streaming at a minimum of ***24 fps, 3000kbps***.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-test-stream-good.jpg" "text" "" "60%">}}

For poor connection speeds, please see the [additional considerations](#additional-considerations) below for tips on how to improve your connection.
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-poor-connection.jpg" "text" "" "60%">}}
# <a name="first-stream"></a>
---
# Step 6 - Our First Stream
Now that the stream has been tested and working. It's time to title our stream. From the Restream Dashboard, click the title tab, enter a title, and click **Update All**. This will change the title of our live stream on each of the platforms below.
{{< img-post-width "/img/articles/stream-guide/" "restream-titles.jpg" "text" "" "90%">}}

From the social tab we can send a message to all social media accounts connected to Restream.
{{< img-post-width "/img/articles/stream-guide/" "restream-socials.jpg" "text" "" "90%">}}

Finally, on the Dashboard tab, be sure to toggle all channels back **on**. Otherwise, the stream will not be broadcast to those platforms.
{{< img-post-width "/img/articles/stream-guide/" "restream-toggle-on.jpg" "text" "" "90%">}}

We did it! Highfive! Now, whenever we tap record on our Streamlabs app we will be live on YouTube and Twitch.
{{< img-post-width "/img/articles/stream-guide/" "highfive.gif" "text" "" "30%">}}
# <a name="additional-considerations"></a>
---
# Additional Considerations
### Power
When recording anything live, especially with a mobile device, it is always best to have the device connected to its charger and pluged into the wall. The camera, Wi-Fi antenna, and screen working simultaneously will quickly drain the battery. Be sure to properly power the device so as to avoid unwanted interruption due to battery drain.

### WiFi Connection
I recommend putting mobile devices in **Airplane** mode, then manually enabling Wi-Fi. Most mobile networks have been known to throttle mobile data connections. This can greatly affect the quality of the stream. Wi-Fi will provide a much more reliable and stable connection without the bandwidth constrictions of mobile data. With mobile data disabled, Streamlabs will automatically use the Wi-Fi connection. 
{{< img-post-width "/img/articles/stream-guide/" "streamlabs-poor-connection.jpg" "text" "" "60%">}}

### Lighting
When it comes to capturing a clear image, lighting is everything. Perhaps that's why the first words God speaks in the Bible are, "Let there be light." And lo, lots of light for any camera is good.

Whenever possible, try to avoid low-light correction from a mobile device. While this may look okay on the mobile device, but it will be different on a computer screen or television. Often, the picture quality will appear grainy and washed out on larger screens.

### Sound
There is no substitute for good sound. When God said, "Let there be light," the light heard and responded with its brightness and splendor. Many of the microphones on mobile devices are decent, but far from perfect. So, be sure to speak loudly and clearly when relying on the built-in microphone.

For better results, an inexpensive wireless lavalier microphone can often make a world of difference. Click [here](https://www.amazon.com/Wireless-Lapel-Microphone-System-Conference/dp/B07Y45TCVJ/ref=sr_1_17?keywords=wireless+lavalier+microphone+for+iphone&qid=1585108979&sr=8-17) for an example of a dual wireless setup for mobile devices.

---
