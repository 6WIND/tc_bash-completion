# Bash completion function for `tc` utility

## Merged into iproute2 package

This code has been merged into the iproute2 package in
[this commit](https://git.kernel.org/cgit/linux/kernel/git/shemminger/iproute2.git/commit/?id=27d44f3a8a4708bcc99995a4d9b6fe6f81e3e15b)
(on 2016-05-03).

As of May 2016, the completion code can be fetched from iproute2 repository
[at this address](https://git.kernel.org/cgit/linux/kernel/git/shemminger/iproute2.git/tree/bash-completion/tc)

The version that used to be accessible on this repository would not received
any update, and hence has been removed.

## Installation

1.  Get the source file (see above). It should be called `tc`, and should not
    be renamed.

2.  Make sure you load `bash_completion` script, for example in your `~/.bashrc`

        [[ $PS1 && -f /usr/share/bash-completion/bash_completion ]] && \
            . /usr/share/bash-completion/bash_completion

3.  Load the function:

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

This code is now part of the iproute2 package, and as such it is released under
the GPLv2 license.
