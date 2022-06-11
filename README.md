# elfedit
elfedit lets you easily edit an .ELF file's program and section headers with valid segments.

## Features
It being a tool for personal use, I don't intend this to be feature heavy:
* 64-bit ELF programs only.
* Dump an .ELF file's program and section headers to .JSON.
* Edit an .ELF file's program and section headers from .JSON.
* Custom program/section headers with valid segments.

It's coded in mind for an .ELF that targets CBEA (Cell Broadband Engine Architecture), but should work with any other 64-bit target.

## Motivation
objcopy and other tools to add/edit sections couldn't produce valid segments. And I found linker scripts too involved for what should be a simple edit.
