<p align="center">
<img src="https://img.shields.io/github/commit-activity/m/rahriver/Noter">
<a href="https://github.com/rahriver/Noter/graphs/contributors"><img src="https://img.shields.io/github/contributors/rahriver/Noter"></a>
<img src="https://img.shields.io/github/v/release/rahriver/Noter">
</p>

# Noter: Library For Your Notes!
> This script gives you the ability to handle notes in the command-line.

![Preview](https://user-images.githubusercontent.com/89016694/193405492-5e96b0fd-53ca-4c21-9173-e1f33a658810.png)

# Dependencies
- [fzf](https://github.com/junegunn/fzf)
- [bat](https://github.com/sharkdp/bat)

# Installation
**Linux**
Move the Library script to your `~/.local/bin` folder or anywhere that's in your `$PATH`.

# Usage
The template folder is consist of 4 templates for:
- **Basic** Markdown Note
- **LaTeX** Template (Should Be Compiled With XeLaTeX)
- **R Markdown** (For Data Science & Programming Notes)
- **Presentation** (With Beamer)

You should change these options for your own use:
- **EXTENSION**: (Your suitable note extension)
- **NOTES_DIR**: (Your note directory)
- **EDITOR**: (Your prefered text editor to open notes)

When you run the script, it gives you these options:
- Create a new note
  - Initially it checks for your note directory, it will create a dir if it's not specified.
- View a note (Using FZF, Preview With BAT)
- Delete a note (Using FZF To Select)
- Exit
