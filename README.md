allcoder
========

A multiplatform CLI Script which enables user to Encode video's without much hassel...

/*
 * ----------------------------------------------------------------------------
 * "THE BEER-WARE LICENSE" (Revision 42):
 * <https://github.com/Spydur> wrote this file. As long as you retain this 
 * notice you can do whatever you want with this stuff. If we meet some day,
 * and you think this stuff is worth it, you can buy me a beer in return Spydur
 * ----------------------------------------------------------------------------
 */


This is the Not well described Version of how to run it in Windows and Linux.
This Script is not for n00bs. Pls if you want to start somewhere go download MeGUI and start learning encoding.

  			++Windows++

1.Download and Install avisynth from <http://sourceforge.net/projects/avisynth2>.

	[1.a]. You need to extract allcoder.rar into C drive nowhere else.

2.This Script only supports MKV and MP4 files till 21/05/2013 , Check my github page for updates.

	[2.a]. If you have a some .mp4 file(s) you want to encode it into 480p copy the file(s) in Inputmp4480p folder and rename it sequentially,and run mp4480p.bat.
 
	[2.b]. If you have a some .mkv file(s) you want to encode it into 480p copy the file(s) in Inputmkv480p folder and rename it sequentially,and run mkv480p.bat.

	[2.c]. If you have a some .mp4 file(s) you want to encode it into 720p copy the file(s) in mp4720p folder and rename it sequentially,and run mp4720p.bat.

	[2.d]. If you have a some .mkv file(s) you want to encode it into 720p copy the file(s) in mkv720p folder and rename it sequentially,and run mkv720p.bat.

3.The batch script(s) are very customizable in nature,But pls dont touch those if don't know what are you doing. * For Experienced users only who know about command prompt and x264 commandlines. *


				++Linux++

1.You need Wine to run these scripts , Download and install from <http://www.winehq.com>.

2.There are lot of dependencies for wine but to run these scripts you specifically need winetricks,vcrun2008,vcrun6. There are lot of distros out there I cannot write howto's for every each of them pls google how to install these.

3.After installing wine,winetricks,vcrun2008 and vcrun6 download and avisynth from <http://sourceforge.net/projects/avisynth2>.

4.Browse to the C drive of wine and extract the contents there.

5.This Script only supports MKV and MP4 files till 21/05/2013 , Check my github page for updates.

	[5.a]. If you have a some .mp4 file(s) you want to encode it into 480p copy the file(s) in Inputmp4480p folder and rename it sequentially, Goto the scripts dir and open a terminal there, run command prompt by typing.
		
		[5.a.1]. Type "wine cmd".
		[5.a.2]. Then Type "mp4480p.bat", Now sit back and relax. :D 
 
	[5.b]. If you have a some .mkv file(s) you want to encode it into 480p copy the file(s) in Inputmkv480p folder and rename it sequentially, Goto the scripts dir and open a terminal there, run command prompt by typing.

		[5.b.1]. Type "wine cmd".
		[5.b.2]. Then Type "mkv480p.bat", Now sit back and relax. :D 

	[5.c]. If you have a some .mp4 file(s) you want to encode it into 720p copy the file(s) in mp4720p folder and rename it sequentially, Goto the scripts dir and open a terminal there, run command prompt by typing.

		[5.c.1]. Type "wine cmd".
		[5.c.2]. Then Type "mkv480p.bat", Now sit back and relax. :D 

	[5.d]. If you have a some .mkv file(s) you want to encode it into 720p copy the file(s) in mkv720p folder and rename it sequentially, Goto the scripts dir and open a terminal there, run command prompt by typing.

		[5.d.1]. Type "wine cmd".
		[5.d.2]. Then Type "mkv480p.bat", Now sit back and relax. :D  
3.The batch script(s) are very customizable in nature,But pls dont touch those if don't know what are you doing. * For Experienced users only who know about command prompt and x264 commandlines. *


NOTE : It probably works on Mac too as it relies entirely on script system , But have not tried and tested.
