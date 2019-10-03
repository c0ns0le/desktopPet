# Changelog
 
 <h3>In the next release:</h3>
 <ol>
   <li>Fixed cutting problem
   <li>Auto update over GitHub for portable version
 </ol>
 
 <h3>Version 1.2.2<sup>08 jul 2019</sup>:</h3>
 <ul>
   <li>Improved border detection, also top and bottom border (not only left and right)
   <li>Some times on respawn, pet was cut in a wrong way
 </ul>
 
 <h3>Version 1.2.1<sup>02 jul 2019</sup>:</h3>
 <ul>
   <li>Improved border detection, now the pet will walk until the border was reached, not before.
   <li>Improved multiscreen, pet will not be visible on the second screen when it leaving the area to respaw
   <li>Improved spawn, it should not blink anymore before spawning again
   <li>NEKO, another mate from 1995 is now available
   <li>GITHUB-Mates! From now, UWP, portable and javascript applications can access the GitHub repository to download new pets.
   <li>Please use the offline editor before uploading the new animation on GitHub as it will validate your xml and check it. 
 </ul>
 
 <h3>Version 1.2.0<sup>12 jun 2019</sup>:</h3>
 <ul>
   <li>Same version as the UWP (Windows 10) version - now as portable (see GitHub).
   <li>Without certificate, maybe the antivirus will give a warning
   <li>Multiscreen added (set it in the option dialog)
   <li>If the application is not installed, the settings are saved in the application folder
   <li>Support for new animations format (https instead of http), since in future the animations will be moved to github.
   <li>NEW OFFLINE EDITOR! CHECK THE GITHUB-PROJECT TO DOWNLOAD THE PREVIEW. 
 </ul>

 <h3>Version 1.0.7<sup>13 jan 2018</sup>:</h3>
 <ul>
   <li>Improvement in the option dialog (help over GitHub).
   <li>My certificate will expire in 5 days and the price is too high now... Don't know if I will ever pay a new certificate :P
 </ul>
 
 <h3>Version 1.0.6<sup>12 aug 2017</sup>:</h3>
 <ul>
   <li>Under options you can start multiple pets when the application starts.
 </ul>
  
 <h3>Version 1.0.5<sup>07 mar 2017</sup>:</h3>
 <ul>
   <li>Multiple childs can be created from the same animation ID
   <li>Online editor can check your xml values, so it gives less errors on the application once released
   <li>Check the new animations under Options!  
 </ul>
 
 <h3>Version 1.0.4<sup>22 feb 2017</sup>:</h3>
 <ul>
   <li>Solved a bug with the icon, if you downloaded an animation with a wrong icon it was not possible to run the app again
 </ul>
 
 <h3>Version 1.0.3<sup>08 feb 2017</sup>:</h3>
 <ul>
   <li>Developers can generate agraphically image from the XML animation: see blog (thank you Robin)
   <li>Improved memory usage (thank you Robin)
   <li>Offset of the pet was not calculated correctly
 </ul>
 
 <h3>Version 1.0.2<sup>02 feb 2017</sup>:</h3>
 <ul>
   <li>Solved a bug when the sheep was falling (app crashed)
   <li>Window will not be set on foreground anymore (you can set it back under options, if you want it)
   <li>The entire documentation can be found online on github now.
 </ul>
 
 <h3>Version 1.0.1<sup>21 jan 2017</sup>:</h3>
 <ul>
   <li>Solved a bug with the fullscreen (pet was set in background even if there wasn't a fullscreen window)
   <li>Increased stability with wrong formatted animations
   <li>New certificate to sign open source application (last one was expired)
 </ul>
 
 <h3>Version 1.0.0<sup>01 jan 2017</sup>:</h3>
 <ul>
   <li>Version 1.0! This application works without any big bugs now :D
   <li>Fullscreen detection, if a movie is playing, the sheep will not be on top most anymore
   <li>Bring to top, if you click on the tray icon, the sheep will be on top most again
 </ul>
 
 <h3>Version 0.9.8 (beta)<sup>13 aug 2016</sup>:</h3>
 <ul>
   <li>If sound player fails, you can see the error on options.
   <li>Corrected the position of the pet if you have the taskbar on the top.
   <li>Removed the async sound, please use the gSheep pet (under option), it is much better than my sheep :P
 </ul>
 
 <h3>Version 0.9.7 (beta)<sup>19 jun 2016</sup>:</h3>
 <ul>
   <li>Default animation had too much sounds
   <li>Pet can create childs and child can create sub-childs.
 </ul>
 
 <h3>Version 0.9.6 (beta)<sup>14 jun 2016</sup>:</h3>
 <ul>
   <li>Border collision sets the pet on the right position.
   <li>Possibility to add sounds (NAudio was implemented)
   <li>Option dialog redesigned
 </ul>
   
 <h3>Version 0.9.5 (beta)<sup>17 apr 2016</sup>:</h3>
 <ul>
   <li>Child can't be picked anymore
   <li>Animation will not steal anymore current window focus when created
   <li>Application update notification appear only if the application is installed
   <li>The last frame of a single animation was not executed correctly
   <li>Solved bug with offsetY in the XML animation
 </ul>
 
 <h3>Version 0.9.4 (beta)<sup>16 apr 2016</sup>:</h3>
 <ul>
   <li>Solved a bug with screen border detection
   <li>If an update is available, the changelog will be show
 </ul>

 <h3>Version 0.9.3 (beta)<sup>14 apr 2016</sup>:</h3>
 <ul>
   <li>Double click to close a single pet
   <li>Publish and create an installer with your PET without see any sheep on the app!
   <li>Solved child animations bugs
   <li>A respawn will be executed when pet is outside the screen and not on collision with the borders
   <li><em>3 new animations for the sheep</em>
   <li>General improvements, like fading pet or installing application
 </ul>

 <h3>Version 0.9.2 (beta)<sup>25 mar 2016</sup>:</h3>
 <ul>
   <li>Optimized source code
   <li>Reading XML with XML serialisation instead of the internal parser
   <li>Smoother movements of the pet 
 </ul>

 <h3>Version 0.9.1 (beta)<sup>25 feb 2016</sup>:</h3>
 <ul>
   <li>Solved a bug with the Culture (countries with "," as comma)
 </ul>
 
 <h3>Version 0.9.0 (beta)<sup>04 feb 2016</sup>:</h3>
 <ul>
   <li>Solved falling bug (window was always take to front)
   <li>Installer integrated in the application
   <li>Signed with SHA-2 Certum Open Source Certificate
 </ul>
 
 <h3>Version 0.8.8 (beta)<sup>03 feb 2016</sup>:</h3>
 <ul>
   <li>Code comments updated: <a href='https://github.com/Adrianotiger/desktopPet/blob/master/Docs/Documentation.chm?raw=true'>API documentation</a>
   <li>If a pet can't be spawn, a default position will be used. 
   <li>About box shows you the information of the current animation.
   <li>Possibility to <b>install</b> application directly from the app.
   <li>Application can be copied in the windows autostart menu!
 </ul>
 
 <h3>Version 0.8.5 (beta)<sup>27 jan 2016</sup>:</h3>
 <ul>
   <li>Code is commented and uploaded here: <a href='https://github.com/Adrianotiger/desktopPet/blob/master/Docs/Documentation.chm?raw=true'>API documentation</a>
   <li>Window will not flash anymore when the sheep fall over it
   <li>Sheep XML animation was optimized
   <li>Solved a little bug when an animation was over
   <li>Application can be executed twice
 </ul>
 
 <h3>Version 0.8.1 (beta)<sup>21 jan 2016</sup>:</h3>
 <ul>
   <li>Begun to commenting source code
   <li>Optimized xml/xsl for animations
   <li>Added detection to screen borders
   <li>Try the beta pet: Arcanoid (go under options and select BETA PET: Nr "7")
   <li>Optimized the online pet editor
 </ul>
 
 <h3>Version 0.8 (beta)<sup>15 jan 2016</sup>:</h3>
 <ul>
   <li>Added a certificate to the application (to increase reputation)<br />
   <li>More "child" animations features<br />
   <li>Solved some bugs with option and about box<br />
   <li>A new webpage design!<br />
 </ul>
 
 <h3>Version 0.7 (beta)<sup>11 jan 2016</sup>:</h3>
 <ul>
   <li>Added child animations, for bath/flowers and so on<br />
   <li>Under option, you can select between 2 animations<br />
   <li>Make your PET under <a href='pets/generator.php'>XML generator</a><br />
   <li>Added a new animation to the sheep<br />
 </ul>
 
 <h3>Version 0.6.1 (beta)<sup>06 jan 2016</sup>:</h3>
 <ul>
   <li>xml and xsd updated, to allow more functionality and more flexibility.<br />
   <li><a href='pets/generator.php'>XML generator</a>, to allow you to create your mate!
 </ul>
 
 <h3>Version 0.6 (beta)<sup>03 jan 2016</sup>:</h3>
 <ul>
   <li>Run-animation was wrong (sheep running to the screen border)<br />
   <li>New collaborator <b>Sergi</b> made some changes:<br />
   <li>removed the mountain and replaced it with a tray icon<br />
   <li>added an about box<br />
 </ul>
 
 <h3>Version 0.5 (beta)<sup>23 dec 2015</sup>:</h3>
 <ul>
   <li>Rewrote completly the code, to be open source<br />
   <li><s>Sheep can take a bath</s><br />
   <li>You can create your own animation!!!<br />
   <li>Check the project page: <a href='https://github.com/Adrianotiger/desktopPet/'>GitHub</a><br />
   <li>Check the manual page to create your own animation: <a href='https://github.com/Adrianotiger/desktopPet/wiki'>Wiki</a><br />
 </ul>
 
 <h3>Version 0.3 (beta)<sup>15 dec 2015</sup>:</h3>
 <ul>
   <li>Better performance<br />
   <li>Optimized window detection and detect if window is not anymore in foreground<br />
   <li>Sheep can pee<br />
   <li>Sheep can fall down from taskbar (reborn)<br />
   <li>Sheep can take a bath<br />
 </ul>
 
 <h3>Version 0.2 (beta)<sup>10 dec 2015</sup>:</h3>
 <ul>
   <li>Added "info dialog" functionality<br />
   <li>Sheep can sleep in 2 different ways<br />
   <li>Sheep falls down in a better way<br />
   <li>Detect window on the desktop and walk on it<br />
   <li>Hurt on the screen border<br />
   <li>Kill all sheeps<br />
 </ul>
 
 <h3>Version 0.1 (beta):</h3>
 <ul>
   <li>First version. Sheep can walk and run on the taskbar.
 </ul>
</div>