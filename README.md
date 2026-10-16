# Intro to Python Notes

My notes and practice for Intro to Python. AI suggestions are turned off in this
workspace on purpose, so everything here gets written by hand. Open this folder
in VS Code, not Cursor, so those settings apply.

## Layout

```
python-notes/
  README.md                 this file
  recall-log.md             tracks what I can write cold, and on which days
  templates/
    topic-template.ipynb    copy this for every new topic
  unit-01/                  one folder per unit
    strings.ipynb           one notebook per topic
```

## Starting a new topic

1. Make a folder for the unit if it doesn't exist yet (`unit-02`, `unit-03`...).
2. Copy `templates/topic-template.ipynb` into the unit folder.
3. Rename it after the topic, like `loops.ipynb`.
4. Fill in the title cell and delete the how-to cell.

## Inside each topic notebook

**Section blocks:** one per course example. The Markdown cell holds the notes
(what it does, why it works, output, notes to self). The code cell under it
holds the course code with `#` comments on the important pieces.

To add a section, select the notes cell and the code cell (click, then
Shift+click), press **C** to copy, click the last cell, and press **V** to
paste. Or type `section` in a new Markdown cell and press **Tab**.

**Experiments:** practice space. Change the examples, write my own versions,
break things on purpose, and note what happened.

**Write it cold:** the end of every topic. No scrolling up.

## Running code

Click a code cell and press **Shift+Enter**. Output appears below it. If
VS Code asks for a kernel, pick Python 3.

If a variable acts strange, cells may be remembering old values. Click
**Restart** in the notebook toolbar, then run the cells again from the top.

Longer practice programs (input, several steps, a result) go in their own
`.py` file inside the unit folder. Run them with the play button in the
top right.

## The rule

A concept only counts as learned when I can write it from memory, with no
notes, on three different days. Log it in `recall-log.md`.
