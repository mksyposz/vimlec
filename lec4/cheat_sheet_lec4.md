Vertical movements
---

|Command                         |Key binding     |
|--------------------------------|----------------|
|go to the top                   |`gg`            |
|go to the end                   |`G`             |
|go to line X                    |`:X` / `XG`     |
|relative movement               |`number+h/j/k/l`|
|jump to empty line below        |`}`             |
|jump to empty line above        |`{`             |
|go up half page                 |`ctrl+u`        |
|go down half page               |`ctrl+d`        |
|go to matching "thing"          |`%`             | 
|delete word                     |`diw`           |
|delete inside braces            |`di(/[/{`       |
|delete paragraph                |`dip`           |
|delete inside braces with braces|`da(/[/{`       |
|repeat previous command         |`.`             |

paragraph - code in between 2 empty lines.
Vim can REPEAT some commands.
{number} + command
half page - you just need to count lines on single page and divide them by 2.
matching "thing" -> for example braces. Vimtex says that begin{env} end{env}\
is a "thing".
Fun delete stuff works also with yank, change and visual.
