# Arboresce
(noun)
The state of being arborescent: treelike form or appearance

## What is it?
An interactive fiction editor for writing branching stories that read like a book, not a game.
Interactive choices appear as inline boxes, permitting continued flow of the story. The exported HTML presents as a modifiable, clean, column that presents the entire story at once.

## Using it

Open arboresce.html in any browser.

## Basics
Write in the Opening passage.
Click ＋ Inline choice and type a destination name. If the passage doesn't exist, it's created.
Use the Navigation panel to switch between the passage list (drag the ⋮⋮ handle to reorder), the connection map, and compact connections. (See issues below)
Adjust fonts, paragraph spacing, indent, and theme in the left panel. The Reader preview shows the result live. (See issues below)

## Save and export
Save downloads your project as a .json file. Nothing is stored automatically, so save often.
Open project JSON… loads a saved project.
Export standalone HTML opens a dialog for column width, margins, alignment, theme, and more, then produces a single file readers can open in any browser.

---

Do you remember, from days gone by, of sitting in front of the family computer experiencing Zork for the very first time? What about Infidel? A Mind
Forever Voyaging? Did the loss of Infocom incite visceral feelings? Maybe you have you memory of Infocom foundation they laid, maybe you started later.
Perhaps your first introduction was Blue Lacuna. Did you enjoy using verbs and the inevitable "I beg your pardon?."

Probably not-to all the above.

Infocom has been gone a long time as so to has the regular players of either the original works or the newer ones reminiscent, in all respects. Interactive
fictions, while still around, aren't remotely as possible in that format anymore. After all, even a simple step such as downloading Gargoyle as an interpreter
creates a not so suprising barrier to entry. Yes, people still do download Gargoyle and will go to The Interactive Fiction Database, but most do not. Nowadays,
interactive fictions are more popular on platforms like Itch.io where there is no need for an interpreter or, in some cases, even the need to download anything.
These interactive fictions, built around Twine, have reached an audience that Infocom could never have imagined.

Twine, in this respect, has dropped the barrier to entry, even though it was already low, onto the ground. Unsurprisingly, as more people are exposed to such a
form a content, more will produce their own. This is where the real benefit to Twine is realized. No longer is a knowledge base in coding required to produce a
story, all that is needed is that story. Yes, knowledge of more complex Twine capabilities, and the code to do so, can greatly improve the work, but it is not
necessary.

The influx of works has only served to benefit those who enjoy interactive fiction's, but it has also made, objectively a personal complaint, more prominent-they
are all games. This may seem like a fools errand to point out, they are, by definition, a video game and to some degree I do admit it is quixotic thought to think
they should be otherwise. At times, however, I have found myself thinking that I would prefer if it read more like a book, something that doesn't try to make
the reader the protagonist. Works along these lines do exist, but they are still bound by SugarCube into never feeling quite right. What I wanted was something
that not only read like a book, but felt like one. I didn't want each section presented to me individually with a list of decisions at the bottom.

That is what Arboresce aims to do.

Arboresce, like Twine at the end of the day, is a writing program focusing on branching choices. In reality, the biggest difference is how the final result is
displayed. Perhaps a Twine template that would lead to a similar result exists, but then, once again, it would feel more like a game rather than a book-at least
with respect to writing it.

I believe the best way to understand what Arboresce aims to different than Twine is to actually see an example of what the final output is. You can find an
partial example of what the final .html can look like. The example provided is from a current work in progress, that isn't intended to be an interactive
fiction so some of the narrative may seem to not quite fit, but you can still understand what the program intends to do.

---

The writing side of the program is mostly self-explanatory so I will spare the details but if you do wish to try it all you need is the singular HTML file.
Everything the program needs to run is contained within there so, in reality, if you wanted to use it on a phone you could but I highly discourage trying to
do so. Circling back, however, if you do use the program, as there is no autosave feature, you need to ensure that you use the save project button at the bottom
of the sidebar. This exports a JSON file that contains all the text as well as all the formatting for both the program and exported text theme, though you do
have the option to change more of the exported HTML setting once you actually go to export. Note that the two exports at the top are not to save the project. You
cannot load either of those files to open the project. 

## Issues

- Once a handful of passages are added the default displayed passage list will either be obscenely long or the connection map will start to have connection arrows
overlapping. Best means for currently using the navigation pane is to use the compact connections.
- If text is copy and pasted from another source its original typography will overwrite any typography changes made in the side bar
