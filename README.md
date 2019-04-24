# Pictures

**Menu**<br />
<br />
<br />
           ![alt text](https://i.gyazo.com/cc2cd034b7320437cc28fdb7c5d9b9a2.png)


**Dialog**<br />
![alt text](https://i.gyazo.com/bbd10ce9f0bcf1e975576fe0e6da3a2f.png)

# Installation
**How to install Menu**<br />
**1.** Go to *esx_menu_default/html/css/app.css*<br /> <br />
**2.** Replace everything inside the *app.css* with everything from the menu file above.<br /> <br />
**3.** Save it and then restart *esx_menu_default*

**How to install Dialog**<br />
**1.** Go to *esx_menu_dialog/html/css/app.css*<br /> <br />
**2.** Replace everything inside the *app.css* with everything from the dialog file above.<br /> <br />
**3.** Go to *esx_menu_dialog/html/js/app.js*, then delete line 5.<br /> <br />
**4.** After that, replace the line 5 with this 

```javascript
'{{#isDefault}}<input type="text" name="value" placeholder="{{title}}" id="inputText"/>{{/isDefault}}' +
```

**5.** Save everything and then restart *esx_menu_dialog*

**How to translate Dialog**<br />
**1.** Go to *esx_menu_dialog/html/js/app.js*<br /> <br />
**2.** Open the app.js and look for line 7 and 8.<br /> <br />
**3.** In the text can you find "Envoyer" and "Annuler", translate it to whatever you want. Should look like this

```javascript
'<button type="button" name="submit">Accept</button>' +
'<button type="button" name="cancel">Cancel</button>' + 
```

## Requirements
esx_menu_dialog<br />
esx_menu_default

## Contact me
Discord: slizzarn#1144
