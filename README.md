# Jinja Bash Sublime

Crude syntax highlighting in Sublime Text 3 for your jinja2-templated shell
scripts!


## Installation Instructions
Sublime bundles some default language syntax files up into zip files, which
are renamed with the `.sublime-package` extension.

1. First, find where the shell script package is on your system, and unzip
them to a new folder. On macOS:

```
$ cd /Applications/Sublime Text.app/Contents/MacOS/Packages/
$ unzip ShellScript.sublime-package -d shellscript
$ cd shellscript
```

You should see a file called `Shell-Unix-Generic.sublime-syntax`.

2. Then, go to the command palette (<kbd>⌘</kbd><kbd>Shift</kbd><kbd>P</kbd>)
and search for `Browse Packages`. Open that folder and drop j2sh.sublime-syntax
inside.

3. You're done!
