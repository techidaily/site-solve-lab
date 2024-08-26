---
title: "A Step-by-Step Guide: Updating Your Kindle Fire's Built-In Thesaurus and Dictionary"
date: 2024-08-25T20:03:42.108Z
updated: 2024-08-26T20:03:42.108Z
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

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-tips-and-tricks-for-easily-finding-your-youtube-comments/"><u>[New] 2024 Approved  Tips & Tricks for Easily Finding Your YouTube Comments</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-capture-the-extraordinary-tips-for-spectacular-slow-motion-video-on-mobile-for-2024/"><u>[New] Capture the Extraordinary  Tips for Spectacular Slow Motion Video on Mobile for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capturing-the-action-5-roblox-recordings-for-mac-users/"><u>[New] Capturing the Action  5 Roblox Recordings for Mac Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-illustrator-way-how-to-create-stunning-motion-effects-for-2024/"><u>[New] The Illustrator Way  How to Create Stunning Motion Effects for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-determinants-of-youtube-video-prominence-and-success-for-2024/"><u>[Updated] Determinants of YouTube Video Prominence and Success for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-concept-to-completion-mastering-the-art-of-snap-campaigns/"><u>[Updated] From Concept to Completion  Mastering the Art of Snap Campaigns</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-mastering-zero-cost-youtube-intros-essential-tips-and-templates/"><u>[Updated] In 2024, Mastering Zero-Cost YouTube Intros  Essential Tips & Templates</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-whats-fresh-with-facebook-latest-info-here/"><u>[Updated] What’s Fresh with Facebook? Latest Info Here</u></a></li>
<li><a href="https://solve-lab.techidaily.com/1-discover-the-aax-file-extension-understanding-its-purpose-and-uses/"><u>1. Discover the .AAX File Extension: Understanding Its Purpose and Uses</u></a></li>
<li><a href="https://solve-lab.techidaily.com/1-effortless-document-conversion-how-to-transform-files-into-pdf-format/"><u>1. Effortless Document Conversion: How to Transform Files Into PDF Format</u></a></li>
<li><a href="https://solve-lab.techidaily.com/1-seamlessly-transform-ebooks-using-calibre-the-ultimate-guide/"><u>1. Seamlessly Transform eBooks Using Calibre: The Ultimate Guide</u></a></li>
<li><a href="https://solve-lab.techidaily.com/1-unlocking-the-secrets-of-digital-rights-management-drm/"><u>1. Unlocking the Secrets of Digital Rights Management (DRM)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-shadow-surge-and-sun-sweep-encounter/"><u>2024 Approved  Shadow Surge and Sun Sweep Encounter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-beginners-guide-to-advanced-techniques-in-gopro-studio/"><u>A Beginner's Guide to Advanced Techniques in GoPro Studio</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-motorola-defy-2-frp-bypass-by-drfone-android/"><u>About Motorola Defy 2 FRP Bypass</u></a></li>
<li><a href="https://solve-lab.techidaily.com/access-15-free-digital-comics-collections-here/"><u>Access 15 Free Digital Comics Collections Here!</u></a></li>
<li><a href="https://solve-lab.techidaily.com/anleitung-zur-bearbeitung-eines-worterbuchs-auf-der-kindle-plattform-aktualisierung-und-erweiterung/"><u>Anleitung Zur Bearbeitung Eines Wörterbuchs Auf Der Kindle-Plattform: Aktualisierung Und Erweiterung</u></a></li>
<li><a href="https://driver-install.techidaily.com/audio-issue-fixed-by-audio-driver-update-in-win11/"><u>Audio Issue Fixed by Audio Driver Update in Win11</u></a></li>
<li><a href="https://solve-lab.techidaily.com/bestselling-case-options-to-safeguard-your-kindle-voyage-reader/"><u>Bestselling Case Options to Safeguard Your Kindle Voyage Reader</u></a></li>
<li><a href="https://solve-lab.techidaily.com/bypassing-ibooks-digital-lock-for-cross-platform-reading-a-guide-to-deleting-drm-from-ibook-files-and-accessing-them-on-pc/"><u>Bypassing iBook's Digital Lock for Cross-Platform Reading – A Guide to Deleting DRM From iBook Files and Accessing Them on PC</u></a></li>
<li><a href="https://solve-lab.techidaily.com/e-book-mastery-with-epubor-streamlined-editing-software-for-beginners/"><u>E-Book Mastery with EPUBOR: Streamlined Editing Software for Beginners</u></a></li>
<li><a href="https://solve-lab.techidaily.com/easy-instructions-on-how-to-perform-software-updates-for-kindle-devices/"><u>Easy Instructions on How to Perform Software Updates for Kindle Devices</u></a></li>
<li><a href="https://solve-lab.techidaily.com/easy-techniques-for-converting-and-printing-adobe-digital-edition-titles/"><u>Easy Techniques for Converting and Printing Adobe Digital Edition Titles</u></a></li>
<li><a href="https://solve-lab.techidaily.com/effective-techniques-for-uninstalling-titles-in-the-apple-ibooks-application/"><u>Effective Techniques for Uninstalling Titles in the Apple iBooks Application</u></a></li>
<li><a href="https://solve-lab.techidaily.com/effortless-guide-transferring-your-pdf-documents-onto-an-ipad/"><u>Effortless Guide: Transferring Your PDF Documents Onto an iPad</u></a></li>
<li><a href="https://solve-lab.techidaily.com/expert-insights-on-the-newly-released-201th-kindle-oasis-a-comprehensive-evaluation/"><u>Expert Insights on The Newly Released 201^Th Kindle Oasis - A Comprehensive Evaluation</u></a></li>
<li><a href="https://solve-lab.techidaily.com/exploring-reasons-you-might-disfavor-using-a-kindle-e-reader/"><u>Exploring Reasons You Might Disfavor Using a Kindle E-Reader</u></a></li>
<li><a href="https://solve-lab.techidaily.com/exploring-the-mystery-of-unknown-digital-rights-management-techniques/"><u>Exploring the Mystery of Unknown Digital Rights Management Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/getting-started-in-vlogging-gear-and-software-guide-for-2024/"><u>Getting Started in Vlogging  Gear and Software Guide for 2024</u></a></li>
<li><a href="https://solve-lab.techidaily.com/how-to-eliminate-adobes-digital-rights-management-drm-from-pdf-and-epub-files/"><u>How to Eliminate Adobe's Digital Rights Management (DRM) From PDF and EPUB Files</u></a></li>
<li><a href="https://solve-lab.techidaily.com/how-to-liberate-vitalsource-projects-comprehensive-tutorial-for-vbk-drm-deletion/"><u>How to Liberate VitalSource Projects: Comprehensive Tutorial for VBK DRM Deletion</u></a></li>
<li><a href="https://solve-lab.techidaily.com/how-to-permanently-bypass-kindle-ebook-drm-without-skipping-restrictions/"><u>How to Permanently Bypass Kindle eBook DRM Without Skipping Restrictions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-iphone-11-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From iPhone 11? Complete Guide</u></a></li>
<li><a href="https://solve-lab.techidaily.com/how-to-transform-your-ebooks-format-from-protected-drm-enabled-epub-to-versatile-pdf/"><u>How to Transform Your eBook's Format: From Protected DRM-Enabled EPUB to Versatile PDF</u></a></li>
<li><a href="https://solve-lab.techidaily.com/how-to-upload-an-epub-book-to-a-kindle-device-with-amazons-send-to-kindle-email-service/"><u>How to Upload an EPUB Book to a Kindle Device with Amazon's Send-to-Kindle Email Service</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-honor-100-pro-easily-by-drfone-android/"><u>In 2024, How To Unlock a Honor 100 Pro Easily?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://solve-lab.techidaily.com/in-depth-expert-advice-handbook-navigate-with-ease-using-this-essential-guide/"><u>In-Depth Expert Advice Handbook: Navigate with Ease Using This Essential Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-hp-laserjet-1018-driver-version-download-now/"><u>Latest HP LaserJet 1018 Driver Version Download Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leading-the-way-in-color-grading-adobes-top-10-luts-for-lightroom/"><u>Leading the Way in Color Grading  Adobe's Top 10 LUTs for LightRoom</u></a></li>
<li><a href="https://solve-lab.techidaily.com/mastering-the-art-of-reading-acsm-ebooks-via-kobo-an-ultimate-guide/"><u>Mastering the Art of Reading ACSM Ebooks via Kobo: An Ultimate Guide</u></a></li>
<li><a href="https://solve-lab.techidaily.com/maximize-your-income-successful-affiliate-marketing-strategies-and-earning-potential/"><u>Maximize Your Income: Successful Affiliate Marketing Strategies and Earning Potential</u></a></li>
<li><a href="https://solve-lab.techidaily.com/quick-and-simple-guide-how-to-change-your-kobo-ebooks-into-pdf-format/"><u>Quick & Simple Guide: How To Change Your Kobo eBooks Into PDF Format</u></a></li>
<li><a href="https://solve-lab.techidaily.com/quick-how-to-simple-instructional-guide-for-assembly-and-installation/"><u>Quick How-To: Simple Instructional Guide for Assembly and Installation</u></a></li>
<li><a href="https://program-issues.techidaily.com/resident-evil-village-unraveling-the-mystery-of-in-game-mouse-problems/"><u>Resident Evil Village: Unraveling the Mystery of In-Game Mouse Problems</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/scorecard-for-the-apple-watch-se-premium-features-at-a-lower-price-point/"><u>Scorecard for the Apple Watch SE: Premium Features at a Lower Price Point</u></a></li>
<li><a href="https://solve-lab.techidaily.com/step-by-step-guide-how-can-you-change-an-azw3-format-book-into-an-accessible-epub-version/"><u>Step-by-Step Guide: How Can You Change An AZW3 Format Book Into an Accessible EPUB Version?</u></a></li>
<li><a href="https://solve-lab.techidaily.com/step-by-step-guide-removing-applications-from-your-kindle-fire-device/"><u>Step-by-Step Guide: Removing Applications From Your Kindle Fire Device</u></a></li>
<li><a href="https://solve-lab.techidaily.com/step-by-step-instructions-on-downloading-and-playing-audible-titles-on-pcs-and-macbooks/"><u>Step-by-Step Instructions on Downloading and Playing Audible Titles on PCs & MacBooks</u></a></li>
<li><a href="https://solve-lab.techidaily.com/submit-inquiry-and-obtain-insight-continue-on-this-page/"><u>Submit Inquiry & Obtain Insight – Continue on This Page</u></a></li>
<li><a href="https://solve-lab.techidaily.com/the-ultimate-guide-to-unlocking-kobos-potential-with-top-7-expert-tactics/"><u>The Ultimate Guide to Unlocking Kobo's Potential with Top 7 Expert Tactics</u></a></li>
<li><a href="https://solve-lab.techidaily.com/top-5-strategies-for-organizing-your-amazon-kindle-libraries/"><u>Top 5 Strategies for Organizing Your Amazon Kindle Libraries</u></a></li>
<li><a href="https://solve-lab.techidaily.com/transforming-acsm-ebooks-into-compatible-kindle-mobi-format-step-by-step-guide/"><u>Transforming .ACSM eBooks Into Compatible Kindle MOBI Format Step-by-Step Guide</u></a></li>
<li><a href="https://solve-lab.techidaily.com/transition-tips-accessing-nook-digital-novels-on-your-kobo-reader/"><u>Transition Tips: Accessing Nook Digital Novels on Your Kobo Reader</u></a></li>
<li><a href="https://solve-lab.techidaily.com/unlock-your-content-freedom-expert-steps-for-drm-free-conversion-of-ebooks-across-various-formats/"><u>Unlock Your Content Freedom: Expert Steps for DRM-Free Conversion of eBooks Across Various Formats</u></a></li>
<li><a href="https://solve-lab.techidaily.com/unraveling-the-secrets-a-comprehensive-guide-to-bypassing-drm-protection-on-e-books/"><u>Unraveling the Secrets: A Comprehensive Guide to Bypassing DRM Protection on E-Books</u></a></li>
</ul></div>
