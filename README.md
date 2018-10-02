# TalkBox-SenseBox
This repository contains Raspberry PI images for the DIY TalkBox and SenseBox systems. For more information please see (contact me for the password):  https://rishmanblog.wordpress.com/2017/06/01/how-to-build-your-own-talkbox/


[This page is under construction. Please do not share widely.]

Fabrication Lab in a Kit (FLiK) is an open-source prototyping kit for creating your own communication devices. While the kit is specifically designed to support the creation of communication boards for users who are non-verbal or have limited speech, it can be used for a variety of applications including to add embedded sound to art projects, wearables, and augmented environments.

At the heart of FLiK is <a href="http://www.foadhamidi.info/talkbox.html">TalkBox</a>: a <a href="https://www.raspberrypi.org/">Raspberry Pi</a>-powered embedded system that allows users to program their own interactions by specifying what sounds should be played back when sensors are touched. We have described TalkBox in <a href="https://rishmanblog.wordpress.com/2014/08/29/the-possibilities-of-diy-assistive-technology-and-digital-media-making-therapy/">a post on the potentials of DIY assistive technology</a> in the past. Here, we want to provide an update about its hardware/software and describe how to make your own and incorporate it into a customized prototype using the FLiK kit that is relevant for you or someone for whom you are building the system. Many people have contributed to this project over the years, please see the end of this post for credits.
<h2>Hardware</h2>
You will need the following ingredients to make a FLiK. FLiK consists of a TalkBox module together with other craft and fabrication tools and components that can be used to fabricate different variants of the TalkBox prototype. Please see below for a list of components and corresponding images in the pictures.

In the list that follows, each component is linked to an e-commerce site that carries it. The main reason for including links to distributors is to provide more information about each item. Please feel free to get the supplies from outlets that are most convenient for you.

[caption id="attachment_5265" align="alignnone" width="1752"]<img class="alignnone size-full wp-image-5265" src="https://rishmanblog.files.wordpress.com/2017/06/screen-shot-2017-06-03-at-9-40-59-am1.png" alt="Screen Shot 2017-06-03 at 9.40.59 AM.png" width="1752" height="1368" /> Components for creating the TalkBox Module and accessing the software[/caption]

<strong>TalkBox Module</strong>

1. <a href="https://www.adafruit.com/product/3055">Raspberry Pi 3</a>

2. <a href="https://www.amazon.com/Sandisk-MicroSDHC-Memory-Card-Adapter/dp/B000WH6H1M/ref=sr_1_2?ie=UTF8&qid=1496411964&sr=8-2&keywords=micro+sd+card+8+gig">Touch Hat for Raspberry Pi</a>

3. <a href="https://www.adafruit.com/product/3369">USB Flash Drive</a>

4. <a href="https://www.adafruit.com/product/1565">Battery</a>

5. <a href="https://www.adafruit.com/product/1995">Power Supply</a>

6. <a href="https://www.adafruit.com/product/2604?gclid=CNPa56Opn9QCFcWFswodHdME9A">Raspberry Pi Official case</a>

7. <a href="https://www.adafruit.com/product/1008">Wires (Alligator clip or otherwise)</a>

8. <a href="https://www.amazon.com/Sandisk-MicroSDHC-Memory-Card-Adapter/dp/B000WH6H1M/ref=sr_1_2?ie=UTF8&qid=1496411964&sr=8-2&keywords=micro+sd+card+8+gig">Micro SD card</a> (at least 8 gigs)

9. <a href="https://www.adafruit.com/product/3369">USB Speaker</a>

<strong>Software Access</strong>

10. <a href="https://www.amazon.com/HP-Wired-Keyboard-K1500-Black/dp/B00E4TOWR0/ref=sr_1_4?s=pc&ie=UTF8&qid=1496413982&sr=1-4&keywords=usb+keyboard">USB Keyboard</a>

11. <a href="https://www.adafruit.com/product/939">Micro SD Card Reader/Writer</a>

12. <a href="https://www.amazon.com/JETech-3-Button-Wired-Optical-Mouse/dp/B00Y20UI1K/ref=sr_1_4?s=electronics&ie=UTF8&qid=1496414055&sr=1-4&keywords=usb+mouse">USB Mouse</a>

