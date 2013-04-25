# About #

This is a very basic [TextMate](https://github.com/textmate/textmate) bundle
for [Natural Docs](http://www.naturaldocs.org). At the moment this bundle
contains exactly one command which will generate documentation for your
current project in the sub-directory `ND_OUTPUT_DIRECTORY` (default value:
`Documentation`).

![Natural Docs Output in TextMate](https://raw.github.com/sanssecours/Natural-Docs.tmbundle/documentation/Preview.png)

# Requirements #

## NaturalDocs ##

Installation via [Homebrew](http://mxcl.github.io/homebrew/):

```shell
    brew install naturaldocs
```

# Variables #

* `ND_OUTPUT_DIRECTORY` — The sub-directory where the generated documentation will be saved (Default value: `Documentation`)
* `ND_PROJECT_DIRECTORY` — The project directory for Natural Docs (Default value: `.nd`)

# Installation #

```shell
    # TextMate 2
	cd ~/Library/Application\ Support/Avian/Bundles/
	git clone https://github.com/sanssecours/Natural%20Docs.tmbundle.git
```

# Usage #

Open a project containing Natural Docs Documentation and press `^⌘H` to
generate and display the current documentation.
