# Intro-to-Unix-Shell

UCI Libraries

February 21, 2018

3:00 pm - 4:30 pm

Instructors: Danielle Kane, Laura Smart

Helpers:
General Information

The Unix shell has been around longer than most of its users have been alive. It has survived so long because it’s a power tool that allows people to do complex things with just a few keystrokes. More importantly, it helps them combine existing programs in new ways and automate repetitive tasks so they aren’t typing the same things over and over again. Use of the shell is fundamental to using a wide range of other powerful tools and computing resources (including “high-performance computing” supercomputers). These lessons will start you on a path towards using these resources effectively.

Who: 

Where: Tomás Rivera Li, 900 University Ave., Riverside, CA 92521. Get directions with OpenStreetMap or Google Maps.

When: March 1, 2018. Add to your Google Calendar.

Requirements: Participants must bring a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed below). They are also required to abide by Software Carpentry's Code of Conduct.

Accessibility: We are committed to making this workshop accessible to everybody. The workshop organisers have checked that:

    The room is wheelchair / scooter accessible.
    Accessible restrooms are available.

Materials will be provided in advance of the workshop and large-print handouts are available if needed by notifying the organizers in advance. If we can help making learning easier for you (e.g. sign-language interpreters, lactation facilities) please get in touch (using contact details below) and we will attempt to provide them.

Contact: Please email kaned@uci.edu for more information.

Schedule

Surveys

Ask your instructor about pre- and post-workshop Survey details.
A.M. Data Intro for Librarians
08:30 	Sign in, coffee
09:00 	Jargon Busting
09:15 	Foundations
10:15 	Break
10:30 	Regular expressions
11:15 	Exercises
11:45 	Lunch break

05:30 	End

We will use this collaborative document for chatting, taking notes, and sharing URLs and bits of code.

Syllabus
Data Intro

    Intro to data
    Jargon busting
    Keyboard shortcuts
    Plain text formats
    Naming files
    Regular expressions
    Reference...

The Unix Shell

    Files and directories
    History and tab completion
    Counting and sorting contents in files
    Pipes and redirection
    Mining or searching in files
    Reference...

Setup

To participate in a Library Carpentry workshop, you will need access to the software described below. In addition, you will need an up-to-date web browser.

We maintain a list of common issues that occur during installation as a reference for instructors that may be useful on the Configuration Problems and Solutions wiki page.
The Bash Shell

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.
Windows
Video Tutorial

    Download the Git for Windows installer.
    Run the installer and follow the steps bellow:
        Click on "Next".
        Click on "Next".
        Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
        Click on "Next".
        Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
        Keep "Use Windows' default console window" selected and click on "Next".
        Click on "Install".
        Click on "Finish".
    If your "HOME" environment variable is not set (or you don't know what this is):
        Open command prompt (Open Start Menu then type cmd and press [Enter])
        Type the following line into the command prompt window exactly as shown:

        setx HOME "%USERPROFILE%"
        Press [Enter], you should see SUCCESS: Specified value was saved.
        Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.
Mac OS X

The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). See the Git installation video tutorial for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop.
Linux

The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.
Text Editor

When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like automatic color-coding of key words. The default text editor on Mac OS X and Linux is usually set to Vim, which is not famous for being intuitive. if you accidentally find yourself stuck in it, try typing the escape key, followed by :q! (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell.
Windows
Video Tutorial

nano is a basic editor and the default that instructors use in the workshop. To install it, download the Library Carpentry Windows installer and double click on the file to run it. This installer requires an active internet connection.

Others editors that you can use are Notepad++ or Sublime Text. Be aware that you must add its installation directory to your system path. Please ask your instructor to help you do this.
Mac OS X

nano is a basic editor and the default that instructors use in the workshop. See the Git installation video tutorial for an example on how to open nano. It should be pre-installed.

Others editors that you can use are Text Wrangler or Sublime Text.
Linux

nano is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are Gedit, Kate or Sublime Text.
Copyright © 2016 Library Carpentry
