# [Source](https://github.com/supertux-community/supertux-pre-0.1-archive/blob/main/0.0.6/ChangeLog)

CHANGES.txt for Super Tux

by Bill Kendrick & Tobias Glaesser
bill@newbreedsoftware.com
http://www.newbreedsoftware.com/supertux/


0.0.6 - March 15th, 2004
---------------------------
  * Game save/load feature.
    Tobias Glaesser <tobi.web@gmx.de>
 
  * Created Level 4 (Tux in Sky)
    Ricardo Cruz <rick2@aeiou.pt>

  * Created Level 3 (Mondo)
    Philippe Saint-Pierre <stpere@linuxmail.org>

  * New collision detection. (object vs. map)
    Tobias Glaesser <tobi.web@gmx.de>
  
  * Nice level-editor help text.
    Christopher A. Webber <creat0r@lingocomic.com>

  * Compiling with g++ is supported.
    Tobias Glaesser <tobi.web@gmx.de>
 
  * Added realistic physics.
    Tobias Glaesser <tobi.web@gmx.de>

  * Created new letters.
    Ingo Ruhnke <grumbel@gmx.de>

  * Gameplay fixes. (with the aim to make it at least as playable as 0.0.5 was)
    Tobias Glaesser <tobi.web@gmx.de>

  * Flexible font (text) handling.
    Tobias Glaesser <tobi.web@gmx.de>

  * Rewritten menu code.
    Tobias Glaesser <tobi.web@gmx.de>

  * Upgrades go into the opposite direction Tux collided with.
    Ricardo Cruz <rick2@aeiou.pt>

  * First implementation of a graphical leveleditor interface.
    Tobias Glaesser <tobi.web@gmx.de>
    
  * You can test levels directly in the leveleditor.
    Ricardo Cruz <rick2@aeiou.pt> & Tobias Glaesser <tobi.web@gmx.de>
    
  * Reinit timers when tux dies.
    Duong-Khang NGUYEN <neoneurone@users.sf.net>

  * Got rid of the TEXTURE_RECTANGLE NVIDIA extension. It should be possible
    to play the game in OpenGl mode with the most graphic cards now.
    Tobias Glaesser <tobi.web@gmx.de>   
  
  * Added optional backgrounds for levels.
    Tobias Glaesser <tobi.web@gmx.de>
    
  * First code to optimize the FPS. The maximum are 100 FPS.
    Tobias Glaesser <tobi.web@gmx.de>    

  * Introduced command line option --show-fps. It's self-describing. :)
    Tobias Glaesser <tobi.web@gmx.de>

  * Text is displayed correctly in OpenGL mode now.
    Tobias Glaesser <tobi.web@gmx.de>
  
  * Alpha works in OpenGL mode now.
    Tobias Glaesser <tobi.web@gmx.de>
        
  * Rewrite of text/font related code, which should bring huge performance increases to you.
    Tobias Glaesser <tobi.web@gmx.de>    

  * Added a highscore background and improved the name input code.
    Tobias Glaesser <tobi.web@gmx.de>
        
  * Added feature to enter your name for a new highscore. 
    Ricardo Cruz <rick2@aeiou.pt>
        
  * Grid support for the leveleditor and you can look
    what's inside a brick now.
    Ricardo Cruz <rick2@aeiou.pt>    

  * Initial infrastructure for mapping keys.
    Tobias Glaesser <tobi.web@gmx.de> & Ricardo Cruz <rick2@aeiou.pt>

  * Fixed a little displaying bug of upgrades.
    Ricardo Cruz <rick2@aeiou.pt> 
    
  * Improved and fixed the sound support another time.
    Duong-Khang NGUYEN <neoneurone@users.sf.net>    
    
  * Fixed uncorrect use of TIME_WARNING.
    Duong-Khang NGUYEN <neoneurone@users.sf.net>    

  * Provided hint for fixing memory leak when fullscreen is toggled.
    Ricardo Cruz <rick2@aeiou.pt> 
    
  * Made the code more flexible. This means we could add support for two-player games
    relativly easily and add tons of bad guys in the future.
    Tobias Glaesser <tobi.web@gmx.de>

  * You can achieve as many frames as your hardware allows now.
    Tobias Glaesser <tobi.web@gmx.de>

  * Timers calculate with the real time now.
    (FIXME: Pause doesn't work properly for now)
    Tobias Glaesser <tobi.web@gmx.de>

  * Added OpenGL mode.
    Tobias Glaesser <tobi.web@gmx.de>  

  * Restructured much code or even all code of SuperTux in an object orientated way.
    Yeah, that's even possible in C and brought many new source-files to us. ;)
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixes and improvements for the leveleditor.
    Ricardo Cruz <rick2@aeiou.pt> 

  * WIN32 build fixes and memory freeing fixes.
    Duong-Khang NGUYEN <neoneurone@users.sf.net>

  * Can now hold and shoot laptops by holding fire and approaching a flat one.
    Dan Koestler <offipso@abeminds.com>

  * Fixed possible segfaults.
    Tobias Glaesser <tobi.web@gmx.de>
    
  * Reorganized level-code and introduced level-subset-structure.
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixed Amiga/MorphOS build problem.
    SixK <dasixk@free.fr>
  
  * Improved menu.
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixed the menu-flickering and added a cool shadow effect.
    Ricardo Cruz <rick2@aeiou.pt> & Tobias Glaesser <tobi.web@gmx.de>

  * Fixed some issues around our new leveleditor.
    Tobias Glaesser <tobi.web@gmx.de>

  * New leveleditor! I'd like to put a second and a third exclamation mark here. :)
    Ricardo Cruz <rick2@aeiou.pt>

  * Added: stereo sounds
    Duong-Khang NGUYEN <neoneurone@users.sf.net>

  * Added: displaying tux left
    Tobias Glaesser <tobi.web@gmx.de>

  * Added: --disable-music and music on/off menu option
    Duong-Khang NGUYEN <neoneurone@users.sf.net>

  * Changed out some music.  Created sped-up versions of songs for when
    time is running out.
    Bill Kendrick <bill@newbreedsoftware.com>

  * New laptop enemy graphics.  Sounds when you stomp and kick them.
    Bill Kendrick <bill@newbreedsoftware.com>


0.0.5 - December 24th, 2003
---------------------------
  * Added "Level 2"
    Tobias Glaesser <tobi.web@gmx.de>

  * Added a menu. You can set sound and fullscreen on and off for example.
    Tobias Glaesser <tobi.web@gmx.de>
    
  * Improved sound handling again. Added: playing different
    songs in one level is now supported (now we need new songs!)
    Duong-Khang NGUYEN <neoneurone@users.sf.net>
    
  * Added 'PAUSE' feature.
    Tobias Glaesser <tobi.web@gmx.de>

  * Levels have to specify a theme now.
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixed FIXME (tux doesn't die anymore, when he reaches the end of a level).
    And added a result-screen. (Nothing spectacular ;) )
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixed FIXME (sound when 100 distros are reached).
    And set the maximum lives to 4.
    Tobias Glaesser <tobi.web@gmx.de>

  * New images for the shared folder.
    Duong-Khang NGUYEN <neoneurone@users.sf.net>

  * command-line option "--disable-sound" and "--help" now work
    Duong-Khang NGUYEN <neoneurone@users.sf.net>
    
  * Added high score feature.
    Adam Czachorowski <gislan@o2.pl>

  * Surfaces converted to display format for speed.
    (Thanks to SDL_DisplayFormatAlpha() - wasn't around a few years ago!)

  * Sped up FPS (throttle)

  * Adding a new level (level,images,music) should be very easy now!
    Tobias Glaesser <tobi.web@gmx.de>

  * Shooting enemies increases score
    Tobias Glaesser <tobi.web@gmx.de>

  * Game over sequence.
    Tobias Glaesser <tobi.web@gmx.de>

  * Added 'make install PREFIX=/usr' and 'make uninstall PREFIX=/usr'
    Tobias Glaesser <tobi.web@gmx.de>

  * Initial support for additional levels.
    Tobias Glaesser <tobi.web@gmx.de>

  * One-ups ever 100 distros
    Tobias Glaesser <tobi.web@gmx.de>

  * Fixed up Makefile
    Tobias Glaesser <tobi.web@gmx.de>

0.0.4 - July 15, 2002
---------------------
  * Fixed source so that "nosound" target would actually compile and build.


0.0.3 - May 27, 2002
--------------------
  * Redid level 1.
  * Coin bricks can be hit multiple times.
  * You lose shooting (coffee) power-up if you get hurt.
  * Jump bug fixed.
  * Added "distros" counter to screen.
  * Added new enemy: Evil Money Bags
  * Game aborted if sounds/music couldn't be loaded.  Fixed.


0.0.2 - November 8, 2001
------------------------
  * Added "--version" and skeleton "--help" displays
  * More sound effects.
  * Laptop bad-guy fixed.
  * Skidding images created.
  * Initial music code added.
  * Bullets kill enemies.
  * Golden Herring (invincibility) upgrade added.


0.0.1 - December 3, 2000
------------------------
  * New title screen
    Eric Windish <raptor@bwbohh.net>

  * Makefile fixes
    Ian <brooke@jump.net>


INITIAL RELEASE 0.0.0 - April 11, 2000
--------------------------------------
  * Initial alpha release.
