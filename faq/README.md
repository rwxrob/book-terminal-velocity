# Frequently Answered Questions (FAQ)

**Q: What about the emacs editor?**  
**Q: What about the Visual Studio Code (VSCode) "light weight" editor?**  
**Q: How should I get Linux?**  
**Q: What about PowerShell on Windows?**  
**Q: Why not use zsh shell?**  
**Q: Why not use fish shell?**  
**Q: Why not use csh/tcsh shell?**  
**Q: Why not use POSIX (ash/dash) shell?**  
**Q: Why `podman` instead of `docker`?**  

## Q: Why not use POSIX (ash/dash) shell?

It's simply safer and easier to learn to code everything in `bash` and
limit yourself when there is a specific requirement to do so. When POSIX
compatibility is needed simply use `shellcheck` to restrict yourself to
using only what such shell support.

## Why bash shell?

* Bash is the default on all enterprise Linux distributions
* Bash is the most secure Linux shell on the planet
* Bash is the most powerful shell scripting language (associative
  arrays, regular expressions, parameter expansion, etc.)
