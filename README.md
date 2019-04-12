# Simple Docker Security

**Simple Docker Security** is a Bash script that extracts relevant security information from Docker instances, images and containers, such as:

- Multiple basic details about the main host operating system
- Images' inspect and history output
- Containers' inspect output and few specific commands outputs
- Networks' inspect and `ps` output

It is not meant to execute automatic analysis, but rather provide a dump of useful information that can then be manually (or automatically) analysed. In the future some automated checks might be included.


## Usage

To use Simple Docker Security, run it with "sudo" on the main Docker host that you want to analyse. For this release, there are no available options.


## Copyright

Copyright (c) 2019 Giovanni Cattani

**Simple Docker Security** is released under [The MIT License](http://www.opensource.org/licenses/mit-license.php).
