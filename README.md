# set
Sector's Edge Translations

## Contributing
Don't worry about lengthy commit messages, since what's changed can be clearly seen through pull requests.
Please create issues if you want to discuss what the best translation for a certain phrase is, or ask for more context for certain phrases.

## Format
Each word in each JSON file follows this format:
```json
"Direct":
{
	"translation": "Direkte",
	"machine": true
},
```
"Direct" is the English keyword
"Direkte" is the German translation
"machine" is true if this translation was done by DeepL. **Set this to false when you translate it yourself, so it isn't sent to DeepL for translation again**

## TO-DO
- Add a "hint" variable below "translation" that tells us where+how this phrase is used
- Allow `strings-*.json` files to be placed inside the `AppData/Roaming/vercidium` folder for testing