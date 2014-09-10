Keyboard Shortcuts on your Desktop
==========================

Go faster, be more precise or quickly find alternative ways to accomplish your tasks. Transform your professional and under-utilized desktop background into an asset, essential to your digital production workflow.

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

As a software, internet or digital media professional, your time is of essence. You need to be quick and precise in accomplishing your tasks. That is why in your daily operations you rely heavily on your keyboard.

The software packages and environments you use nowadays however, are huge. Together with their extensions, they provide you with multiple ways to accomplish almost anything in your field.

**The only problem is, if you could remember how.**

When under pressure, gunning for that deadline, you have no time to dwell into manuals, learn new features, let search for keyboard shortcuts. You just blindly run, relying on what you know by heart. But human memory is a tricky thing. It does not always play by the rules you may expect. As a result you stick to the basics, start making errors, and ultimately slip away from your performance targets.

**The images provided here intend to get you back on track, today.**

Your computer desktop is almost always in your field of vision, regardless whether you work, relax with your favorite game or have your attention away. As a plain image however, its background serves a little purpose. What could you possibly do to utilize that huge empty area on your desktop better?

The images provided here have been prepared with the intention to serve multiple purposes and strike balance on various conflicting criteria:

* To keep you focused on your task and provide you with extra tools, but without compromising the pleasant view in the back.

  * The panoramic background images provided here are desaturated and further have lowered contrast, so your attention gets distracted as little as possible. Their predominantly low details and visual depth effectively separate these images from everything above them.

  * On contrary, the applications you use, with their aggressive colors and widgets practically stand out on top of everything. They effectively fix your attention on completing your task.

  * By being placed on semi-transparent and desaturated bases on the one hand, the keyboard shortcuts blend with the panoramic background without compromising the view. On the other hand the crisp monochromatic text is clearly distinguishable from the applications you use. In this way the keyboard shortcuts unobtrusively "fly" in the middle.

  In overall, the clear distinction between panoramic view in the back, shortcuts in between and applications in front, tries to keep you focused on your task. On the other hand, you can visually switch between these three layers in a split-second.

* To enable you to find quickly what you need, so you can accomplish your task better.

  * It is practically impossible to fit all shortcuts of all possible applications on the limited space of a single desktop background. To circumvent this limitation, each of the images provided here refers to a single application environment. In this way you can switch the background images when needed.

  * While incorporating as much information as possible, the desktop shortcuts attempt to allocate the available space without hampering your visual comfort.

  * Use your precious time more efficiently. No need to sift through manuals or dig the Internet in order to find how to invoke a specific function. You already have the information you need in front of your eyes, all the time. Just move the window obstructing the relevant part of your desktop away, or press a single keystroke to minimize them all (Win+D on Windows&reg;).

  * Contrary to most user manuals, the emphasis here is on the functions your environment exposes, rather than on keyboard shortcuts. The various functions are further arranged by similarity on task-related groups, or attempt to mirror the layout of the widgets your application exposes. In this way you could find what you need quick.

* Promote learning on the go. As a side effect of how the various functions are arranged, while visually scrolling through your desktop background seeking the information you need, you can immediately realize how to accomplish many other similar tasks.

* Promote peaceful, calm but creative environment. Although being of subjective nature, moods and emotions can be rather important topics in establishing an environment that attributes to less errors and higher performance. Issues like these have been essential in the selection of the panoramic background images for this project.

In summary, instead of being just a plain image of dubious value, your professional desktop background can provide you with the speed, accuracy and cognitive offload you need in order to perform under pressure better.

![Screenshot of a Windows&reg; 7 Aero&reg; desktop with background image containing the keyboard shortcuts of Eclipse&trade; PDT (left half) and Aero&reg; desktop (right half)](screenshot.png)

Screenshot of a Windows&reg; 7 desktop with background image containing the keyboard shortcuts of both Eclipse&trade; PDT (left half) and Aero&reg; desktop (right half).

To create desktop backgrounds encompassing all display resolutions, multi-monitor layouts, application environments and personal tastes is practically impossible. That is why this project has been limited to cover a reference set-up with the following characteristics:

* Horizontal, linear dual 1080p (3840x1080 px) monitor layout

* Desktop background images covering the major keyboard shortcuts for the following applications and environments:

  * [Adobe&reg; After Effects&reg;](backgrounds/after-effects.png)

  * [Adobe&reg; Illustrator&reg;](backgrounds/illustrator.png)

  * [Adobe&reg; Photoshop&reg;](backgrounds/photoshop.png)

  * [Blender&trade;](backgrounds/blender.png)

  * [Eclipse&trade; IDE with PHP Development Tools](backgrounds/eclipse-pdt.png)

  * [Microsoft&reg; OneNote&reg;](backgrounds/onenote.png)

  * Microsoft&reg; Windows&reg; 7 Aero&reg; desktop

The templates provided can be used to correct and supplement the shortcuts you need, or incorporate raster background imagery that appeals to you best.

#Prerequisites

To take maximum advantage of this project, you will need the following software installed:

* Git&trade; core client, in order to manage your local copy of the project files:  http://git-scm.com/downloads

* Illustrator and Photoshop, in order to use the provided templates

#Install

To install this project on Windows&reg; 7 for example, follow these steps:

1) Grab a copy of the project repository and place it in an appropriate local folder. Execute in Command Prompt:

```
  git clone https://github.com/bogomirov/keyboard-shortcuts.git ^
  %USERPROFILE%\keyboard-shortcuts
```

2) Enable any or all of the desktop backgrounds. Navigate to:

```
  Start -> Control Panel -> Personalization -> Desktop Background
```

    and browse to the folder where the background images have been installed. In our example that would be:

