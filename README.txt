{\rtf1\ansi\ansicpg1252\cocoartf1187\cocoasubrtf390
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural

\f0\fs24 \cf0 This is a (hopefully temporary) fix to allow  WiiFlashServerJ to run on\
OS X 10.8 "Mountain Lion". *You do not need this* if you use an\
earlier version of OS X.\
\
Step 1: Download WiiFlashServerJ+BSB at http://cote.cc/w/wp-content/uploads/drupal/WiiFlashServerJ+BSB.app_.zip and move it to your Applications folder.\
\
Step 2: Right click and check 'Run in 32 bit mode'.\
\
Step 3: Run "WiiFlash.command" instead of starting WiiFlashServerJ+BSB.\
directly (from the Dock or the Applications folder) as you'd normally do.\
WiiFlash.command is a shell script that will start the regular\
WiiFlashServerJ+BSB application (via the Terminal).\
\
You can put this script anywhere you want, but it is important that is\
in the same folder as the file "IOBluetooth". For convenience, the script\
can also be put in right area of the Dock (where the Trash and folders are),\
and can be launched by clicking on it.\
\
Note: If running files doesn't launch application, open the .command files in textedit and change the paths.}