# [Adobe After Effects 2019/2020](https://helpx.adobe.com/after-effects/kb/known-issues-after-effects.html) stuck during startup & you don't even see the splash screen yet?

Had to kill AfterFX.exe via the [Task Manager](https://en.wikipedia.org/wiki/Task_Manager_%28Windows%29) multiple times, no success.

[Some old advice dating back to Adobe CS6 still applies](https://www.reddit.com/r/AfterEffects/comments/95d17p/aftereffects_stuckfreeze_on_loading_screen_startup/), it appears:
 
![](assets/after%20effects%20deleted%20files.png)
 
- After updating my video card drivers: *no luck, bad joss!* 😥
 
- A suggested fix elsewhere, though not for me today: 😤 I **did not want to uninstall** my "*third party AVI, MKV, MP4, etc. drivers*" a.k.a. [K-Lite Mega Codec Pack](https://www.codecguide.com/download_k-lite_codec_pack_mega.htm) - though I must say I've had trouble with older After Effects installs back in the day when DivX was king. 
 
- A suggested fix elsewhere, though not for me today: 😤 **Nor did I want to uninstall the installed fonts** and go through that hassle again.
 
- 😩 Deleting all the After Effects config, cache & temp files in `C:\User\<YourUserId>\...` I finally got to the After Effects splash screen once again and could continue from there.
 
## Who was the culprit?
 
I don't know.
 
Haven't used After Effects for quite a while (about half a year) and many parts of my rig have (auto)updated themselves while the machine kept silently slugging along in the background:
 
- [K-Lite](https://www.codecguide.com/download_k-lite_codec_pack_mega.htm)
- some new fonts have been installed for a tiny web project
- Windows of course went ahead and redid itself in the night several times
 
## Useful bits? Lessons learned?

I installed [UltraSearch](https://www.jam-software.com/ultrasearch) today to help me find these files quickly as Windows Ctrl+F Find was sluggish as usual - the snails in my garden are way faster and they also don't 'benefit' from a [(crappy/guzzling) NTFS Search Index](https://answers.microsoft.com/en-us/windows/forum/windows_10-win_cortana/index-search-in-file-explorer/b549368b-dba4-421e-aeef-0f9d03b1de72) either.

So I will have train my muscle memory to hit [UltraSearch](https://www.jam-software.com/ultrasearch) instead of Windows Explorer Ctrl+F.

This last bit of hassle from AE had me seriously considering finally switching to Blender and to Hell with the fresh new learning curve there! *!@#$%^&* 🤐 *Adobe coders.* Getting your app stuck on something stupid like this... doesn't raise my confidence in the code overall. Alas, it's what I'm used to use, but now Blender will certainly get my attention ASAP - the few times I kickstarted that one in the past it never failed to boot on my rig.



 