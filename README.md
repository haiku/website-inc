# Haiku Inc. website

This repository contains the source code for the website for
[Haiku, Inc.](https://www.haiku-inc.org/about/), the non-profit
organization registered in New York that supports the development
of the Haiku operating system.

## How to test locally

This site uses Hugo to generate the site from a theme and Markdown files.

Please install Hugo either from [its website](https://gohugo.io/) or using a
package manager.

Unfortunately due to the state of the Go port in Haiku, it is unlikely that recent
versions of Hugo can be used there. But otherwise Hugo can be used on most other
operating systems.

Once Hugo is installed, run the following command within this repo:

    hugo server -D

This will run the local Hugo server and include any drafts (`-D` does this) and
usually it can be found on http://localhost:1313.

Any changes made should be picked up by the server.