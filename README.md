# poisson-disk
## About
This is an implementation of https://www.cct.lsu.edu/~fharhad/ganbatte/siggraph2007/CD2/content/sketches/0250.pdf ,
which generates evenly distributed noise within a circular area.

Requires at least Python 2.7 and the corresponding version of Pygame.

## Usage
To run, execute the following command line:

`python poisson_disk_sample.py [distance]`

Where `[distance]` is the minimum distance between two samples.  The window is considered to be a space from
`(-1, -1)` in the lower left to `(1, 1)` in the upper right.

`Esc` will exit the program and `spacebar` will regenerate the samples.