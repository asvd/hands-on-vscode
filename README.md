**Hands-on**
============

**Hands-on** is a Keymap extension for Visual Studio Code that aims at *dramatical increase of coding experience* by keeping your hands in typing position at all times, even during navigation. This is an extended port of [hands-on for atom](https://atom.io/packages/hands-on).

**Hands-on** puts navigation and control keys under the right hand, where it is naturally located when typing. This way navigation actions would not alter hand position, and you can proceed with typing immediately.

**Hands-on** mode is activated by holding left <kbd>**Alt**</kbd> key (<kbd>**Command**</kbd> on Mac). When the mode is active, some of the letter key act as navigation keys:


| key | action|
|-|-|
| **Home row** | **essential navigation** |
| <kbd>**Alt**</kbd> <kbd>**J**</kbd> | move left one character |
| <kbd>**Alt**</kbd> <kbd>**K**</kbd> | move down |
| <kbd>**Alt**</kbd> <kbd>**L**</kbd> | move up |
| <kbd>**Alt**</kbd> <kbd>**:**</kbd> | move right |
| **Lower row** | **works on bigger distance** |
| <kbd>**Alt**</kbd> <kbd>**M**</kbd> | move to the line start <kbd>**Home**</kbd> (first non-whitespace character of a wrapped part of the line) |
| <kbd>**Alt**</kbd> <kbd>**,**</kbd> | page down |
| <kbd>**Alt**</kbd> <kbd>**.**</kbd> | page up |
| <kbd>**Alt**</kbd> <kbd>**/**</kbd> | move to the line end <kbd>**End**</kbd> (last non-whitespace character of a wrapped part of the line) |
| **Adding** <kbd>**Ctrl**</kbd> | **increases impact** |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**J**</kbd> | move left one word |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**K**</kbd> | move down 5 lines |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**L**</kbd> | move up 5 lines |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**:**</kbd> | move right one word |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**M**</kbd> | move to the (whole) line start |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**,**</kbd> | move to the file start |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**.**</kbd> | move to the file end |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**/**</kbd> | move to the (whole) line end |
| **Adding** <kbd>**Shift**</kbd> | **also performs selection** |
| ... | ...for example... |
| <kbd>**Alt**</kbd> <kbd>**Shift**</kbd> <kbd>**J**</kbd> | select one character to the left |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**Shift**</kbd> <kbd>**L**</kbd> | select 5 lines above |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**Shift**</kbd> <kbd>**.**</kbd> | select everything from here to the end of file |
| ... | ...and so on... |
| **Top row** | **performs scrolling** |
| <kbd>**Alt**</kbd> <kbd>**I**</kbd> | scroll down |
| <kbd>**Alt**</kbd> <kbd>**O**</kbd> | scroll up |
| <kbd>**Alt**</kbd> <kbd>**Ctrl**</kbd> <kbd>**I**</kbd> | scroll down stronger |
| <kbd>**Alt**</kbd> <kbd>**Ctrl**</kbd> <kbd>**O**</kbd> | scroll up stronger |
| **Useful extras** ||
| <kbd>**Alt**</kbd> <kbd>**'**</kbd> | type newline <kbd>**Enter**</kbd>|
| <kbd>**Alt**</kbd> <kbd>**[**</kbd> | erase to the left <kbd>**Backspace**</kbd>|
| <kbd>**Alt**</kbd> <kbd>**]**</kbd> | erase to the right <kbd>**Delete**</kbd>|
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**[**</kbd> | erase word to the left |
| <kbd>**Ctrl**</kbd> <kbd>**Alt**</kbd> <kbd>**]**</kbd> | erase word to the right |
| **Using** <kbd>**Meta**</kbd> **(**<kbd>**Command**</kbd> **on Mac,** <kbd>**Win**</kbd>+<kbd>**Alt**</kbd> **on Windows)** | **performs group navigation** |
| <kbd>**Meta**</kbd> <kbd>**J**</kbd> | switch to the group on the left |
| <kbd>**Meta**</kbd> <kbd>**K**</kbd> | switch to the group below |
| <kbd>**Meta**</kbd> <kbd>**L**</kbd> | switch to the group above |
| <kbd>**Meta**</kbd> <kbd>**:**</kbd> | switch to the group on the right |
| <kbd>**Meta**</kbd> <kbd>**U**</kbd> | decrease group width |
| <kbd>**Meta**</kbd> <kbd>**I**</kbd> | decrease group height |
| <kbd>**Meta**</kbd> <kbd>**O**</kbd> | increase group height |
| <kbd>**Meta**</kbd> <kbd>**P**</kbd> | increase group width |

> **note**: <kbd>**Meta**</kbd> stands for <kbd>**Win**</kbd>+<kbd>**Alt**</kbd> on Windows (not just <kbd>**Win**</kbd>) in order to avoid conflicts with sytem hotkeys

> **note**: there is no additional keybinding to split or close group provided by **hands-on**, because it is available in Visual Studio Code by combinations like <kbd>**Ctrl**</kbd> <kbd>**/**</kbd> and  <kbd>**Ctrl**</kbd> <kbd>**W**</kbd>

**Hands-on** is layout-agnostic, meaning that it is tied to keycodes, and always resides in the same place under your right hand, even if you use [Dvorak for Programmers](https://github.com/asvd/programmer-dvorak-eu). For example, in German layout the key to press for moving to the end of the line would be <kbd>**Alt**</kbd> <kbd>**-**</kbd>, instead of <kbd>**Alt**</kbd> <kbd>**/**</kbd> for US layout (but physical position of the key is intact).


---

I am from the world of [emacs](https://www.gnu.org/software/emacs/), the main feature I have been missing so far was the opportunity to navigate without moving my hands away from their normal position (and therefore avoid briefly looking at the keyboard when puting them back in order to properly position).

Base navigation line layout <kbd>←</kbd> <kbd>↓</kbd> <kbd>↑</kbd> <kbd>→</kbd> was inspired by [vim](https://www.vim.org/). Main navigation keys moved one position to the right eventually (in vim it starts with the <kbd>**H**</kbd> key), which is more natural position of the right hand.

---

https://asvd.github.io

https://twitter.com/asvd0