13. <a href="https://www.amazon.com/dp/B01JH71AFK/?ref=sxts_snpl_2_0_2958666122&qid=1496414007&pf_rd_m=ATVPDKIKX0DER&pf_rd_p=2958666122&pf_rd_r=42NZYKYR6JPTCM7X8CMY&pd_rd_wg=PqOLm&pf_rd_s=desktop-signpost&pf_rd_t=301&pd_rd_w=7F51J&pf_rd_i=hdmi+cable&pd_rd_r=R9F9MDS46VXMEXBYVK90">HDMI cable</a>

14. <a href="https://www.amazon.com/ASUS-VS228H-P-1920x1080-Back-lit-Monitor/dp/B005BZNDOO/ref=sr_1_3?s=electronics&ie=UTF8&qid=1496414035&sr=1-3&keywords=hdmi+monitor">HDMI monitor</a> (not shown in the picture)

15. (Optional) <a href="https://www.amazon.com/VicTsing-Gold-Plated-Converter-Adapter-Laptop/dp/B016HL49OS/ref=sr_1_1?ie=UTF8&qid=1496414088&sr=8-1&keywords=B00G9UWP94%7CB00K4W62R4%7CB00YC7U0NE%7CB016HL49OS%7CB016HL4CAY%7CB019BTJ1UA%7CB01BTROG0M%7CB01ID8FZZU">VGA to HDMI converter</a> (not shown in the picture)

 

<img class="alignnone size-full wp-image-5266" src="https://rishmanblog.files.wordpress.com/2017/06/screen-shot-2017-06-03-at-9-41-09-am.png" alt="Screen Shot 2017-06-03 at 9.41.09 AM.png" width="1840" height="1382" />

Tools and materials for chassis
<strong>Chassis and Tools</strong>
16. <a href="https://www.amazon.com/Elmers-900803-Surface-Boards-Carton/dp/B000EFLX5C/ref=sr_1_4?s=electronics&ie=UTF8&qid=1496413047&sr=1-4&keywords=foamcore">Foamcore Sheets </a>

 

17. <a href="https://www.amazon.com/OLFA-9881-18-Inch-Self-Healing-Double-Sided/dp/B000BNLO3S/ref=sr_1_1?s=hi&ie=UTF8&qid=1496413282&sr=1-1&keywords=cutting+mat">Cutting Matt</a>

18. <a href="https://www.amazon.com/uxcell-Degree-0-30cm-0-20cm-Square/dp/B00JR3T6Q0/ref=pd_day0_469_5?_encoding=UTF8&pd_rd_i=B00JR3T6Q0&pd_rd_r=T379RP35D2EP3RPVBHCJ&pd_rd_w=EBlRm&pd_rd_wg=Tv8Y5&psc=1&refRID=T379RP35D2EP3RPVBHCJ">Steel Cutting Ruler</a>

19. <a href="https://www.amazon.com/Utility-Cutter-Retractable-Safety-Wholesale/dp/B01LKMLG7C/ref=sr_1_9?s=hi&ie=UTF8&qid=1496413250&sr=1-9&keywords=service+knife">Utility Knife </a>(Cutter)

20. <a href="https://www.amazon.com/Westcott-Titanium-Scissors-Straight-Handle-13901/dp/B000P0LNRE/ref=sr_1_4?s=hi&ie=UTF8&qid=1496413345&sr=1-4&keywords=scissors">Scissors</a>

21. <a href="https://www.amazon.com/Elmers-Purpose-School-Washable-0-24-ounce/dp/B001E69WBW/ref=sr_1_3?ie=UTF8&qid=1496413184&sr=8-3&keywords=glue+stick">Glue</a>

22. <a href="https://www.amazon.com/Duck-299006-4-Inch-Utility-Electrical/dp/B001B19JLS/ref=sr_1_1?ie=UTF8&qid=1496413087&sr=8-1&keywords=tape+black">Regular Tape</a>

23. <a href="https://www.amazon.com/Copper-Conductive-Adhesive-1inch-12yards/dp/B018RDZ3HG/ref=sr_1_5?ie=UTF8&qid=1496413110&sr=8-5&keywords=conductive+tape">Conductive Tape</a>

24. <a href="https://www.amazon.com/VELCRO-Brand-Industrial-Strength-Black/dp/B00006RSP1/ref=sr_1_4?ie=UTF8&qid=1496413128&sr=8-4&keywords=velcro">Velcro</a>

25. Printed out symbols

