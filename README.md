# Python nose2 unittesting example
This is an example package setup for having unittests in a separate folder from the actual package.

Run the unittests from the top folder with `PYTHONPATH=. nose2` if you haven't installed this package in your pythonpath anywhere (through virtualenv or side wide).

Note now I modify the PYTHONPATH environment variable to tell nose2 where to find the package. I also use relative imports inside my package to make sure all modules can be found.
