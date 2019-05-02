# Pictures

**Menu**<br />
<br />
<br />
           ![alt text](https://i.gyazo.com/cc2cd034b7320437cc28fdb7c5d9b9a2.png)


**Dialog**<br />
![alt text](https://i.gyazo.com/bbd10ce9f0bcf1e975576fe0e6da3a2f.png)

# Installation
**How to install the menu**<br />
**1.** Go to *esx_menu_default/html/css/app.css*<br /> <br />
**2.** Replace everything inside the *app.css* with everything from the menu file above.<br /> <br />
**3.** Save it and then restart *esx_menu_default*

**How to install the dialog**<br />
**1.** Go to *esx_menu_dialog/html/css/app.css*<br /> <br />
**2.** Replace everything inside the *app.css* with everything from the dialog file above.<br /> <br />
**3.** Go to *esx_menu_dialog/html/js/app.js*, replace line 3 to line 12 with this:<br /> <br />

```javascript
	let MenuTpl =
		'<div id="menu_{{_namespace}}_{{_name}}" class="dialog {{#isBig}}big{{/isBig}}">' +
			'{{#isDefault}}<input type="text" name="value" placeholder="{{title}}" id="inputText"/>{{/isDefault}}' +
				'{{#isBig}}<textarea name="value"/>{{/isBig}}' +
				'<button type="button" name="submit">Accept</button>' +
				'<button type="button" name="cancel">Cancel</button>'
			'</div>' +
		'</div>'
	;
```

**5.** Save everything and then restart *esx_menu_dialog*

**How to translate the dialog**<br />
**1.** Go to *esx_menu_dialog/html/js/app.js*<br /> <br />
**2.** Open the app.js and look for line 7 and 8.<br /> <br />
**3.** In the text can you find "Accept" and "Cancel", translate it to whatever you want. Should look like this

```javascript
'<button type="button" name="submit">Accept</button>' +
'<button type="button" name="cancel">Cancel</button>' + 
```

## Requirements
esx_menu_dialog<br />
esx_menu_default

## Contact me
Discord: slizzarn#1144