26. <a href="https://www.amazon.com/Mudder-Solder-Ag0-3-Electrical-Soldering/dp/B01B61TWGY/ref=sr_1_3?s=hi&ie=UTF8&qid=1496413234&sr=1-3-spons&keywords=solder&psc=1">Solder</a>

27. <a href="https://www.amazon.com/J-L-SI60-Soldering-Iron/dp/B0006NGZK0/ref=sr_1_10?s=hi&ie=UTF8&qid=1496413204&sr=1-10&keywords=soldering+iron">Soldering Iron</a>
<h2>Putting Together a TalkBox Prototype</h2>
The following steps describe how to put together the different parts of a standard TalkBox prototype using the components listed above. We will soon have more detailed instructions and videos that show each of these steps.

<strong>TalkBox Module</strong>
<ol>
	<li style="list-style-type: none;">
<ol>
	<li>Assemble and solder the Touch Hat</li>
	<li>Prepare the Raspberry Pi Case</li>
	<li>(Optional) solder wires to Touch Hat</li>
	<li>Connect the USB Speaker, battery and power supply</li>
	<li>Assemble all the pieces o the module together</li>
</ol>
</li>
</ol>
There's a <a href="https://www.youtube.com/watch?v=4ltxBA4Jk-Y&feature=youtu.be">video that shows this step</a>. However, it is a bit old and some of the components and tools are better now. We will update it as soon as possible.

<strong>Combining the TalkBox Module with a Chassis</strong>
<ol>
	<li style="list-style-type: none;">
<ol>
	<li>Cut the foamcore into size your design requires</li>
	<li>Use conductive tape to create buttons</li>
	<li>Connect wires and buttons</li>
	<li>Decide where you want to layout the components</li>
	<li>Use tape and velcro to connect components to chassis</li>
	<li>Print and cut out symbols</li>
	<li>Glue symbols to the corresponding foamcore pieces</li>
	<li>Assemble everything together</li>
</ol>
</li>
</ol>
Again, there's a <a href="https://www.youtube.com/watch?v=sXVilSFXu7A&feature=youtu.be">video that shows these steps</a>. Please note that some of the components and tools are different now. We will update the video as soon as possible.
<h2>Setting up the TalkBox Software</h2>
Once you have assembled a TalkBox, it is time to load the software.

<strong>Step 1. </strong>Download the latest image file from here [coming soon].

<strong>Step 2. </strong>Burn the image file onto your micro SD card using the Apple-Pi Baker program.

<strong>Step 3. </strong>Insert the micro SD Card into the Raspberry Pi and plug the system into power. TalkBox should boot and you should hear the startup sound.
<h2>Understanding and Modifying the TalkBox Software (for Developers)</h2>
Once you have the basic TalkBox setup, you can look at the code and change it to suit your needs. This section provides an overview of the code and also provides a set of resources for developers.

In order to access the code, you need to connect TalkBox to a monitor and attach a USB keyboard and mouse to it. Once you have all the peripherals connected boot up the system.

The system will either boot into a command line interface or a GUI. To get to the GUI use the following command:
<pre>startx</pre>
Once the system has loaded, the first thing to do is stop the current version of TalkBox that is running from startup. To do this open a terminal (or use a terminal that is already open), and type the following command:
<pre>top</pre>
This command shows all the active processes. Find the process that is associated with a "python" program and note its process ID (number). Press "q" to exit the top application.

Now use the following command to stop the TalkBox process (where is the process ID you noted in the previous step):
<pre>sudo kill</pre>
Now, we have to go to the TalkBox folder in the main directory to look at the program code. Navigate to the following folder:
<pre>cd /home/pi/TalkBox</pre>
The following image shows the structure of the TalkBox software:

<img class="alignnone size-full wp-image-5268" src="https://rishmanblog.files.wordpress.com/2017/06/screen-shot-2017-06-03-at-9-57-06-am.png" alt="Screen Shot 2017-06-03 at 9.57.06 AM.png" width="2546" height="1424" />

To run TalkBox again, you can either use the script in the TalkBox folder:
<pre>bash TalkBoxLaunch.sh</pre>
Or go to the bin directory and run the following command:
<pre>sudo python TalkBox.py</pre>
For a detailed description of the functions please see the comments in the code.
<h2>Credits</h2>
FLiK and TalkBox were made possible by the tireless effort of many people. In this section, we wish to thank everyone who has worked on this project.

[This section will be completed later.]
