# What commands exactly?

There are thousands of terminal commands so isolating the ones you will use the most is crucial if you actually care about your time. Eventually, you'll come to master more and more, even make your own. That's when you know you've *arrived*.

The most fundamental commands run the interactive terminal shell itself and lookup local help information when you encounter something you don't know.

`sh`, `ash`, `dash`, `bash`, `man`, `help`

Usually, you don't have a terminal interface readily available and need to connect to one, locally or remotely.

`ssh`, `docker`, `podman`, `kubectl`, `kind`, `minikube`

And not having a pretty graphic interface with cute folder icons makes understanding how the file system is organized and searched essential, and powerful. For example, moving or renaming hundreds of files with a single command would take hours with a graphic user interface.

`ls`, `pwd`, `cd`, `mv`, `touch`, `rm`, `rmdir`, `chown`, `du`, `df`

But what is actually in those files and how do you find something specific?

`file`, `cat`, `tac`, `head`, `tail`, `grep`, `head`, `find`, `jq`, `yq`

Files that are too big to copy around easily, or that need to be combined into a single file, or encrypted add a layer you'll need to unwrap to get to the content.

`gz`, `gunzip`, `tar`, `base64`

Backing up files in a way that preserves the changes and allows different versions to be tracked and managed is important if you actually *care* about what they contain.

`sftp`, `scp`, `git`, `gh`, `rsync`

Changing what's in the file using nothing but tools available from the terminal usually involves a terminal editor, but not always.

`ed`, `sed`, `vi`, `vim`, `nvi`

Not having a mouse, or even more than one terminal window can get pretty frustrating, and limiting, which is why "multiplex" commands were invented.

`screen`, `tmux`

And now that you can have several windows and panes open at the same time and navigate between them with nothing but your keyboard it is time to drop your graphic browser for more searching on the Web and using a lightning-fast, visually consistent, secure, image-less text-based browser instead. Don't worry, you can open your fat graphic browser with one keystroke when you need it to see the images or the "mandatory" JavaScript some stupid web developers require.

`lynx`, `w3m`

Speaking of stupid web developers, have you heard about  *Knowledge Exchange Graphs* on the KEG network? It's an ultralight alternative to the modern Web for creating, managing, and exchanging your knowledge using nothing but your favorite terminal editor.

`keg`, `pandoc`

Need really powerful mathematical calculations quickly?

`bc`, `dc`

Eventually, you will begin scripting your favorite things to create your own commands and be able to manage things that are currently running.

`ps`, `bash`, `shellcheck`, `env`
