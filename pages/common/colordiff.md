# colordiff

> A tool to colorize diff diff output.
> The Perl script colordiff is a wrapper for `diff` and produces the same output but with pretty 'syntax' highlighting. Colour schemes can be customized..
> More information: <https://github.com/kimmel/colordiff>.

- Compare files:

`colordiff {{file-1}} {{file-2}}`

- Compare files, output in two columns:

`colordiff -y {{file-1}} {{file-2}}`

- Compare files, Ignore case differences in file contents:

`colordiff -i {{file-1}} {{file-2}}`

- Compare files,  Report when two files are the same:

`colordiff -s {{file-1}} {{file-2}}`

- Compare files, ignoring white spaces:

`colordiff -w {{old_file}} {{new_file}}`