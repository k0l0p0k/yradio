# yradio
Internet Radio Player

Much inspired by PMRP from misko_2083, see:  
http://murga-linux.com/puppy/viewtopic.php?p=963382#963382  
Took as a base GUI concept for this from: Victor Ananjevsky's (yad author) "find frontend" example from here:  
https://sourceforge.net/p/yad-dialog/wiki/Frontend%20for%20find%2Bgrep%20commands/?limit=50  

Depends on **yad** (version 0.35 or higher) and **mplayer** installed.  

Search option has access to large database from "RadioSure" (commercial M$ app) converted to use with this app.
(need to click 'Update Index' first)    

**Options:**
- Load a Category or do a search
- Add (from Category list or search results) or remove to/from 'Favorites'      
- Save search results to a new 'Category'    
- Ability to rip the stream (requires "streamripper" installed)    
  
Forum thread:  
http://murga-linux.com/puppy/viewtopic.php?p=986591#986591

**Installation:**
```    
git clone https://github.com/fredx181/yradio.git  
```   
Make 'yradio' bash script executable:  
```  
chmod +x yradio  
```  
And run 'yradio' from yradio directory  
  
**Or:**    Download ZIP  
Extract and run 'yradio' from 'yradio-master' directory  
  
![yradio](YRadio.png)  
