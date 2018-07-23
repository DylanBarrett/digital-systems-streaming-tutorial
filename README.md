# Streaming Tutorial / Resources - Zachary Kipping (zkp64)

## Overview
  This tutorial is going to go over everything you may need to start streaming on the web. This will be useful for anyone looking to stream for person or commercial use. Streaming is starting to become a large phenomenon on the internet and companies/individuals can make great use of it.

  Topics Included:

  * [Platforms](#platforms)
  * [Software](#software)
  * [Tools](#tools)
  * [Specs (Hardware/Internet)](#specs)
  * [Peripherals (Mics/Cameras/etc.)](#peripherals)
  * [Special Setups](#special-setups)
  * [Full Startup Guide](#full-startup-guide)

## Platforms
  * ### [Twitch](https://twitch.tv/)
    The hands down most popular streaming platform on the internet right now is currently Twitch.tv. This website exploded in growth back when it was known as Justin.tv. In early 2014 the website changed it's name to what it is today. Overall the website is about gaming related streaming, but recently has expanded it's horizons to include IRL, Music, Talkshows, etc...

    Twitch has a very active community and a plethora of developers actively making plugins, chatbots, and services to help aid in your streaming adventures. Not to mention Twitch itself is constantly striving to improve, with features like VOD saving/upload, a desktop app, a good notification system (looking at you youtube), and a great dashboard for everything you need to edit your stream/profile.

    I'll be using Twitch.tv for the basis of showing how to setup our software later on and getting ourselves live on the web.
  
  * ### [Youtube Gaming](https://gaming.youtube.com/)
    As opposed to just uploading videos, Youtube started allowing users with over 1000 subscribers in May of 2013. Throughout the year it slowly reduced this limit. In 2017 Youtube also allowed users to stream using it's mobile app. Twitch definitely is more popular, at least with gamers, but youtube is also more lax with it's TOS which can be a big draw to many users in the current Twitch atmosphere. Plus who doesn't know about youtube in this day and age?

    I won't be using Youtube for my examples later on, but it is actually quite simple to setup. See this [link](https://support.google.com/youtubegaming/answer/6305973?hl=en) if this seems interesting to you. It's an official guide by Google on how to get up and running with their streaming service.

  * ### [Mixer](https://mixer.com/)
    In 2016 Microsoft decided to join the excitement and created their own streaming platform. Microsoft bought out the formerly known service Beam to compete with other popular streaming services. One nice reason to use Mixer is that it is intergrated into the Xbox One dashboard. Mixer focused primarily on gaming like many of it's competitors, but one shining feature is that unlike other chat interactions; mixer allows for users to press actual buttons on the side of the stream to interact with games. So instead of sending very particular messages in a chat for a bot to read, you can quite simply press buttons to interact + chat normally to talk with the streamer.

  These three services are the top dops right now. There are obviously others but none of them pull in anywhere close to the consisten number that streamers on the above services can achieve.

## Software
  * ### [OBS](https://obsproject.com/)
    OBS or "Open Broadcast Software" is one of the more popular streaming softwares available, especially on Twitch. This is the software I will be using in my example later on. OBS allows for countless scenes, keybinding for everything, easy to make re-usable sources, along with a plethora of settings. OBS also allows for plugins and other 3rd party services to create add-ons for their software (see [StreamsLabs](#streamlabs) below in tools). Along with streaming, you can also record. You can do this at the same time or completely seperately. Personally I use OBS for recording as well since all your scenes can be used for either.

    As a note of warning OBS can be pretty resource intensive if you are not careful. Since it has so many options, it can take a lot of fine tuning/optimizations to create a good stream experience for your viewers while keeping your computer from seeing blue. Some of the below examples are more lightweight and are better for rigs that can't handle OBS + an activity (also see [Special Setups](#special-setups) below as well).

  * ### [XSplit](https://www.xsplit.com/)
    XSplit is a great alternative to OBS. It has been around for a very long time as a resource for gamers, originally used just for recording. Currently with XSplit you have two options: Broadcaster or Gamecaster.

    Broadcaster is the more verbose of the two services XSplit provides. It is meant for those looking for a more professional & advanced setup that allows for a great amount of customizability. Broadcaster can be used for either streaming or recording.

    Gamecaster allows for easy setup and go streaming for gamers. It has easy access to many stream controls, plugins, and social media. It may be less customizable compared to Broadcaster, but it's widget system allows for adding everything you might need to get your stream up and running quickly.

    XSplit as compared to OBS or Bebo isn't free though. If you want to use it commercially you will have pay at most $8.32 a month (based on current pricing of a 3 month license). You can use it for free of course, but the capabilities are hindered.

  * ### [Bebo](https://bebo.com/)
    Bebo is a new streaming app that is trying to making streaming easier and less messy compared to its competitors. Bebo combines all the best plugins, extensions, and services right into its app. This makes it a one stop shop for getting up and running with your stream. You can make use of scenes, chat, stats, alerts, and your video feed all on one screen. Plus it's layout is completely customizable. Bebo's integration with a lot of your favorite apps makes it a great new comer into the realm of streaming software and is definitely one I am going to keep my eye on.

## Tools
  * ### [StreamLabs](https://streamlabs.com/)
    StreamLabs is one of the most popular stream tools available currently (slightly better or tied with [StreamElements](#streamelements)). It is used by a lot of the top streamers on Twitch. This will be the tool I will be implementing in my [Full Start Guide](#full-start-guide). 
    
    StreamLabs allows for easy to use alerts, stats, and chat bots. StreamLabs also has a full desktop app that is integrated ontop of OBS allowing for the ultimate streaming experience. This desktop app comes with 1000s of free themes and can help you get up and running quick.
    
    StreamLabs integration with OBS allows for better game specific video encoding and less CPU usage on average. Along with this the desktop app allows for a single live view of everything going on with your app: Video feed, chat, stats, alerts, and OBS settings. 

    Unfortunately the desktop app is only available for Windows, while OBS in general is available for Mac and Linux as well. You can also use the website version, but it obviously won't be integrated into OBS for you. The website version is still fantastic and provides a similar live dashboard with alerts and settings.

  * ### [StreamElements](https://streamelements.com/)
    StreamElements is very similar in terms of functionality provided to its users compared to StreamLabs. Both of the services are extremely good and its purely up to your discretion which one you pick up and stick with. 

    StreamElements comes with a handy customizable chatbot. It has a cool module system that allows for drag and drop functionality for making your chatbot better in all sorts of ways. It also has a vast library of themes to get your stream up and running, while looking good in the process. It also has a custom overlay system that boats "unrivaled management of your overlays". It allows for saving of setups to your account so you can stream anywhere and everywhere you have an internet connection. 

  * ### [Muxy](https://muxy.io/)
    Muxy is more unique in that it isn't as large as the two services mentioned above but it does very well in its niche userbase. It has great custom alerts, cheer cups, and plenty of extensions to help you and your stream. It has great integration with Esports and Brand analytics; great for teams or event organizers. 

    Muxy also has an extensive development kit that allows for a lot of customizability in creating twitch extensions. They have a lot of templates you can use, allow for the creation of your own, or you can even hire them out for special requests.

## Specs
  The core parts of your spec for streaming are going to be your CPU and GPU.

  ### CPU
  The CPU is probably the most important component for streaming. It allows for the encoding of your game frames that are being sent to your streaming platform. If your CPU isn't good enough and you crank up your encoding your gameplay will suffer, less encoding and your gameplay will be better but your stream quality will be worse. It can be a hard sword to balance between good encoding and good FPS. You will want to pour the majority of your budget into your CPU and I would only recommend getting Intel Core i7's or better. The more cores you can get, the faster your encoding will be since the work loads are split into different threads. Anything above an i7 in the 4000 range will be sufficient for streaming. Obviously if you get can get better, than get better. **Always** remember the more cores the better even if it means getting an older CPU compared to a newer version with less cores.
  
  I **would not** recommend AMD for streaming since even the newest have low IPC performance compared to even 3-4 year old Intel CPUs.

  ### GPU
  The second most important part of streaming would be your GPU. If you are using any of the above streaming softwares then they will be eating at your GPU to do compositing of layers, scaling, and other actions. If your GPU isn't good enough this will start heavily affecting your FPS in your games as well and start ruining any quality you have in your stream. Nvidia or AMD are fine for GPUs. Anything above a GTX 700 or Radeon 7000 will be sufficient.

  If you want to be playing the newest and flashiest games though, you may need to consider investing more and getting a more top of the line GPU to keep your FPS and Quality at a solid level.

  ### RAM
  Most streaming apps can be very memory intensive (although this has gotten better with time and plenty of updates). I would suggest having **at least** 8 GB of RAM. If you can splurge for 16 GB all the better. This will allow you to push the boundaries of streaming quality while still being able to run everything else (games, browsers, etc...). This isn't as important nowadays, but if your software (OBS for example) has a lot of plugins it can start to eat up memory. It really depends on the type of user you are with how much RAM you will need. More often than not 8GB of RAM will be plenty, but in some cases more could be needed. RAM is one of the less important parts, so make sure to focus on your CPU and GPU first.

  ### Motherboard
  Motherboards don't have much of an impact on your streaming performance. Just make sure to get on that is reliable since you may be streaming for long periods of time. Also, take into consideration if you want to overclock your CPU you may want to look into motherboards that are better at this.
  
  ### Internet
  Along with hardware specs you need to take into account your internet. Your internet can literally make or break your stream. No matter how fancy your computer/setup is if you don't have reliable and good enough rates, you won't be streaming at a good quality. The better the upload speed you can get, the higher the bitrate you can stream at. Careful though, because if you go too high people with lower download rates may not be able to view your stream without buffering a lot.
 
  I don't know about you but in general I try to avoid more complex math if I can. So, I usually use a [online calculator](https://www.chow-bryant.com/services/social-media-marketing/live-streaming/live-streaming-calculator/) of sorts to figure out my optimal streaming bit rate. Using the link the online calculator I provided, you can enter in your information and get a good idea of what kind of internet plan you are going to have to shell out for. 

  In general if you want to save on having a lower Upload speed, downsizing your video resolution can be a great asset to you. I usually opt for downscaling to 1280x720, but it might take experimentation with different resolutions to find one that suits your needs. 
  
  Your fps is really going to depend on what type of game you are playing and each have their trade-offs in quality vs fluidity. I either go with 30 fps for FPS games or any game with a lot of particle effects (like an mmo or similar). With games that are slower or have a lot of still frames (think card games or point&clicks) 60 fps will help with overall quality of each frame. Obviously if you can afford the higher bitrate try to stream at 60fps always since your viewers will get much better quality & fluidity.

  I usually recommend a bitrate in the 3000s for good quality and less choppyness, so using the max audio bit rate of 96 (at least for twitch's recommendations) you end up with a video bit rate at around 100 less than your full stream bitrate.

  So for example if I put in some of the examples above:
   * 1280x720
   * 30 fps
   * 96 audio bit rate

  I end up with a video bit rate of around 2850 and a required internet Upload plan of 3.576 Mbps. Earlier I recommended around 3000-4000 for most people. This is because the higher bitrate after your minimum will help reduce choppyness of frames for your viewers. With a 3500 bitrate I would recommend around a 5 Mbps upload plan. Nothing outrageous, but still very necessary. If you want to start streaming in full 1920x1080 with 60 fps it the Mbps start to add up fast.

  In terms of download rate, just make sure your rates/ping are good enough and consistent enough to be a good viewing and playing experience for everyone. Plus if you ever need to download a game on the fly, having 100 Mbps down can really help tackle that problem. 
  
  Also **please** make sure to vet your ISPs thoroughly and get familiar with calling their support lines if necessary. Having your internet throttled or go out in the middle of a stream can be embarrassing for starters, but also catastrophic for maintaining viewership.

## Peripherals
  ### Audio
  #### Mic
  Your mic is going to be an important part of your streaming setup and spending the extra money here can really help you seem more professional. I would **highly** recommend getting an actual professional grade mic with a pop filter and the works. One that is on a moveable stand can help a lot with adjusting distance and position.

  Headset mics can work, if you have no other options. Just be aware that a lot of background noise might be picked up, which can be annoying for viewers. Having a crisp clear voice while streaming makes the experience all the better. In the (Startup Guide)[#full-startup-guide] I go into methods for making a headset mic work decently well.

  The actual mic itself is up to you and the amount of money you are willing to spend. Company wise I will always recommend [Audio Technica](https://www.audio-technica.com/cgi-bin/product_search/wired_mics/mics_by_type.pl?product_type=Microphones%3A+Side-address&lang=eng). That link has a good list of side-address mics which will be your best best. This will help with only picking up your voice and limit background noise. Make sure to get a pop filter and a long enough mount.

  #### Mixer
  In many cases a mixer can be helpful as well. It can help monitor audio levels, limit peaking, and do a lot of filtering/cleaning up of audio for you. Using this would be opposed to using a lot of the settings in OBS, but with better quality usually. Again I would recommend against using Behringer mixers since a lot of users report low quality with their preamps and faders.

  I would suggest mainly getting some kind of USB mixer, since it consolidates all inputs into one master stereo, which can be very useful. Plus it obviously uses an USB output. [Mackie](https://www.amazon.com/Mackie-Mix-Mix8-8-Channel-Mixer/dp/B00ND1KGEI/ref=sr_1_1?s=musical-instruments&ie=UTF8&qid=1454090497&sr=1-1&keywords=mackie+mixer) is supposedly a decent enough company, you may want to do your own research though.

  You may also want to consider using a [Virtual Mixer](https://www.google.com/search?q=virtual+mixer&oq=Virtual+mixer&aqs=chrome.0.0l6.1512j0j4&sourceid=chrome&ie=UTF-8). This will mean using a program on your computer instead of a physical device. This can be easier if you don't need to have a ton of different physical mics/cameras running through one device. So, if you are just starting out this may be the best path.

  ### Camera
  In the current age most people will expect to see a facecam in your stream. Obviously you can get by without it (Lirik) but it can help improve connections made with your stream and make you more personable.

  [Logitech](https://www.logitech.com/en-us/video/webcams) has some of the best webcams for streaming currently; so, I would highly recommend checking out their list. It's up to you what you want to buy. Just remember what type of quality your streaming at. If it's 60 fps, sure go for the super high quality camera where you can see your pores. If you are at 30 fps, consider somethin on the lower end, otherwise their might be a lot of tearing since your quality can't keep up. Your bit rate also matters for a lot in this.

  ### Monitors
  I have no real recommendation for monitors, since that it personal preference. This is mostly a side note to **really** consider having two monitors at a **bare** minimum. This allows for one monitor to be your content/what the viewer sees and the other allows for you to see your streaming software/chat/etc... This makes for a much easier time streaming and a cleaner workflow.

## Special Setups
  Dual computer setups can be very beneficial for hardcore streamers. This allows for having one dedicated PC for streaming and gaming respectively. This way all the streaming software and encoding doesn't drag down the performance of your gaming setup. This setup makes use of capture cards to get the feed from your gaming PC to your streaming PC. So, it is definitely worth the trouble, but only if you need the upmost quality/performance and are willing to drop quite a substantial amount of money.

  Twitch themselves have a article going into depth about how to go about setting up dual pcs for streaming. https://help.twitch.tv/customer/en/portal/articles/1988680-broadcasting-with-two-computers

## Full Startup Guide

