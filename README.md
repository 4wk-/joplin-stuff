# joplin-stuff
Custom CSS, settings, etc for Joplin - https://github.com/laurent22/joplin  
*Joplin is a free and open-source desktop and mobile note-taking application, named after the ragtime composer and pianist, Scott Joplin.*


## Get the old color scheme for standard editor (pre 2.2.2)
Some changes were added to Joplin in the past month that changed the style (colors, fonts, etc) of the Markdown editor ([#5174 Codemirror theme update](https://github.com/laurent22/joplin/pull/5174) // [#5314 Improved Markdown editor code styling](https://github.com/laurent22/joplin/pull/5314) // [Added margin for readability](https://discourse.joplinapp.org/t/please-read-this-if-you-are-wondering-why-theres-now-a-margin-on-the-note-text/19585), among other things).

In this attempt, I wrote some custom CSS put in the file [**userchrome.css**](https://github.com/4wk-/joplin-stuff/blob/main/userchrome.css) that outclass the regular CSS, for the Light theme. This file is usually located in `C:\Users\XXX\.config\joplin-desktop\` on Windows, but you also can access it throught Joplin settings.  
You also need to update those settings, in **Options > Appearance**:  
```
Editor font size = 12
Editor font family = Courier New
Editor monospace font family = Courier New
Editor maximum width = 0
Custom stylesheet for Joplin-wide app styles => (paste the content of userchrome.css file here)
```

--- 

Here is a visual example (open in a new tab and zoom):  
![JoplinCustomCSS](https://user-images.githubusercontent.com/1439550/154075280-24c1cf05-6b5d-40ac-ad7e-f42fe7fbfe6e.png)

---

Here are the settings you need to edit:  
![JoplinCustomSettings](https://user-images.githubusercontent.com/1439550/154076620-19ce650a-3b6d-440d-a818-b8d4ab775b95.PNG)

---

I might have missed some other changes, so let me know if you find something that need to be tweaked as well!  
Feel free to contact me.
