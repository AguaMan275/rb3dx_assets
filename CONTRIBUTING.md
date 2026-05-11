# Contributing Guidelines
Anyone is free to add models, but please keep a few things in mind.  
We are still in the very beginning of custom models in Rock Band 3 and things are evolving rapidly.  
Current documentation is available on [[Google Docs]](https://docs.google.com/document/d/16hRGfKVZlf0QR6v0r4YlS0LUob0jrQWG7t24oGc2jSc/edit?usp=sharing).

Here are dos and don'ts:
* Do test your models on at least one system before submitting.
* Add the character to the [[Locale file]](dx/locale/dx_locale_updates_chars.dta).
	* It's suggested to copy the previous line because you need to keep the invisible "zero width joiner" character to not break sorting.
	* There's an approx. limit of around 23 characters. If you go over, it will get cut off.
* **DO NOT** use any uppercase in the filenames, especially in `.milo` files. Your file will either not load or cause issues (thumbnails not working).
* **DO NOT** change the `prefab_name` file if possible.
	* If users have the characters saved into their band, **it will cause a broken save** as the game won't be able to find the file anymore!
* Do try to communicate with others if you have issues or suggestions, whether it's through here or through the [[MiloHax Discord]](https://discord.gg/milohax).