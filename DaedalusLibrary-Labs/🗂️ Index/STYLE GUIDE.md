---
title: "STYLE GUIDE"
created: 2023-11-11
# edited:

---


## Ymal Headers

#### Example
```ymal
---
title: "Title as str"
created: yyyy-mm-dd # this does not change

# edited: yyyy-mm-dd # if needed, shows the last edit

tags: camelCase

# Other
variable_name: camelCase
---
```

- Dates
	- yyyy-mm-dd format
- Category
	- "index"
		- this is something that stays in the root directory
	- "blog"
		- an article of my own creation and contains my ideas on a particular subject.
	- "*plug-in name*"
		- This is a file containing a plug in such as annotator, data view, or kanban board. The name of the plug in.
- Tags
	- camelCase
- General rules for other data
	- varable_name (snake_case)
		- strings (camelCase) # add variable type
		- bool # bool
		- num # int
		- float # float

## Folders

All Folders will have an emoji and then a capitalized one to two word description. Only use two words when it is a title of a project or a plug in. If it is an abbreviation use emoji and all CAPS.

## Files

- Files in all CAPS are live documents which will exist in the folder that they are most applicable.  
- Any other files are capitalized
- No emojis in file names