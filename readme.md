# kiwis 🥝
> open a **k**eyword **i**n a **w**ebsite's **i**nternal **s**earch  

<a href="url"><img src="https://i.imgur.com/qERpvSX.jpg"></a><br></br>


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

> right click on the tray menu icon and select "reload this script" to update your changes  

&nbsp;

#### using ezMenu  

the menu in this script is generated using ezMenu. &nbsp;you can read more about that [here](https://github.com/davebrny/ezMenu) but the main things that would be useful to know for this script are:  

- lines that are indented by 1 tab or 4 spaces become sub-menus  
- lines that contains 3 dashes `---` and nothing else will turn into menu separators  
- putting a full stop at the start of the line disables it and turns the text grey  
&nbsp;


## options  

**start with windows**  

to have the script start when windows boots up, select "start with windows" from the tray icon    
&nbsp;
