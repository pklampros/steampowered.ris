# Ludography / Steam Videogame Citation Info grabber
Runs a browser script on game websites of Steam, that allows exporting a RIS file (that includes the bibliographical information of the game) in order to help add them in a bibliography catalogue and cite apps and video-games from steampowered.com
Creates a new button next to the "Community hub" button, downloads a RIS file, importable in Bibliography management software.

## Installation instructions: 
  1. Install a user script manager for your browser 
    * Tampermonkey browser plugin - https://tampermonkey.net (supports Chrome, Opera, Safari, Firefox, Microsoft Edge and more) 
    * or Greasemonkey of Firefox - http://www.greasespot.net
  2. Import the script to the plugin
    * Click on the plugin icon on your browser (next to address bar) and then "Add new script" 
    
## What it does: 
1. Upon visiting any game on the Steam website, the script will add a button on the top right, labled "EXPORT CITATION (RIS)". 
2. By pressing the button, a RIS file will be downloaded on your computer. 
3. RIS Files are compatible and can be imported in:
  * Zotero (recommended - free and open source bibliography management and citation software Zotero.org) 
  * EndNote (commercial bibliography and citation software by Reuters) 
  * Mendeley (bibliography and citation software by Elsever) 
  * Citavi (commercial PC bibliography management software) 

## What the citation includes: 
  * Entry as "_Computer Program_"
  * Game title as "_Title_" 
  * Developer as "_Programmerer_" & "_Company_" 
  * Publisher (if applicable) as "_Programmer_" 
  * Release Date as "_Date_" 
  * Description as "_Abstract_"
  * Steam URL as "_URL_"
  * Also RIS download date as "_Accessed_" 
  
  ![Zotero Info panel](https://image.ibb.co/bB9vrR/Screen_Shot_2017_10_16_at_15_21_05.png ){:height="50%" width="50%"}
  
## Notice 
There is no "correct" way for citing videogames and few guidlines are available for that. However this might be a first ste

## Known issues:
  * Entries are made as "Computer Programs". 
## To-do:
  * Platforms
