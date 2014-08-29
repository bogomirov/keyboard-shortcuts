Keyboard Shortcuts on your Desktop
==========================

Get faster, more precise or find alternative ways to accomplish your tasks. Transform your professional and under-utilized desktop background into an asset, essential to your digital workflow.

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

The software packages and environments you use nowadays are huge. Together with their extensions they provide you with multiple ways to accomplish almost anything in their field.

**The only problem is if you could remember how.**

When under pressure, gunning for that deadline, you have no time to dwell into manuals, learn new features, let search for keyboard shortcuts. You just blindly run, relying on what you know by heart. But human memory is a tricky thing - it doesn't always play by the rules you may expect. So you stick to the basics, start making errors, and as a result you under-perform.

**The images provided here intend to get you back in track, today.**

Your desktop background is always in your field of vision, regardless whether you work, relax with your favorite game or your attention is away. As a plain image however, it serves a little purpose. What if you could utilize that huge empty area on your desktop better?

The images provided here have been prepared with the intention to serve multiple purposes and balance on multiple criteria:

* They are with reduced contrast, so you do not get distracted from your task.

* They are desaturated. In this way the applications you use, with their aggressive colors and widgets practically stand out, and you can immediately distinguish them from the background.

* Layout that efficiently uses the space of your multi-monitor setup, separating application and desktop environment keyboard shortcuts, icons and desktop widgets.

* The keyboard shortcuts, while being sharp and distinguishable on the one hand, do not distract you unnecessarily from your task, while on the other do not compromise the image in the back. They unobtrusively "fly" in the middle, so you can focus back and forth between applications, shortcuts and background in a split-second.

* Emphasize on tasks and less on details. Contrary to most user manuals, the emphasis here is on tasks and not keyboard shortcuts. In this way you just need to locate in the hierarchical tree the task you seek to accomplish and not explicitly memorize keyboard shortcuts.

* Implicitly learn on the go. Due to the hierarchical organization of the content, while visually scrolling on the tree seeking the task you need, you implicitly realize how to accomplish many other similar tasks.

* Coherent design. It is practically impossible to fit all shortcuts of all applications on a single desktop background. If you place the shortcuts for the different applications on separate images, you could switch to the desktop background relevant to the application you use at the moment.

* Provide a calm environment. It is a common truth that when you are calm, you make less errors and perform better. That is why the images provided here have been chosen such that have relaxing effect.

* Quick access. Your desktop background is in your field of vision all the time. To find any detail you need, you just minimize the application you are using, which is a click away.

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

Grab a copy of the project repository and place it on an appropriate local folder. On Windows 7 for example, execute in Command Prompt:

git clone https://github.com/bogomirov/keyboard-shortcuts.git ^
%USERPROFILE%\AppData\Local\keyboard-shortcuts

Enable any or all of the desktop backgrounds. On Windows 7 navigate:

Start -> Control Panel -> Personalization -> Desktop Background

and browse to the folder:

%USERPROFILE%\AppData\Local\keyboard-shortcuts\backgrounds

Select any or all of the desktop backgrounds and adjust the timing of their appearance to your liking.

Press Save changes

optionally, save the new desktop theme under a new name.

From now on, you can switch desktop backgrounds regarding the application you use.

Right-click on an empty area on your Desktop and choose "Next desktop background"
 
If you are satisfied with what you get and never plan to make any modifications to the design of the backgrounds and any of the shortcuts, you can conserve some disk space by removing the templates. Execute in Command Prompt:

1. Switch to the location of the keyboard shortcuts repo:

cd %USERPROFILE%\AppData\Local\keyboard-shortcuts

2. Remove the templates from your working tree and index:

git rm -r templates

3. Commit the changes to your local repo:

git commit -am "Removed the templates dir, not planning to make any customizations"

In this way the templates will never re-appear in the keyboard-shortcuts directory when you make upgrades (see below).

This action is reversible whenever you choose to.

#Upgrade

Upgrade your local copy of the keyboard shortcuts repo with the last changes in the remote. On Windows you can accomplish that by executing the following two statements in Command Prompt:

1. Switch to the folder where you have installed your local copy:

cd %USERPROFILE%\AppData\Local\keyboard-shortcuts

2. Pull the latest changes:

git pull origin master

Now you could verify that the backgrounds you like are still available to your theme by navigating to:

Start -> Control Panel -> Personalization -> Desktop Background

#Modify

Modifying these desktop backgrounds is pretty straightforward.

Use Adobe Photoshop templates to generate raster background images with the exact size of your desktop.

Keep in mind that to achieve the effect intended by this project, the images should be of low contrast and desaturated. Whether they are bright or dark is to your liking but ensuring low contrast is important.

Export the background image from Photoshop as an intermediary .png

Open the Adobe Illustrator template

Link the new intermediary .png image you exported from Photoshop externally

Make the changes you need to the shortcuts content and layout towards your liking

Export the so composited new image into the backgrounds directory

Delete the intermediary .png image you exported from Photoshop

Ensure the new background is available to your desktop theme

Do not forget to store these changes you made into the local repository. In this way you can switch back and forth between modifications, protect against accidental file loss, recover errors, etc. Execute in Command Prompt:

1. Switch to the location of the keyboard shortcuts repo:

cd %USERPROFILE%\AppData\Local\keyboard-shortcuts

2. Commit the changes, adding a relevant descriptive comment:

git commit -am "Created a background shortcut image for my other application"

Now if you like to incorporate in your modifications updates coming from the original repository as described above, please keep in mind that the vector and raster content distributed with this project is in binary format. There is no version control system yet capable to assist you in merging changes in binary content from different sources. Therefore, when making updates you should keep both copies - your version of the binary file and the new version coming upstream. Open them side-by-side in Photoshop or Illustrator, and attempt to transfer any modifications to your version manually.

For more information on binary merges, see the free on-line book about version control with Git: http://git-scm.com/book

#Contribute

Now, if you would like to share your modifications or new keyboard shortcuts with the world, you need to complete few steps in order to get it right. For more information you could review the relevant section of the Bluebird Glx-Dock Theme project: https://github.com/bogomirov/glx-dock-bluebird-theme#contribute


#Uninstall

Uninstalling the keyboard shortcut desktop images is pretty straightforward.

1. Ensure the desktop images are not used in your desktop theme, or you use a different theme completely by navigating to:

Start -> Control Panel -> Personalization -> Desktop Background

2. Remove the keyboard shortcuts project from your hard drive. Execute in Command Prompt:

rmdir /s %USERPROFILE%\AppData\Local\keyboard-shortcuts

Please note that with this operation you will irrecoverably delete all the files associated with the project, together with the history of their modifications. Therefore, if you have made any modifications to the project by yourself, it is advisable you to keep a backup of your work, e.g. by sharing it in on-line.

#Legal notices

All raster imagery used in and distributed through this project is believed to be in the "public domain" and of unknown to the author origin. The author does not intend to infringe any legitimate intellectual right, artistic rights or copyright. If you are the rightful owner of any of the raster images used in this project, and you do not want it distributed, or if you require a suitable credit, then please contact the author of this project to immediately do whatever is needed either for the image to be removed or provide credit where it is due. Please note that all the content of this project is provided free of charge and therefore the author does not gain any financial benefit from its distribution.

Copyright on the project concept, layout design, vector artwork, image processing and composition &copy; 2014, Bogomir Bogomirov.

This project is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons Attribution 4.0 International License](https://i.creativecommons.org/l/by/4.0/80x15.png)
