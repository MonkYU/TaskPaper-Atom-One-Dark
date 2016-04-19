# Atom One Dark 2 for TaskPaper 3

A dark theme for [TaskPaper 3](http://taskpaper.com) heavily inspired by @pslobo's excellent adaptation of (stolen from) [Atom One Dark Syntax](https://github.com/atom/one-dark-syntax).

![](https://raw.githubusercontent.com/jasonshanks/TaskPaper-Atom-One-Dark/master/Preview.png)

## Colours/Colors

- Fountain Blue for items tagged @next
- Malibu Blue for URLs and Projects (gradually faded at each level)
- Soft Purple for items tagged @waiting
- Pistachio Green for items tagged @today, @active or @now (this is especially useful in conjunction with [this great script](http://support.hogbaysoftware.com/t/script-displaying-the-active-task-in-the-os-x-menu-bar/1290) by @complexpoint)
- Froly Red for items tagged @due
- Sunset Red for items tagged @flag, @high, @hot, @priority(high) or @prio(1)
- Whisky Orange for vanilla tags
- Faded Chalky Orange for context tags
- Selection is a subtle mix of fore/background colors same as original One Dark Atom theme

## Other Style Features

- Done tasks are dimmed so as not to distract from what needs to be done
- Done tasks also mutes all other colours that may have been applied from previous tags
- Notes are dimmed, non-italiced and slightly smaller in relation to tasks.
- Tags are always dimmed in relation to task text.
- Saved searches are a very subdued tone so as not to distract from the main list
- Guide lines and item handles are slim, subdued and tinted a faded Malibu blue.
- Paragraph spacing before and after Project titles is enhanced for clean separation.

## Installation

Backup then replace the **theme.less** file located at:

  ~/Application Support/TaskPaper/

> NOTE: You can easily get to this folder location from the TaskPaper File menu > **Open Application Folder**.

## TODO

- continue to update as TaskPaper theme styles change or expand
- style the Sidebar if this becomes possible (white is really jarring against a dark theme, so I recommend hiding it and the Toolbar most of the time).
- add subtle variation to Priority levels
- add distinction between due and overdue?

## RELEASE NOTES

2016-03-17:

- forked from @pslobo's excellent code heist!
- renamed the deprecated **user.less** filename to new **theme.less**
- updated the handle tints to be in line with TP3 release style of tinting dim when not collapsed.
- borrowed the cleaner handle idea from [theme-notes-first](https://github.com/pascallaliberte/theme-notes-first) to make them invisible when there are no sub-tasks or sub-notes. [UPDATE: now a TP3 default style!]

2016-04-20:

- added new theme possibilities from 3.1 and 3.2
  - item-handle-size, guide-line width, paragraph-spacing-before(after)
  - updated deprecated ```display``` label to ```content```
- reintegrated additional Atom One Dark styles of syntax-saturation, syntax-brightness, mono-2
- swapped Project and Tag colors (not a fan of Orange, but true to Atom One Dark it is heavily used as a function or value color.)
- changed tint of guides and invisibles to malibu blue.
- found content uses for 2 unused colours.
- swapped a few other colours around to my personal preference.
- de-italiced and reduced font size of notes (slightly OmniFocus-like)
- further reduced fade of Search tag lines.
- Enlarged top Project title font size
- Expanded Project styles to 4 levels with gradually reducing color fade and type size.
- Added additional tag names to related functions (active, now, hot, priority, due)
