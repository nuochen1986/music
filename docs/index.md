
# Welcome to MkDocs
For full documentation visit [mkdocs.org](https://www.mkdocs.org).

updated:
> - [2022-04-15]: created the docs
> 

[TOC]

## Maxwell's Equations

Meep simulates [Maxwell's equations](https://en.wikipedia.org/wiki/Maxwell's_equations), which describe the interactions of electric ($\mathbf{E}$) and magnetic ($\mathbf{H}$) fields with one another and with matter and sources. In particular, the equations for the time evolution of the fields are:

$$\displaystyle\tag{1}
\frac{d\mathbf{B}}{dt} = -\nabla\times\mathbf{E} - \mathbf{J}_B - \sigma_B \mathbf{B}
$$

$$\displaystyle\tag{2}
\mathbf{B} = \mu \mathbf{H}
$$

$$\displaystyle\tag{3}
\frac{d\mathbf{D}}{dt} = \nabla\times\mathbf{H} - \mathbf{J} - \sigma_D \mathbf{D}
$$

$$\displaystyle\tag{4}
\mathbf{D} = \varepsilon \mathbf{E}
$$

## Commands

* `mkdocs new [dir-name]` - Create a new project.[^1]
* `mkdocs serve` - Start the live-reloading docs server.[^2]
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
- insert mathjax equations $\phi$
$$
\displaystyle\tag{5}
E=mc^2
$$
- 
## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## code example
this is an example of code highlight
```py linenums="1" title="read_and_write_csv.py" 
import numpy as np
import csv
import os

x = np.arange(12).reshape(3,4)

with open("test.csv","w",newline='') as f:
    fw = csv.writer(f,delimiter=',')
    fw.writerow(["#comment"])
    for row in x:
        fw.writerow(row)
```
## table example

| Method      | Description     |
| ----------- | --------------- |
| `GET`       | Fetch resource  |
| `PUT`       | Update resource |
| `DELETE`    | Delete resource |


[^1]: 
    This is a note
[^2]: 
    This is a note

