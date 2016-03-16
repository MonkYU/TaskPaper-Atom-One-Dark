# Atom One Dark for TaskPaper 3

A dark theme for [TaskPaper 3](http://taskpaper.com) heavily inspired on (stolen from) [Atom One Dark Syntax](https://github.com/atom/one-dark-syntax).
A few more details can be found in the [forum](http://support.hogbaysoftware.com/t/theme-dark-theme-based-on-atom-one-dark-syntax/1297).

![](https://raw.githubusercontent.com/pslobo/TaskPaper-Atom-One-Dark/master/Preview.png)

## Features

- Green for items tagged @today or @active
- Cyan for items tagged @next
- Red for items tagged @flag  or @high or @prio
- Faded blue for items tagged @waiting
- Selection is a subtle tint color which allows for easy reading of all text

## Other features

- Done tasks are dimmed so as not to distract from what needs to be done
- Done tasks also mutes all other colours that may have been applied from previous tags
- Notes are also dimmed in relation to tasks.
- Tags are always dimmed in relation to task text.
- Saved searches are a more subdued tone as not to distract from main list

## TODO

- Still some tweaks needed, such as the dash
- More stuff...
- Fix bugs too.

## FORK CHANGES

- renamed the deprecated **user.less** filename to new **theme.less**
- updated the handle tints to be in line with TP3 release style of tinting dim when not collapsed. Made even dimmer than original tint to be as distinct as possible from collapsed handles, yet still visible.
- borrowed the cleaner handle idea from [theme-notes-first](https://github.com/pascallaliberte/theme-notes-first) to make them invisible when there are no sub-tasks or sub-notes.

## Installation

Backup then replace the **theme.less** file located at:

  ~/Application Support/TaskPaper/

> NOTE: You can easily get to this folder location from the TaskPaper File menu > Open Application Folder.
