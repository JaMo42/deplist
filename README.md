# deplist

A C/C++ dependency listing tool.

## Usage

`deplist <target> [<dir>]`

Lists all C/C++ files in `<dir>` that include `<target>`. If `<dir>` is omitted
the current directory is used.

Additional include directories can be given using `-I<dir>`, these will be used
to match the file names in the include directives to the target.
