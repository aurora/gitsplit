# gitsplit

## Description

This tool is used to split parts of a repository into a new repository.
The tool must be executed inside the source repository, but does not
modify the source repository (make sure to read the disclaimer). The
tool tries to determine file renames and keep history across renames
accordingly.

This tool seems to work quite well for my own purpose, but it's not
garanteed to work for others as well.

## Usage

```
usage: gitsplit branch dst [keep [keep ...]]

DESCRIPTION
    This tool is used to split parts of a repository into a new
    repository. The tool must be executed inside the source re-
    pository. The specified destination path cannot be a sub-
    directory of the source repository.

ARGUMENTS
    branch    The source branch to split from.

    dst       The destination path for the repository to create
              This path must not exist.

    keep      One path or multiple paths to keep in the new repository,
              if no paths are specified the entire source branch is
              splitted into a new repository.
```

## Disclaimer

Use with caution. This software may contain serious bugs. I can not be
made responsible for any damage the software may cause to your system
or files. Make sure to backup your source repository before using this
tool.

## License

gitsplit

Copyright (C) 2018-present by Harald Lapp <harald@octris.org>

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.

