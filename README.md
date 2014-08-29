Keyboard Shortcuts on your Desktop
==========================

Get faster, more precise or find alternative ways to accomplish your tasks. Transform your professional and under-utilized desktop background into an asset, essential to your digital production workflow.

#Table of contents

1. Introduction

2. Prerequisites

3. Install

4. Upgrade

5. Modify

6. Contribute

7. Uninstall

8. Legal notices

#Introduction

As a software, internet or digital media professional, your time is of essence. You need to be quick and precise in accomplishing your tasks. That is why in your daily operations you heavily rely on your keyboard.

The software packages and environments you use nowadays however, are huge. Together with their extensions they provide you with multiple ways to accomplish almost anything in your field.

**The only problem is if you could remember how.**

When under pressure, gunning for that deadline, you have no time to dwell into manuals, learn new features, let search for keyboard shortcuts. You just blindly run, relying on what you know by heart. But human memory is a tricky thing - it doesn't always play by the rules you may expect. So you stick to the basics, start making errors, and as a result, you under-perform.

**The images provided here intend to get you back in track, today.**

Your desktop background is always in your field of vision, regardless whether you work, relax with your favorite game or your attention is away. As a plain image however, your desktop background serves a little purpose. What could you possibly do to utilize that huge empty area on your desktop better?

The images provided here have been prepared with the intention to serve multiple purposes and strike balance on multiple conflicting criteria:

* Stay focused on your task

  * The background images provided here are with reduced contrast and desaturated. They do not distract you from the applications you use, but still clearly separate from the rest.

  * The keyboard shortcuts unobtrusively "fly" in the middle. While crisp and distinguishable, they blend with the background without compromising it. They are also easily distinguishable from your applications without unnecessarily attracting your attention.
  
  * You get three layers with an illusion of depth - the applications you use in front, keyboard shortcuts in the middle and a panoramic, low detail, high-quality image in the far back. And you can visually switch between the three layers in a split-second.

* Stay organized and find quickly what you need

  * Contrary to most user manuals, the emphasis here is on functions and not keyboard shortcuts. In this way you just need to locate in the hierarchical tree the task you seek to accomplish and not explicitly memorize keyboard shortcuts.

  * The layout attempts elegantly to fit as much information on it as possible, while separating application shortcuts, desktop environment shortcuts, icons and desktop widgets. In this way you can find your way through the overloaded with information desktop background quick.

  * No need to spend precious time sifting through manuals or searching on the Internet anymore, in order to find how to invoke a specific function. All the information you need is in front of your eyes, all the time. Just move the window obstructing the view away, or press a single keystroke to minimize them all (Win+D on Windows).

  * It is practically impossible to fit all shortcuts of all applications on a single desktop background. If you place the shortcuts for the different applications on separate images, you could switch to the desktop background relevant to the application you use at the moment.

* Implicitly learn on the go. Due to the organization of the content, while visually scrolling on the tree seeking the task you need, you implicitly realize how to accomplish many other similar tasks.

* Attribute to a calm environment. The images provided here have been chosen such that to provide a relaxing effect, so you make less errors and perform better.

In short, instead being just a plain image of dubious value, your professional desktop background can provide you with the speed, accuracy and cognitive offload you need in order to perform better under pressure.

![Screenshot of an Windows 7 desktop with a background image containing the keyboard shortcuts of Eclipse PDT on left and Windows Active Desktop on right](screenshot.png)

Screenshot of an Windows 7 desktop with a background image containing the keyboard shortcuts of both Eclipse PDT (on left) and Windows Active Desktop (on right).

To create desktop backgrounds encompassing all display resolutions, multi-monitor layouts, application shortcuts and personal tastes is practically impossible. Neither this project has such an ambition. For the time being, the images provided here:

* Support horizontal, linear dual 1080p (3840x1080 px) monitor set-up

* Provide keyboard shortcuts for the following applications and environments:

  * [Adebe After Effects](backgrounds/after-effects.png)

  * [Adobe Illustrator](backgrounds/illustrator.png)

  * [Adobe Photoshop](backgrounds/photoshop.png)

  * [Blender](backgrounds/blender.png)

  * [Eclipse IDE with PHP Development Tools](backgrounds/eclipse-pdt.png)

  * [Microsoft OneNote](backgrounds/onenote.png)

  * [Microsoft Windows Active Desktop](backgrounds/active-desktop.png)

You can use the provided templates to correct and supplement the shortcuts you need or include background imagery that appeals to you best.

#Prerequisites

In order to take maximum advantage of this project, you will need the following software installed:

* Git core client, in order to manage your local copy of the project files:  http://git-scm.com/downloads

* Adobe Illustrator and Adobe Photoshop, to use the provided templates

#Install

The installation of this project on your system includes the following steps:

1. Grab a copy of the project repository and place it on an appropriate local folder. On Windows 7 for example, execute in Command Prompt:

```
git clone https://github.com/bogomirov/keyboard-shortcuts.git ^
%USERPROFILE%\AppData\Local\keyboard-shortcuts
```

