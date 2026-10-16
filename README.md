# Intro to Python Notes

My notes and practice for Intro to Python. AI suggestions are turned off in this
workspace on purpose, so everything here gets written by hand. Open this folder
in VS Code, not Cursor, so those settings apply.

## Layout

```
python-notes/
  README.md                 this file
  recall-log.md             tracks what I can write cold, and on which days
  scratchpad.py             free play in the console (terminal)
  templates/
    topic-template.ipynb    copy this for every new topic
    experiment-template.ipynb  just experiments: predict, run, explain
  unit-01/                  one folder per unit
    strings.ipynb           one notebook per topic
```

## Starting a new topic

1. Make a folder for the unit if it doesn't exist yet (`unit-02`, `unit-03`...).
2. Copy `templates/topic-template.ipynb` into the unit folder.
3. Rename it after the topic, like `loops.ipynb`.
4. Fill in the title cell and delete the how-to cell.

## Inside each topic notebook

Fill it in top to bottom:

- **Overview:** big idea, key terms, general notes from the lesson.
- **Sections:** one per course example, three cells in this order: title,
  code (run it first with **Shift+Enter**), then notes (What it does, Why it
  works, Output, Notes to self).
- **Experiments:** change the examples, break things, note what happened.
- **Write it cold:** the end of every topic. No scrolling up.

**Extras** at the bottom (Gotcha, Error log, Question): copy them where
needed and delete the ones I don't use.

To copy cells, click the first one, Shift+click the last, press **C**, click
where it should go, and press **V**. The **Outline** panel in the sidebar
jumps to any heading. Shortcuts in a new Markdown cell: `section` + **Tab**
for a title, `notes` + **Tab** for the questions.

## Running code

Click a code cell and press **Shift+Enter**. Output appears below it. If
VS Code asks for a kernel, pick Python 3.

If a variable acts strange, cells may be remembering old values. Click
**Restart** in the notebook toolbar, then run the cells again from the top.

Longer practice programs (input, several steps, a result) go in their own
`.py` file inside the unit folder. Run them with the play button in the
top right.

## Playing in the console

`scratchpad.py` is for messing around. Run it with the play button and the
output shows in the terminal. For instant one-liners, type `python3` in the
terminal to open the interactive console (like the browser console in
JavaScript). Type `exit()` to leave.

## The rule

A concept only counts as learned when I can write it from memory, with no
notes, on three different days. Log it in `recall-log.md`.
