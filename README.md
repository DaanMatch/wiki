# Wiki

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)]( https://daanmatch.github.io/wiki/)

![build](https://github.com/DaanMatch/wiki/workflows/deploy/badge.svg?branch=master)

## Updating Instructions

For those wishing to add their agendas to this Jupyter Book:

- Please upload content as `.md` files or `.ipynb` files to the wiki directory.
- Add files to the Table of Contents in the meetings/_toc.yml file.
- Include any dependencies to the requirements.txt file.
- The book will be rebuilt and deployed automatically.

## Developer Usage

### Building the book

If you'd like to develop and/or build the My Book book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `meetings/` directory
4. Run `jupyter-book clean wiki/` to remove any existing builds
5. Run `jupyter-book build wiki/`

## Contributors

We welcome and recognize all contributions.

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