2. Enable any or all of the desktop backgrounds. On Windows 7 navigate to:

```
Start -> Control Panel -> Personalization -> Desktop Background
```

and browse to the folder where are the background images provided by the project:

```
C:\users\<your-user-name>\AppData\Local\keyboard-shortcuts\backgrounds
```

3. Select any or all of the desktop backgrounds and adjust the timing of their appearance to your liking.

4. Press Save changes

5. Optionally, save the desktop theme under a new name.

From now on, you can switch desktop backgrounds regarding the application you use. On Windows 7, right-click on an empty area on your Desktop and choose `Next desktop background`
 
If you are satisfied with what you get and never plan to make any modifications to the design of the backgrounds and any of the shortcuts, you can conserve some disk space by removing the templates. On Windows, execute in Command Prompt:

1. Switch to the location of the keyboard shortcuts repo:

```
cd %USERPROFILE%\AppData\Local\keyboard-shortcuts
```

2. Remove the templates from your working tree and index:

```
git rm -r templates
```

3. Commit the changes to your local repo:

```
git commit -am "Removed the templates dir, not planning to make any customizations"
```

In this way the templates will never re-appear in the keyboard-shortcuts directory when you make subsequent upgrades and merges. This action is reversible whenever you choose to.

#Upgrade

You can upgrade your local copy of the keyboard shortcuts repo with the last changes in the remote pretty easily. On Windows you can accomplish that by executing the following two statements in Command Prompt:

1. Switch to the folder where you have installed your local copy:

```
cd %USERPROFILE%\AppData\Local\keyboard-shortcuts
```

2. Pull the latest changes:

```
git pull origin master
```

3. Verify that the backgrounds you like are still available to your theme by navigating to:

```
Start -> Control Panel -> Personalization -> Desktop Background
```

#Modify

Modifying these desktop backgrounds is pretty straightforward.

1. Use Adobe Photoshop templates to generate raster background images with the exact size of your desktop.

  Keep in mind that to achieve the effect intended by this project, the images should be of low contrast and desaturated. Whether they are bright or dark is to your liking but ensuring low contrast is important.

2. Export the background image from Photoshop as an intermediary .png

3. Open the Adobe Illustrator template

4. Link the new intermediary .png image you exported from Photoshop externally

5. Make the changes you need to the shortcuts content and their layout

5. Export the so composited image into the backgrounds directory

6. Delete the intermediary .png image you exported from Photoshop

7. As above, ensure the new background image is available to your desktop theme

Do not forget to store these changes you made into the local repository. In this way you can switch back and forth between modifications, protect against accidental file loss, recover errors, etc. Execute in Command Prompt:

1. Switch to the location of the keyboard shortcuts repo:

```
cd %USERPROFILE%\AppData\Local\keyboard-shortcuts
```

2. Commit the changes, adding a relevant descriptive comment:

```
git commit -am "Created a background shortcut image for my other application"
```

If you would like to incorporate in your modifications the updates coming from the original repository (see the Upgrade section), please keep in mind that the vector and raster content distributed with this project is in binary format. There is no version control system yet capable to assist you in merging changes in binary content from different sources. Therefore, when receiving updates you should keep both copies - your version of the binary file and the new version coming upstream. Open them side-by-side in Photoshop or Illustrator, and attempt to transfer any modifications to your version manually.

For more information on binary merges, see the free on-line book about version control with Git: http://git-scm.com/book

#Contribute

If you would like to share your modifications to the project or new keyboard shortcuts with the world, you need to complete few steps, similar to the ones outlined in the Bluebird Glx-Dock Theme project: https://github.com/bogomirov/glx-dock-bluebird-theme#contribute

#Uninstall

Uninstalling the keyboard shortcut desktop images is pretty straightforward.

1. Ensure the desktop images are not used in your desktop theme, or you use a different theme completely by navigating to:

```
  Start -> Control Panel -> Personalization -> Desktop Background
```

2. Remove the keyboard shortcuts project from your hard drive. Execute in Command Prompt:

```
rmdir /s %USERPROFILE%\AppData\Local\keyboard-shortcuts
```

Please note that with this operation you will irrecoverably delete all the files associated with the project, together with the history of their modifications. Therefore, if you have made any modifications to the project by yourself, it is advisable you to keep a backup of your work, e.g. by sharing it in on-line.

#Legal notices

All raster imagery used in and distributed through this project is believed to be in the "public domain" and of unknown to the author origin. The author does not intend to infringe any legitimate intellectual right, artistic rights or copyright. If you are the rightful owner of any of the raster images used in this project, and you do not want it distributed, or if you require a suitable credit, then please contact the author of this project to immediately do whatever is needed either for the image to be removed or provide credit where it is due. Please note that all the content of this project is provided free of charge and therefore the author does not gain any financial benefit from its distribution.

Copyright on the project concept, layout design, vector artwork, image processing and composition &copy; 2014, Bogomir Bogomirov.

This project is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons Attribution 4.0 International License](https://i.creativecommons.org/l/by/4.0/80x15.png)
