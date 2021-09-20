# BorderHacks Demo Video Template

For those hackers who aren't experienced with video editing, there is a video template here that’s free to use. You will need two different softwares to create your video:

- OBS Studio. This is the software you will be using to record your screen.
- HitFilm Express. This is the video editing software where all the magic happens!

**If you have any trouble with this process, please feel free to reach out to Justin Bornais on the BorderHacks server and I will gladly help you!

## First, you will work with OBS Studio:

1. Click the link [OBS Studio Download](https://obsproject.com/) to download the software.
2. Follow the installation instructions.
3. [Check out this amazing guide to setting up your Scene to start recording.](https://www.youtube.com/watch?v=Muk9LfEWHeU)
   - **A couple notes:** It is recommended to use Display Capture instead of Window Capture for recording your screen. Make sure it is selected to the correct monitor if you have a setup with multiple monitors.
   - If you see a black screen when you set your Display Capture on Windows 10, [check out this video on YouTube to fix it.](https://www.youtube.com/watch?v=awXP6_kDii4)
4. Make sure your settings are all correct. Go to File/Settings to edit the general recording preferences. Here are the recommended settings:
   - On the *Output* tab at the left:
     - Make sure under *Recording*, you have the option *Recording Format* set to mkv. Recording in mov or mp4 are also good options, but should something happen to your computer, only mkv will autosave most of the recording.
     - Under *Recording*, you should have the option *Recording Quality* to either "High Quality, Medium File Size" or "Indistinguishable Quality, Large File Size". Note the file size difference is small.
     - Under *Recording*, make sure *Encoder* is set to "Software (x264)". This is usually the default option, but make sure this option is selected. If you have an NVIDIA GPU, you can also try selecting the option "Hardware (NVENC)". This may result in an error on some machines.
   - On the *Video* tab at the left:
     - Make sure your *Base (Canvas) Resolution* option (this is the base resolution of your recording screen) is the same as your monitor's resolution (or if you have a 4K monitor, set it to 1080p to save CPU stress). Set your *Output (Scaled) Resolution* to the same value as the *Base (Canvas) Resolution* option.
     - Make sure your *Downscale Filter* is set to *Bicubic (Sharpened scaling, 16 samples)*.
   - **If you have your _Recording Format_ option set to mkv,** go to the *Advanced* tab. Under the *Recording* section, check the box *Automatically remux to mp4*.
5. Start recording yourself! You can click the *Start Recording* button in the lower right portion of the screen.
   - **Tips:** If you slip up while recording, keep going! You can edit and trim later on in the editing process through HitFilm Express. Give yourself a couple second pause if you slip up so editing later on is easier.
   - Make sure you give yourself a 5 second pause before you start speaking during your recording, and also another 5 second pause before you stop recording. This will make editing and trimming a lot easier.
6. Once you're done recording, hit *Stop Recording*. Now you're all set!

## Now, you will download and install HitFilm Express:

1. [Download and install HitFilm Express.](https://fxhome.com/product/hitfilm-express) You can either hit the *Download HitFilm Express* button or the *Download FREE* button to download.
2. A slider will pop up that looks like the image below. HitFilm Express is a software that is free that also comes with advanced editing tools, if you pay. For BorderHacks, the free version is more than enough. To download for free, just slide the slider all the way to the left. The *Buy Now* button will change to *Download*. Click the Download button.

![Slider](https://drive.google.com/uc?export=view&id=1OhabHYrA7fsGonwe1pyriEbGry5JnRhr)

3. You will be directed to a page where you will have to enter your display name (can be made up), country, email, password and age. For the option *Subscribe to our emails for special offers, exciting developments, free content & prizes.* simply click No.
4. Once the page is filled out, click *Send me the Express download*. It will send a link to the email you provided.
5. Go to this email and click the button *Get Your Express Installer*. Then click which operating system you have under Step 2. Then the installer will download. Next, follow the instructions in the installer and you will be good to go!

## How to edit the template file:

1. Open the template file (extension .hfp) in HitFilm Express.
   - You may notice an error that says *The following files could not be found at their previously saved locations. Missing files will be relinked automatically where possible*. If this pops up, simply double-click one of the files that shows up in the popup box, then go to the Images folder in the repository and select the corresponding image.This should fix the issue if it pops up.
   
   ![Error](http://drive.google.com/uc?export=view&id=1BR_cr4J3ibV9qSJxsX7LHncG1XHKEMgK)
2. Start editing! There are template texts in the project to edit the text to match your project. To edit this, double click on the corresponding box at the bottom portion of the *Editor*, and then click on the corresponding text box that gets highlighted on the main view. There you will be able to rewrite the text.
3. Should you want to change some of the transitions (optional), you can change the duration by dragging the little boxes at the top of the main element.

![Elements](https://drive.google.com/uc?export=view&id=1BiOp4TPy8cSzeUnBVdgXu_w2WFlumobX)

4. To add your OBS recordings, near the bottom-left corner of the screen, there should be a *Media* tab with a button *Import*. Click *Import* and then find your video recording. The video should show up below the Import button along with the other text elements and images. Drag the video to the tab in the Editor that says *Add Video/Screenshots Here*.

5. To cut your video (should you have made an error), position the black play bar over where you want to cut the clip, select the video box (should display orange when selected) and right click it. Then click the option *Slice* or if you are using Windows, you can also use the keyboard shortcut Ctrl + Shift + D. This will split the clip into two. Do this over both areas where the error is, then you can delete the mistake.

6. Keep on editing! Once you're done, at the top of the editor, click *Export/Export Now/Contents*. Then the video will export in the path given in the Output section of the Export tab (should be defaulted to your Videos folder).

That is everything you should know about video editing! Should you have any questions, please reach out to Justin Bornais in the BorderHacks Discord Server.

# Happy Hacking!
