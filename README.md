# Bash completion function for `tc` utility

## Installation

1.  Make sure you load `bash_completion` script, for example in your `~/.bashrc`

        [[ $PS1 && -f /usr/share/bash-completion/bash_completion ]] && \
            . /usr/share/bash-completion/bash_completion

2.  Load the function:

        wget https://raw.githubusercontent.com/6WIND/tc_bash-completion/master/tc
        source ./tc

    Alternatively, you can load it automatically by moving the file to somewhere
    bash-completion will find it, usually under
    `/usr/share/bash-completion/completions/` or by copying its content into
    file `~/.bash_completion`.

More detailed instruction for installation and usage of bash-completion are
available [here](https://github.com/scop/bash-completion#installation).

## Usage

Once the script is loaded, Bash should automatically provide completion for
`tc` commands. Start typing a command and hit `<Tab>`. And enjoy!

## License

This code is released under the GPLv2 − see
[license file](https://raw.githubusercontent.com/6WIND/tc_bash-completion/master/LICENSE).
