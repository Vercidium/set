# set
Sector's Edge Translations

## Contributing
Don't worry about lengthy commit messages, we can see what's changed through pull requests.
Please create issues if you want to discuss what the best translation for a certain phrase is, or ask for more context for certain phrases.

## Format
Each word in each JSON file follows this format:
```json
{
	"phrase": "Blocks",
	"context": "Cubes",
	"comment": "A 3d voxel",
	"locations": [],
	"translation": "Bloklar",
	"machine": true
},
```
- `phrase` - English keyword
- `context` - A more specific keyword, which is sent to DeepL instead of `phrase`
- `comment` - An explanation of the phrase, or an example of the single word in a sentence. Some comments start with `[Settings] [Button]`, which are attributes you can use to search through the file faster
- `locations` is unused
- `translation` is the translated word
- `machine` is true if this translation was done by DeepL. **Set this to false when you translate it yourself, so it isn't overwritten by DeepL**

## TO-DO
- Allow `strings.json` files to be placed inside the `AppData/Roaming/vercidium` folder for testing
- Add a keybind in-game that toggles translations on and off for quick testing
