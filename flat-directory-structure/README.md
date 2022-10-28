# Flat Directory Structure

If you glance at the source code of this content you will notice that
these sections are organized into a single, flat directory structure.
This presents several advantages for writing and maintaining the
knowledge source (aka words) contained therein.

*Browsing from GitHub `README.md` files does not break link navigation.*
One of the most annoying parts of GitHub `README.md` file rendering (and
I'm not talking about the GitHub Pages stuff) is that relative links
simply do not work at all. Having a flat directory structure allows
adding an initial slash to the links ensuring that they all work no
matter where the user encounters them in the content. This also allows a
quick browser search from the root repo view for a keyword contained
within any of the titles (without the need to create an additional
manifest or table of contents until the final version is rendered).
