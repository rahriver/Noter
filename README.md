# Noter: Library For Your Notes!
> This script gives you the ability to handle notes in the command-line.

![Preview](https://user-images.githubusercontent.com/89016694/193405492-5e96b0fd-53ca-4c21-9173-e1f33a658810.png)

# Dependencies
- bat
- fzf

# Installation
---
## Linux
Move the Library script to your `~/.local/bin` folder or anywhere that's in your `$PATH`.

# Usage
---
The template folder is consist of 4 templates for:
- Basic Markdown Note
- LaTeX Template (Should Be Compiled With XeLaTeX)
- R Markdown (For Data Science & Programming Notes)
- Presentation (With Beamer)

When you run the script, it gives you these options:
- Create a new note
  - Initially it checks for your note directory, it will create a dir if it's not specified.
- View a note (Using FZF, Preview With BAT)
- Delete a note (Using FZF To Select)
- Exit
