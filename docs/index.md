# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Code Sample 

### Sample 1 
`Python` program that contains line numbers from 1
``` py linenums="1"
print()
print("Hello World")
print()
```

### Sample 2
`Python` program that contains a function
``` py linenums="1"
def display(words):
    print(words)
```

### Sample 3
`Python` program that contains the **highlights** of the *1st* line
``` py hl_lines="1"
# display function
display("Hello World")
```