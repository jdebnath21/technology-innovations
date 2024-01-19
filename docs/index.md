# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).


## Code Annotation Examples

### Interesting Code Blocks

Some `code` goes here

### Plain Code Block

```
Random Code
def basefunction()
// Comments
```

### Code in specific language

Some Python Code with `py`

``` py
import tensorflow as tf
def whatever()
```

#### With some title example

``` py title="bubblesort.py", linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 -i):
            if items[j] == items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]

```

#### Highlight specific lines

``` py title="bubblesort.py", linenums="1", hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 -i):
            if items[j] == items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]

```

<!-- ## Icons and Emojis

:smile: <br>
:fontawesome-regular-face-laugh-wink: -->



<!-- ## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->