```
  C:\users\<your-user-name>\keyboard-shortcuts\backgrounds
```

3) Select any or all of the desktop backgrounds and adjust the timing of their appearance to your liking.

4) Press `Save changes`

5) Optionally, save the desktop theme under a new name.

From now on, you can switch desktop backgrounds with respect to the application you use. Right-click on an empty area on your desktop and choose `Next desktop background`.

If you are satisfied with the background images as they are provided by this project and never plan to make any modifications, you can conserve some disk space by removing the templates. Execute in Command Prompt:

1) Switch to the location of the keyboard shortcuts repo:

```
  cd %USERPROFILE%\keyboard-shortcuts
```

2) Remove the templates from your working tree and index:

```
  git rm -r templates
```

3) Commit the changes to your local repo:

```
  git commit -am "Removed the templates dir, not planning to make any customizations"
```

In this way the templates will never re-appear inside the installation directory whether you make subsequent upgrades or merges. This action is reversible however, whenever you choose to.

#Upgrade

You can upgrade your local copy of the project with the last changes in the remote repository pretty easily. On Windows&reg; 7 for example, execute in Command Prompt:

1) Switch to the folder where you have installed your local copy:

```
  cd %USERPROFILE%\keyboard-shortcuts
```

2) Pull the latest changes:

```
  git pull origin master
```

3) Verify that the backgrounds you like are still available to your theme by navigating to:

```
  Start -> Control Panel -> Personalization -> Desktop Background
```

#Modify

Modifying the desktop backgrounds provided by the project is pretty straightforward.

1. Use the Photoshop templates to generate raster background images with the exact size of your full desktop.

  Keep in mind that to achieve the effect intended by this project, the images should be of low contrast and subsequently desaturated. Whether they are predominantly bright or dark is to your liking but ensuring low contrast is important.

2. Export the background images from Photoshop as an intermediary `.png` in the 'templates' directory

3. Open the Illustrator template and link externaly the new intermediary `.png` images you exported from Photoshop

4. Make the changes you need to the shortcuts content or their layout

5. Export the so composited layers as `.png` images into the project's `backgrounds` directory

6. Delete the intermediary `.png` images you exported from Photoshop

7. As noted previously, ensure the new background images are available to your desktop theme

Do not forget to store the changes you made to the project files in your local Git repository. In this way you can switch back and forth between modifications, protect against accidental file loss, recover from errors, etc. Execute in Command Prompt:

1) Switch to the location where you have installed the keyboard shortcuts repo:

```
  cd %USERPROFILE%\keyboard-shortcuts
```

2) Commit the changes you have made, adding a relevant descriptive comment, e.g.:

```
  git commit -am "Created a new background image for my other application"
```

If, at this point and onwards you would like to incorporate in your local modifications also updates coming from the original repository (see the Upgrade section), please keep in mind that the Illustrator and Photoshop templates distributed with this project are binary files of proprietary format. So far, the safest way to merge changes in such content is the manual one:

1. When receiving updates to a template file, request to perform a manual merge. This will keep both copies - the version of the file modified by you, as well as the new version coming from upstream, both in the directory of the project.

2. Open both files side-by-side in Photoshop or Illustrator

3. Attempt to transfer any modifications to your version manually and save the file

4. Export the images from Photoshop or Illustrator as previously explained

5. Mark the conflicts as resolved

6. Commit the changes to your repository

For more information on binary merges, see the free on-line book about version control with Git: http://git-scm.com/book

#Contribute

If you would like to share the corrections or additions you have made to the project with the world, you need to complete few steps, similar to the ones outlined in the Bluebird Glx-Dock Theme: https://github.com/bogomirov/glx-dock-bluebird-theme#contribute

#Uninstall

You can uninstall the keyboard shortcuts project by following few steps. On Windows&reg; 7:

1) Ensure that there are no desktop images provided by the project who are currently in use by your desktop theme, or switch to a different theme completely. Navigate to:

```
  Start -> Control Panel -> Personalization -> Desktop Background
```

2) Remove the keyboard shortcuts project from your hard drive by executing in Command Prompt:

```
  rmdir /s %USERPROFILE%\keyboard-shortcuts
```

Please note that this operation will **irrecoverably delete** all the files associated with the project, together with the history of their modifications. Therefore, if you have made any modifications to the project by yourself, it is advisable to keep a backup copy of your work elsewhere, e.g. by sharing it in on-line.

#Legal notices

All raster imagery used in this project is believed to be in the "public domain" and of unknown to the author origin. The author does not intend to infringe any legitimate intellectual right, artistic rights or copyright. If you are the rightful owner of any of the raster images used in this project, and you do not want it distributed, or if you require a suitable credit, then please contact the author of this project to immediately do whatever is needed either for the image to be removed or provide credit where it is due. Please note that all the content of this project is provided free of charge and therefore the author does not gain any financial benefit from its distribution.

Adobe, After Effects, Illustrator and Photoshop are either registered trademarks or trademarks of Adobe Systems Incorporated in the United States and/or other countries.

Blender is a trademark of Stichting Blender Foundation.

Eclipse is a trademark of Eclipse Foundation, Inc.

Git is a trademark of Software Freedom Conservancy, Inc.

Microsoft, Aero, OneNote and Windows are either registered trademarks or trademarks of Microsoft Corporation in the United States and/or other countries.

"Keyboard Shortcuts on your Desktop" is an independent project and is not affiliated with, nor has it been authorized, sponsored, or otherwise approved by Microsoft Corporation.

Copyright on the project concept, layout design, vector artwork, raster background image processing and composition &copy; 2014, Bogomir Bogomirov.

This project is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons Attribution 4.0 International License](https://i.creativecommons.org/l/by/4.0/88x31.png)
