# my-dear-diary
Diary software in one page of code.

#My Dear Diary

A command line diary in Falcon language. 

#Summary

This is a diary application for the command line. It has all features you need to keep
a diary and all that is packed in a short page of code. 

#History
I created this application in 2012. I pasted it at https://groups.google.com/forum/#!topic/falconpl/bVePM1TPlyo .
Now, time later I decided to put the application in my bitbucket account.

#Requirements

1. Falcon interpreter: http://www.falconpl.org/project_dl/_official_rel/Falcon_0_9_6_8_VS9.exe
2. Windows 7.
3. After you install falcon, there are a couple of things you need to do:
if you do not have sqlite3_fm.dll in falcon\bin\dbi, create directory dbi under falcon\bin (if it does not exist).
Then, place the file in dbi directory, from falcon\bin.

#Use

Start application with: falcon MyDearDiary.fal . Type your diary entry.

There are the following commands:
1. commands. It displays commands.
2. clear. It deletes current entry.
3. exit. Exits application.
4. save DD/MM/YYYY. It saves current entry.
5. load DD/MM/YYYY. It loads specified entry.
6. load entries. It shows all your entries.
7. display. It display current entry.

