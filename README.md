####LICENSE: GPL 2.0

![alt tag](https://lh3.googleusercontent.com/z7RoMGVtvrMri2S5QkDyj0n2Ji6W-GcOt3Zl3QhtQY0=w1366-h768-rw)

###Introduction to Cycripter
A mini-mobile Scripting tool for Android, Cycripter runs some simple commands to make things easier for you. Enter and go! It carries out the function coded, giving a command-line-ish experience combined with a mini-scripter.

###Android Core
Cycripter is powered by a built-in, little programming language called Core, developed by me. Here is some example Core code to get you started:
<br>
<br>• android.print(&quot;TEXT&quot;)
<br>• android.print(NO. x/+- NO.)
<br>• android.action([callNumb]-NO.)
<br>• android.action([textMssg]-&quot;MSSG&quot;-NO.)
<br>• android.action([sendMail]-&quot;TITLE&quot;-&quot;MAIL&quot;-&quot;TO&quot;)
<br>
<br>This code can be found in the App's RemoteExpandedStyle of the Quick Settings Menu for CyanogenMod

###CyanogenMod 12.1+ Exclusive
Exclusveley for CyanogenMod 12.1+, using the Cyanogen Platform SDK, I added a custom quick tile with expanded menu within Quick Menu for Cycripter, integrating it in some capacity to the framework. Code for this called at the onCreate method at MainActivity.java, but it checks if the device runs CyanogenMod and the right version of the Custom ROM for the Quick Tile feature to work, so it won't affect the app experience for users/developers not running CyanogenMod 12.1+.

###Current Development Focus
• Code Efficency/Simplification (as of 29/11/15)

###Requirements + Dev. Status
|                 | Stock Android       | CyanogenMod|
| -------------   |:-------------:| -----:    |
| Minimum Version    | 4.0 (ICS)     | 9.1       |
| Min. V. for Quick Settings Tile/Menu | N/A           |   12.1    |
| Development Status   | Active     |    Active     |

###Credits
• Thanks to <a href="http://www.github.com/futuresimple">Base Labs</a> and <a href="http://www.github.com/chalup">chalup</a> for their Floating Action Menu+Labels for FABs library.
