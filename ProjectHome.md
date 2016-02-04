<img src='http://img204.imageshack.us/img204/392/logoav8.jpg' />
<p />
A attempt to port Google's Android to the Sony Playstation 3. Anyone that has anything to bring to this project please inquire. scramble@gmail.com


Update 7/11/09
Sorry for the lack of news I have been in the process of moving and have since sold my old ps3 that contain the original project. Quite a few things have changed since the move. Believe it or not it takes quite a lot of time to compile this sucker on the ps3 and some serious space. When originally trying to get android to work on the ps3 I ran into many issues with memory and drive space. I have a 80gb ps3 which made things go quite a lot smoother. I wish I would have had a real ppc64 development platform before attempting this project but I was just pissed at the fact that stupid people on forums said oh it wont work "ARM" lol, and really I just wanted to prove a point. Android loads but I have no interest in continuing work on the project for I am more interested in ChromeOS and believe it will be much more suited for the ps3. I would also like to thank IBM for their continued email support with me regarding PPC java. If anyone is interested on picking up on the project, inquire. "It doesn't take much"
<img src='http://img190.imageshack.us/img190/8140/ps3dump.gif' />
<p />





Update 3/17/09
Hi guys its been a while, the project is finally coming together. I plan on release my modified source code soon. Thanks for waiting.

Update 1/12/09
Resolved a problem using ant -diagnostic tool. Fixed issue.
export JAVA\_HOME=/opt/ibm/java-s390x-60/


Update 1/10/09
Overall progress has been progressing on getting this to compile, google had added some left overs to help in the compiling process. I am still battling a new error that is becoming quite problematic. I already resolved a memory issue in which you could only compile the source with a computer that has 1080mb or ram or more. Anyway keep looking.

Update 1/9/09
make -j2 TARGET\_ARCH=ppc64 TARGET\_PRODUCT=generic
TARGET\_SIMULATOR=false TARGET\_BUILD\_TYPE=release TARGET\_OS=linux
LOCAL\_PRELINK\_MODULE=false

Well well well... got it to compile just fine. I believe once I the bootloader setup we will have android on the ps3 (proof of concept). I will be updating this page for frequently with my findings. I am going to try to get this to run directly off a USB flash drive.



Update 1/8/09
Using PPC64 GCC Cross Compiler
binutils-2.15.tar.bz2
crosstool-0.28-rc29.tar.gz
gcc-3.4.1.tar.bz2
glibc-linuxthreads-2.3.2.tar.bz2
glibc-2.3.2.tar.bz2
Building android from full source.
Compiling kernel image with minimal hardware peripheral support for the time being.

Thats it for today. Time will tell. Lots of debugging to do.