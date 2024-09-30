---
title: "A Step-by-Step Guide: Updating Your Kindle Fire's Built-In Thesaurus and Dictionary"
date: 2024-09-26T17:05:47.189Z
updated: 2024-09-30T18:46:13.610Z
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/d63b36b5c666fd9de9fccce4561bf07299ad84d3949b489b0214f6877268e346.png
---

## A Step-by-Step Guide: Updating Your Kindle Fire's Built-In Thesaurus and Dictionary

## How to Replace Kindle Fire Dictionary

Posted by [Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) on 11/30/2018 10:26:27 AM.

4.5 [(6 comments)](http://www.epubor.com/#comment-area) 

![follow](http://www.epubor.com/images/follow.png)

Kindle Fire is not only a great e-book reader but also a good tool for learning English. By tapping any words in the book, we can easily learn its detailed meaning and related expression. But it's a bit pity that you can't switch from one dictionary to another when looking up a word which you can do on Kindle and Kindle Paperwhite. This is because the Kindle Fire has only one dictionary by default and it has no options for you to add or change any dictionaries. Although the built-in New Oxford American Dictionary is enough for some degrees, some people want to use a more professional or specialized dictionary, especially those who want to learn a foreign language like Chinese, but not English. So we need to replace Kindle Fire dictionary.

As we mentioned above, Amazon doesn't want us to change the Kindle Fire default dictionary. So we need some hackings to modify the system files. Yes, you may have realized it – You need root your Kindle Fire. If you haven't rooted your device, check out these two rooting tutorials:

1\. [How to root Kindle Fire](https://tools.techidaily.com/epubor/products/)

2\. [Root Kindle Fire with one click](http://ebookconverter.blogspot.com/2013/07/root-kindle-fire-with-one-click.html)

PS: Our tutorial can only replace the default dictionary as Kindle Fire only supports one dictionary. You can't choose an alternative dictionary.

1 Get your dictionaries 

We can purchase dictionaries from Amazon Kindle Store. But most of them are paid ones. Actually there are many free dictionaries on the Internet. Download a dictionary with a suffix "**mobi**" or "**prc**". Rename it as "**B003ODIZL6**" and change its file extension to "**prc**". Then transfer the dictionary to your Kindle Fire. Here I choose the **Oxford English-Chinese Dictionary** for example. 

2 Modify system file 

Reboot your Kindle Fire and then open ES File Explorer. Find the new dictionary file you get in step1 and long tap to copy it. 

![copy-dictionary-file](https://www.epubor.com/images/uppic/1-copy-dictionary-file.jpg)

Then navigate to this path: **/system/etc/labdictionary**. You can find two files here: B003ODIZL6.prc and Kindle\_User\_Guide.prc. Tap the Fast Access icon and choose "**Tools**" – "**Root Explorer**" – "**Mount R/W**" and set all the paths to "**RW**" permission. Then rename the "**B003ODIZL6.prc**" as "**B003ODIZL6.prc.bak**".

![find-default-dictionary](https://www.epubor.com/images/uppic/2-find-default-dictionary.jpg)

![modify-system-permission](https://www.epubor.com/images/uppic/3-modify-system-permission.jpg)

![rename-default-dicionary-file](https://www.epubor.com/images/uppic/4-rename-default-dicionary-file.jpg)

Tap the Clipboard icon and choose "Paste". Long tap the new "B003ODIZL6.prc" file and choose "**More**" – "**Properties**" – "**Permissions**: **Change**". Set the permissions like this and click "OK" to confirm.

![paste-new-dictionary-here](https://www.epubor.com/images/uppic/5-paste-new-dictionary-here.jpg)

![change-permission](https://www.epubor.com/images/uppic/6-change-permission.jpg)

3 Test new dictionary 

Now open an e-book and tap any words, you can find its explaining has changed into Chinese, that means the new dictionary works! 

![replace-kindle-fire-dictionary](https://www.epubor.com/images/uppic/7-new-dictionary-works.jpg)

If you want to change back to the default dictionary, just delete the "B003ODIZL6.prc" at the directory: **/system/etc/labdictionary** and rename the "B003ODIZL6.prc.bak" as "B003ODIZL6.prc". Then reboot the Kindle Fire and you can find the Oxford dictionary comes back.

![author](https://www.epubor.com/images/uppic/jonny.png)

[Jonny Greenwood](https://plus.google.com/u/0/+JonnyGreenwood999) joined Epubor since 2011, loves everything about eBooks and eReaders. He seeks the methods to read eBooks more freely and wants to share all he has got with you.

SHARING IS GREAT!

[Tweet](https://twitter.com/share) 

[SAVE PAGE AS PDF](https://tools.techidaily.com/epubor/products/) 

6 Comments

[reply](https://tools.techidaily.com/epubor/products/) 

[reply](https://tools.techidaily.com/epubor/products/) 

Kt

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

11/24/2013 16:24:46

I rooted the device and changed the dictionary but at the end of step 2 you say to change the file properties to this: and then there is no photo explaining. when i try to use the dictionary it is blank and i don't know if it's because of the file properties or because of the dictionary file itself. please write the properties or take a picture :) thank you

[reply](https://tools.techidaily.com/epubor/products/) 

jose luis

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

02/28/2014 22:15:34

hi, thanks for your tutorial, but i have a problem, i do it evething like images and change the dictionary but when i boot it eraseand no appears any definition, like no dictionary

 "Properties" – "Permissions: Change". Set the permissions like this which one exactly are the options we have to put

 thank you again for the tutorial really helps alot!!!

[reply](https://tools.techidaily.com/epubor/products/) 

Alex

[Re:How to replace Kindle Fire dictionary](https://tools.techidaily.com/epubor/products/)

07/11/2014 14:06:07

Thanks for tutorial it helped a lot.  
 P.S  
 I have set the new dictionary's permissions similar to old one's and it worked for me.  
 you should check "read" for 'owner', 'group' and 'other', and you should check "write" for 'owner'.  
 everything besides these options should be unchecked.   
 If you didn't understand what i wrote, you can simply check for the permissions for old dictionary  
 and copy them to new dictionary's permissions.  
 Hope it helped, sorry for bad english

[reply](https://tools.techidaily.com/epubor/products/) 

William Sanderson

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

02/5/2015 01:20:10

An amazing tutorial. I have followed all the steps with no problem.

 All went well until I arrived at /system/etc/labdictionary section. The two files mentioned do not exist! The only items there were dcp.dat, dcp.db and ODE\_KCP.mobi. None the less I pasted my "new" dictionary into the folder and reset the permissions. But with no effect. It does not recognise my new dictionary. Should this "new" dictionary be placed in an alternative directory?

 Any assistance you can give will be of a great help  
 For your information I own a Kindle Fire HD 7  
 Kindest regards

 Wm Sanderson 

[reply](https://tools.techidaily.com/epubor/products/) 

George

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

03/21/2015 09:07:34

I followed this to the end and now no dictionaries work! Help!

[reply](https://tools.techidaily.com/epubor/products/) 

lanfeng

[Re:How to Replace Kindle Fire Dictionary](https://tools.techidaily.com/epubor/products/)

03/25/2015 01:37:09

my kindle fire is 1st,I followed this to the end and now no dictionaries work! Help!

[reply](https://tools.techidaily.com/epubor/products/) 

Leave a comment

| Rating |  |
| ------ |  |

| YourName | \*  1 to 50 chars |
| -------- | ----------------- |

| email | Internet Email |
| ----- | -------------- |

| Comments | UBB Editor |
| -------- | ---------- |

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/updated-quick-fix-for-identifying-imposters-in-your-instagram-community/"><u>[Updated] Quick Fix for Identifying Imposters in Your Instagram Community</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-desktop-capture-the-windows-user-guide/"><u>2024 Approved Desktop Capture The Windows User Guide</u></a></li>
<li><a href="https://solve-lab.techidaily.com/easy-instructions-on-how-to-perform-software-updates-for-kindle-devices/"><u>Easy Instructions on How to Perform Software Updates for Kindle Devices</u></a></li>
<li><a href="https://solve-lab.techidaily.com/easy-techniques-for-converting-and-printing-adobe-digital-edition-titles/"><u>Easy Techniques for Converting and Printing Adobe Digital Edition Titles</u></a></li>
<li><a href="https://solve-lab.techidaily.com/effective-techniques-for-uninstalling-titles-in-the-apple-ibooks-application/"><u>Effective Techniques for Uninstalling Titles in the Apple iBooks Application</u></a></li>
<li><a href="https://solve-lab.techidaily.com/effortless-guide-transferring-your-pdf-documents-onto-an-ipad/"><u>Effortless Guide: Transferring Your PDF Documents Onto an iPad</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-crafting-captivating-content-with-correct-dimensions/"><u>In 2024, Crafting Captivating Content with Correct Dimensions</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-prime-stabilization-techniques-for-youtubers/"><u>In 2024, Prime Stabilization Techniques for YouTubers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-tecno-spark-20-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Tecno Spark 20 and Browser | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/seamless-srt-discover-the-top-8-subs-to-srts-software-for-every-os-for-2024/"><u>Seamless SRT Discover the Top 8 Subs to SRTS Software for Every OS for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-guide-visible-wi-fi-network-problems-and-effective-solutions/"><u>Troubleshooting Guide: Visible Wi-Fi Network Problems & Effective Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

