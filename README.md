# divio-docs
Divio User handbook
Published version: Divio user handbook.

This documentation is intended for Divio customers.

Build the documentation locally
You'll need the enchant library, used by pyenchant for spelling.

Install with brew install enchant (macOS) or the appropriate command for your system.

Then:

git clone git@github.com:divio/divio-docs.git  # clone
cd divio-docs
make install  # create a virtualenv and install required components
make run  # build and serve the documentation
open http://localhost:8001  # open it in a browser
Notable techniques used in this documentation
Read the Docs
We serve our documentation via Read the Docs, a superb free service that's especially well-known in the Python world, and is ideal for open-source projects.

The documentation is written in ReStructed Text (RST) and built using Sphinx.
