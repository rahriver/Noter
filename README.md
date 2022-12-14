![Logo](https://user-images.githubusercontent.com/89016694/193409622-6c8cf774-0980-4497-93f7-5cf2ee1334ec.png)
<p align="center">
<a href="https://github.com/rahriver/Noter/master/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=flat&label=License&message=MIT&logoColor=eceff4&logo=github&colorA=black&colorB=green"/></a>
<img src="https://img.shields.io/github/commit-activity/m/rahriver/Noter">
<a href="https://github.com/rahriver/Noter/graphs/contributors"><img src="https://img.shields.io/github/contributors/rahriver/Noter"></a>
<img src="https://img.shields.io/github/v/release/rahriver/Noter">
</p>

# Noter: Library For Your Notes!
> Manager notes in the command-line.

![image](https://user-images.githubusercontent.com/89016694/194278194-3255fa5a-0d9d-4f88-aecf-401b9c838552.png)

## Dependencies
Install these programs before running the script:
- [fzf](https://github.com/junegunn/fzf)
- [bat](https://github.com/sharkdp/bat)

## Installation
### Linux
Move the Library script to your `~/.local/bin` folder or anywhere that's in your `$PATH`.

## Usage
The template folder is consist of 4 templates for:
- **Basic** Markdown Note
- **LaTeX** Template (Should Be Compiled With XeLaTeX)
- **R Markdown** (For Data Science & Programming Notes)
- **Presentation** (With Beamer)

You should change these options for your own use:
- **EXTENSION**: (Your suitable note extension)
- **NOTES_DIR**: (Your note directory)
- **EDITOR**: (Your preferred text editor to open notes)

When you run the script, it gives you these options:
- Create a new note
  - Initially it checks for your note directory, it will create a dir if it's not specified.
- View a note (Using FZF, Preview With BAT)
- Delete a note (Using FZF To Select)
- Exit

To invoke just the View Note option, you can pass the `view` argument when running the script:

`noter view`

## Support
> Give this repository a star and share it with someone who cares about these stuff :O
