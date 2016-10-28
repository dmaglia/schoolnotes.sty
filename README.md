# schoolnotes.sty
A Latex Package optimized for schoolnotes. It provides a number of package for math operations and a clean typography out of the box. In addition there a some [commnads](#commands) to simplify reference in a latex document.


# Commands
| Command            | Output                      |
|--------------------|-----------------------------|
| `\tabref{tab:1}`   | (siehe Tab. 12.4)           |
| `\tableref{tab:1}` | (siehe Tab. 12.4, Seite 5)  |
| `\tref{tab:1}`     | (siehe 3.4)                 |
| `\treft{tab:1}`    | Abschnitt 3.4               |
| `\textref{label}`  | (siehe 3.4, Seite 12)       |
| `\fref{fig:1}`     | (siehe Abb. 10.4)           |
| `\figref{fig:1}`   | (siehe Abb. 10.4, Seite 12) |
| `\figreftt{fig:1}` | Abbildung 10.4              |
| `\seepage{label}`  | (siehe Seite 12)            |


## `\frontmatter`
Changes the Pagenumbering to **Roman** and the pagestyle to **plain**. Should be used for the first pages with the table of contents, list of figures etc. **If you use `\frontmatter` you have to use `\mainmatter` as well.**

## `\mainmatter`
Changes the Pagenumbering to **arabic**, resets the page counter to 1 and changes the pagestyle to **maincontentstyle**.

# Shortcuts
| Shortcut | Original | Purpose                           |
| ---------|----------|-----------------------------------|
| `\m`     | `\cdot`  | Simplify writing of math formulas |

# Contribution Guide
coming soon
