# Alfred Bible.com
A alfred 3 workflow for searching bible verse from bible.com.

This workflow provide a easy way to search bible verse on bible.com, it's written in Ruby.

## Usage
1. The default trigger keyword is 'bible', and the format is 'keyword book verse'.
2. Type 'bible book' to see a book from ch 1. (e.g. 'bible 約翰福音')
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/a_book.png)
3. Search a chapter in a book. (e.g. 'bible 約翰福音 3')
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/a_chapter.png)
4. Search a verse in a book. (e.g. 'bible 約翰福音 3:16')
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/a_verse.png)
5. Search a range of verses in a book. (e.g. 'bible 約翰福音 3:14-18')
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/verse_range.png)

## Installation
Download/clone this project and double click the workflow file to install.

## Setting
1. Before Using this workflow, you must edit the variables of Bible_tools module in scriptfilter for language setting.
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/variables_setting.jpg)
	- For setting bible version, please see what's the version index of your favorite version on [bible.com](http://bible.com).
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/bible_version_idx.jpg)
2. I recommend disable 'shift' key to preview beaucse some input methods use 'shift' key to switch languages.
	![](https://raw.github.com/yea107/alfred-bible-com/master/screenshots/change_shift_setting.jpg)