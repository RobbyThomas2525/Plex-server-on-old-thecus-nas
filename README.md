# Plex-server-on-old-thecus-nas
how i got plex server to run on my 2010 NAS everything should work as long as it's 
TheCus OS 5 32bit so these devices '1U4200XXX, 1U4600, N2200XXX, N3200XXX, N4100PRO, N4200, N4200Eco, N4200PRO, N5200XXX, N5500, N7700, N7700+, N7700PRO, N7700SAS, N8200XXX, N8800, N8800+, N8800PRO, N8800SAS. if not the guild should still work if you have TheCus OS 5 64 bit and 6 7 32 and 64 bit you just need to get it from archive.org instead of me here's the URL where i got it from
https://web.archive.org/web/20150423124637/http://www.thecus.com/sp_app_center.php

(Note for Plex) I am not associated in plex in any way also forget about plex supporting this it's from 2013 and there might be a security risk using this old of a version but anyways)

Step 1 download the .mod i have here or from my archive.org https://archive.org/details/Plex_0.9.7.28.33_x86_ForTheCusNAS if you need one for TheCus OS 5 64 bit and 6 7 32 and 64 bit i got my files from here https://web.archive.org/web/20150423124637/http://www.thecus.com/sp_app_center.php

step 2 go to module installion part on the NAS take the .mod files including ffmpeg and modcase and click the computer box with the + icon and select the files and click install and let it install after that enable the all the modules with either the small square or the the play button under the action section 

<img width="694" height="405" alt="image" src="https://github.com/user-attachments/assets/ba5b77f0-a471-477a-baeb-f2f46195b788" />

https://youtu.be/D3vO1IHt8wA?si=fPokbozZw4951pmG

step 3 after that you should be able to launch plex though (yourip):32400/ or though the module page it will have a setup page like this i don't think you need a plex account 

<img width="1055" height="761" alt="whatplexneeds" src="https://github.com/user-attachments/assets/49366f3b-8ba8-4275-8ed9-b742f2aed299" />

step 4 is ripping your media 

Update: i have desided now to use makemkv since i just realize it's a waste of time and space to try and do such high bitrate for 480P also it's a simpler tool and apparently free if your using it just for DVD also it has a linux port that also has a flatpak BUT IT'S UNVERIFIED https://flathub.org/en/apps/com.makemkv.MakeMKV 

They also have just a linux download from the makemkv site but to me it's way more complicated https://www.makemkv.com/download/

the steps for using are here from the makemkv site https://www.makemkv.com/onlinehelp/
or use this video from linus tech tips (if your ripping a dvd avoid 1:53-2:05 that's for blurays and also pick the titles you want if you want just the main movie it should be the biggest one)
https://youtu.be/GdQ5bClEgHg?si=uVpp8keOF9u4qho-&t=100


OLD POST: 'you can use makemkv i just use handbreak cause the linux version comes with software needed to break the DVD encryption i'm using these settings the RF you might have to change depending on the movie also i use H264 cause H265 and AV1 i'm sure is out of the question on these NAS and i'm only doing DVDs there's other videos online about it if you use someone elses video just make sure you use MKV as the format'

<img width="1920" height="1035" alt="Screenshot from 2026-01-05 13-36-25" src="https://github.com/user-attachments/assets/29ee5379-c5bb-421c-aa3f-4fe5a8827f3e" />

step 5 is adding the media to plex the way i do it is i make a media folder and add more folders in /raid0/data/ftproot and add the media though there after that go to the plex dashboard on your NAS and click the + icon and go though and put what media and what location to check after that it should work and the media should be up there in the dashboard 

<img width="948" height="326" alt="image" src="https://github.com/user-attachments/assets/f44c477c-2eef-4493-bc54-bd5a4656c97f" />

https://youtu.be/wq-W7blKmp0?si=I9GKzial3s7ImiBl

Last step last thing is to check to see if it worked only thing i'll say is the plex app won't find it cause again it's from 2013 and i guess the plex apps do not like the old verison your using the way you got to do it is use it with some sort of media server app so far i've tried it with the roku media app and just though the plex dashboard but there should be a way to work with everything TheCus has a guild with some stuff that might help in this case 

https://www.thecus.com/download/howtoguide/HowToGuide-Plex_en.pdf

