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
	"translation": "Bloklar",
	"machine": true
},
```
- `phrase` - English keyword
- `context` - A more specific keyword. If this field is present, please translate this rather than `phrase`
- `comment` - An explanation of the phrase, or an example of the single word in a sentence. Some comments start with `[Settings] [Button]`, which are attributes you can use to search through the file faster
- `translation` - The translation of `context`. If `context` is missing, this is the translation of `phrase`
- `machine` - This is set to true if this translation was done by DeepL. **Delete this line when you translate the phrase, so that DeepL doesn't overwrite it**
