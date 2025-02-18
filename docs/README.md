# Awesome Xontribs

> [Xonsh](https://xon.sh/) is a Python-powered, cross-platform, Unix-gazing shell language and command prompt. 
> xontributions, or xontribs, are a set of tools and conventions for extending the functionality of [xonsh](https://xon.sh/).

Awesome list of Xonsh contributions/extensions. 



## Popular Links

- [Official Site](https://xon.sh/)
- [GitHub Repository](https://github.com/xonsh/xonsh)
- [Gitter Channel](https://gitter.im/xonsh/xonsh)
- [Xontribs@GitHub](https://github.com/topics/xontrib)
- [Xontrib Template](https://github.com/xonsh/xontrib-cookiecutter/)


## Core Xontribs

*These [modules](https://xon.sh/api/_autosummary/xontribs/xontrib.html) are part of xonsh itself but need to be loaded explicitly using [`xontrib load`](https://xon.sh/tutorial_xontrib.html#loading-xontribs)*

* [abbrevs](https://xon.sh/api/_autosummary/xontribs/xontrib.abbrevs.html#module-xontrib.abbrevs) - Fish like command abbreviations

* [bashisms](https://xon.sh/api/_autosummary/xontribs/xontrib.bashisms.html#module-xontrib.bashisms) - Bash-like interface extensions for xonsh.

* [coreutils](https://xon.sh/api/_autosummary/xontribs/xontrib.coreutils.html#module-xontrib.coreutils) - Additional core utilities that are implemented in xonsh.

* [fish_completions](https://xon.sh/api/_autosummary/xontribs/xontrib.fish_completer.html#module-xontrib.fish_completer) - Populate rich completions using fish shell instead of bash

* [free_cwd](https://xon.sh/api/_autosummary/xontribs/xontrib.free_cwd.html#module-xontrib.free_cwd) - This will release the lock on the current directory whenever the prompt is shown.

* [pdb](https://xon.sh/api/_autosummary/xontribs/xontrib.pdb.html#module-xontrib.pdb) - Simple built-in debugger.

* [prompt_ret_code](https://xon.sh/api/_autosummary/xontribs/xontrib.prompt_ret_code.html#module-xontrib.prompt_ret_code) - show return-code from last command in prompt

* [whole_word_jumping](https://xon.sh/api/_autosummary/xontribs/xontrib.whole_word_jumping.html#module-xontrib.whole_word_jumping) - Jumping across whole words (non-whitespace) with Ctrl+Left/Right.

* [xog](https://xon.sh/api/_autosummary/xontribs/xontrib.xog.html#module-xontrib.xog) - This adds xog - a simple command to establish and print temporary traceback log file.

### Python virtual-environment management

  * [vox](https://xon.sh/api/_autosummary/xontribs/xontrib.vox.html#module-xontrib.vox) - Python virtual environment manager for xonsh.
  * [autovox](https://xon.sh/api/_autosummary/xontribs/xontrib.autovox.html#module-xontrib.autovox) - A framework for automatic vox.


## Tab-completions

*Extends auto-completion capabilities*

* [apt_tabcomplete](https://github.com/DangerOnTheRanger/xonsh-apt-tabcomplete) - Adds tabcomplete functionality to apt-get/apt-cache inside of xonsh.
* [argcomplete](https://github.com/anki-code/xontrib-argcomplete) - Argcomplete support to tab completion of python and xonsh scripts in xonsh.
* [django](https://github.com/jnoortheen/xontrib-django) - Django management command completions for Xonsh shell
* [docker_tabcomplete](https://github.com/xsteadfastx/xonsh-docker-tabcomplete) - Adds tabcomplete functionality to docker inside of xonsh.
* [jedi](https://github.com/xonsh/xontrib-jedi) - Use Jedi as xonsh's python completer.
* [scrapy_tabcomplete](https://github.com/Granitas/xonsh-scrapy-tabcomplete) - Adds tabcomplete functionality to scrapy inside of xonsh.

## Directory Navigation

* [autojump](https://github.com/wshanks/xontrib-autojump) - autojump support for xonsh
* [back2dir](https://github.com/anki-code/xontrib-back2dir) - Return to the most recently used directory when starting the xonsh shell. For example, if you were in the '/work' directory when you last exited xonsh, then your next xonsh session will start in the '/work' directory, instead of your home directory.
* [broot](https://github.com/jnoortheen/xontrib-broot) - supports broot with br alias
* [cd](https://github.com/eugenesvk/xontrib-cd) - 'cd' to any path without escaping in xonsh shell ('cd '→'cd! ')
* [hist_navigator](https://github.com/jnoortheen/xontrib-hist-navigator) - fish like `nextd` and `prevd` with default keybindings.
* [up](https://github.com/oh-my-xonsh/xontrib-up) - The fast way to go up directories.
* [z](https://github.com/AstraLuma/xontrib-z) - Tracks your most used directories, based on 'frecency'.
* [zoxide](https://github.com/dyuri/xontrib-zoxide) - Zoxide integration for xonsh.



## Prompts

* [powerline](https://github.com/santagada/xontrib-powerline) - Powerline for Xonsh shell

* [powerline2](https://github.com/vaaaaanquish/xontrib-powerline2) - Powerline for Xonsh shell forked from santagada/xontrib-powerline

* [powerline3](https://github.com/jnoortheen/xontrib-powerline3) - Powerline theme with native $PROMPT_FIELDS support.

* [powerline_binding](https://github.com/dyuri/xontrib-powerline-binding) - Uses powerline to render the xonsh prompt

* [prompt_bar](https://github.com/anki-code/xontrib-prompt-bar) - An elegance bar style for prompt.

* [prompt_starship](https://github.com/anki-code/xontrib-prompt-starship) - Starship prompt in xonsh shell.

* [prompt_vi_mode](https://github.com/t184256/xontrib-prompt-vi-mode) - vi-mode status formatter for xonsh prompt

  

## Theming & Styling

* [base16_shell](https://github.com/ErickTucto/xontrib-base16-shell) - Change base16 shell themes
* [gruvbox](https://github.com/rpdelaney/xontrib-gruvbox) - A gruvbox color scheme for xonsh
* [dracula](https://github.com/agoose77/xontrib-dracula) - Dracula theme for xonsh.



## Integrations

* [distributed](https://github.com/xonsh/xontrib-distributed) - The [distributed](https://pypi.org/project/distributed/) parallel computing library hooks for xonsh.
* [jupyter](https://github.com/xonsh/xontrib-jupyter-shell) - Jupyter Notebook kernel for Xonsh
* [kitty](https://github.com/scopatz/xontrib-kitty) - Xonsh hooks for the Kitty terminal emulator.
* [mpl](https://github.com/xonsh/xontrib-mpl) - Matplotlib hooks for xonsh, including the new 'mpl' alias that displays the current figure on the screen.
* [pyenv](https://github.com/dyuri/xontrib-pyenv) - pyenv integration for xonsh.
* [homebrew](https://github.com/eugenesvk/xontrib-homebrew) - Add Homebrew's shell environment to xonsh shell on macOS/Linux
* [init_ssh_agent](https://github.com/theRealBithive/xontrib-init-ssh-agent) - ssh-agent initialization
* [ssh_agent](https://github.com/dyuri/xontrib-ssh-agent) - ssh-agent integration
* [tcg](https://github.com/zasdfgbnm/tcg/tree/master/shells/xonsh) - tcg integration.
* [xo](https://github.com/scopatz/xo) - Adds an 'xo' alias to run the exofrills text editor in the current Python interpreter session. This shaves off a bit of the startup time when running your favorite, minimal text editor.

## Plugins

* [autoxsh](https://github.com/Granitas/xonsh-autoxsh) - Adds automatic execution of xonsh script files called ``.autoxsh`` when enterting a directory with ``cd`` function

* [cmd_done](https://github.com/jnoortheen/xontrib-cmd-durations) - send notification once long-running command is finished. Adds `long_cmd_duration` field to $PROMPT_FIELDS.

* [commands](https://github.com/jnoortheen/xontrib-commands) - Some useful commands/aliases to use with Xonsh shell

* [default-command](https://github.com/oh-my-xonsh/xontrib-default-command) - Run a default command when you press return on an empty command line.

* [direnv](https://github.com/74th/xonsh-direnv) - Supports direnv.

* [fzf-widgets](https://github.com/laloch/xontrib-fzf-widgets) - Adds some fzf widgets to your xonsh shell.

* [gitinfo](https://github.com/dyuri/xontrib-gitinfo) - Displays git information on entering a repository folder. Uses ``onefetch`` if available.

* [history_encrypt](https://github.com/anki-code/xontrib-history-encrypt) - History backend that encrypt the xonsh shell commands history to prevent leaking sensitive data.

* [histcpy](https://github.com/con-f-use/xontrib-histcpy) - Useful aliases and shortcuts for extracting links and textfrom command output history and putting them into the clipboard.

* [macro_lib](https://github.com/anki-code/xontrib-macro-lib) - Library of the useful macros for the xonsh shell.

* [onepath](https://github.com/anki-code/xontrib-onepath) - When you click to a file or folder in graphical OS they will be opened in associated app.The xontrib-onepath brings the same logic for the xonsh shell. Type the filename or pathwithout preceding command and an associated action will be executed. The actions are customizable.

* [output_search](https://github.com/anki-code/xontrib-output-search) - Get identifiers, names, paths, URLs and words from the previous command output and use them for the next command.

* [pipeliner](https://github.com/anki-code/xontrib-pipeliner) - Let your pipe lines flow thru the Python code in xonsh.

* [pyrtn](https://github.com/dyuri/xontrib-pyrtn) - IPython like In[]/Out[] to access python return values in the current session.

* [readable-traceback](https://github.com/6syun9/xontrib-readable-traceback) - Make traceback easier to see for xonsh.

* [schedule](https://github.com/AstraLuma/xontrib-schedule) - Xonsh Task Scheduling

* [sh](https://github.com/anki-code/xontrib-sh) - Paste and run commands from bash, zsh, fish in xonsh shell.

* [xpg](https://github.com/fengttt/xsh/tree/master/py) - Run/plot/explain sql query for PostgreSQL.

### Python virtual-environment management

  * [avox](https://github.com/AstraLuma/xontrib-avox) - Policy for autovox based on project directories

  * [avox_poetry](https://github.com/jnoortheen/xontrib-avox-poetry) - auto-activate venv as one cd into a poetry project folder. Activate ``.venv`` inside the project folder is also supported.

    
