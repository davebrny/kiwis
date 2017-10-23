# kiwis 🥝
> open a **k**eyword **i**n a **w**ebsite's **i**nternal **s**earch  

<a href="url"><img src="https://i.imgur.com/EpEUQpo.jpg"></a><br></br>


## installation

- install [AutoHotkey](https://www.autohotkey.com)  
- download and extract the [latest release](https://github.com/davebrny/kiwis/releases) .zip file  
- run [kiwis.menu.ahk](kiwis.menu.ahk)  
&nbsp;



## usage

- highlight a word   
- use <kbd>ctrl</kbd><kbd>alt</kbd> + <kbd>k</kbd> to open the menu  
- (at the top of the menu you will see the word you selected)  
- select a website from the list to have it open with the word already searched    

> if no text is selected then the website will be launched without searching anything  

&nbsp;


#### adding new sites  

- go to a site's internal search and search the word `kiwi`  
- copy and paste the url into the `[kiwis]` ini section at the top of [kiwis.menu.ahk](kiwis.menu.ahk)  
```
url example:  https://github.com/search?&q=kiwi&type=  
ini format:   website name = url   
```

- give the website a name, then add that name to the menu text in the [ezMenu] ini section  
- right click on the tray menu icon and select "reload this script" to update your changes  

&nbsp;


## options  

**start with windows**  

to have the script start when windows boots up, select "start with windows" from the tray icon    
&nbsp;
