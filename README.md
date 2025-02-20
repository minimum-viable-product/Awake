# 🐧 _Awake! Linux_
_A politically agnostic Linux distribution, without any AI 🐄💩_

---

* Fiercely independent & honest open-source software. _(The FUTO Pledge)_
  - We will never sell out.
  - We will never abuse our users.
  - We will always be transparently devoted to making delightful software.
* Linux From Scratch (LFS) is the initial starting point.
  - Available security updates / bug fixes applied.
  - Custom script(s) based on manual instructions (not necessarily ALFS, but possibly).
* System to be migrated to clang/llvm instead of / in addition to gnu toolchain.
  - Because clang/llvm toolchain offers better static analysis features.
  - Because clang/llvm toolchain generally results in better performance.
* Follow standards as much as reasonably possible.
  - POSIX
  - FHS

---

## Knowledge
* [The Linux Documentation Project](https://tldp.org/) - _All the classic oldskool essentials!_
  - [Introduction to Linux](https://tldp.org/LDP/intro-linux/html/index.html)
  - [Pocket Linux Guide](https://tldp.org/LDP/Pocket-Linux-Guide/html/index.html)
  - [System Administrator's Guide](https://tldp.org/LDP/sag/html/index.html)
* [Linux From Scratch](https://www.linuxfromscratch.org/) [[_wikipedia_](https://en.wikipedia.org/wiki/Linux_From_Scratch)]
  - [LFS current/stable](https://linuxfromscratch.org/lfs/view/stable/)
  - [LFS current/multilib](https://www.linuxfromscratch.org/~thomas/multilib/index.html)
  - [LFS 6.3](https://linuxfromscratch.org/museum/lfs-museum/6.3/LFS-BOOK-6.3-HTML/) (_2007_)
  - [BLFS current/stable](https://linuxfromscratch.org/blfs/view/stable/)
* [ArchWiki](https://wiki.archlinux.org/title/Main_page)
  - [General Recommendations](https://wiki.archlinux.org/title/General_recommendations)
  - [Installation Guide](https://wiki.archlinux.org/title/Installation_guide)
  - [Man Pages](https://man.archlinux.org/)
* Standards
  - [Filesystem Hierarchy Standard (FHS) 3.0](https://refspecs.linuxfoundation.org/FHS_3.0/fhs/index.html) - linux foundation [[_wikipedia_](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard)]
  - [POSIX.1-2024](https://pubs.opengroup.org/onlinepubs/9799919799/) - opengroup
  - [Linux Standard Base (LSB)](https://linuxfromscratch.org/lfs/view/stable/prologue/standards.html) - lfs
  - [Unix Philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) - wikipedia
* Miscellaneous
  - [Handmade Manifesto](https://handmade.network/manifesto)
  - [We are destroying software](https://antirez.com/news/145) - antirez

## Desktop Environment
* [freedesktop.org](https://www.freedesktop.org/wiki/) [[_wikipedia_](https://en.wikipedia.org/wiki/Freedesktop.org)]
* LXDE - [[_archwiki_](https://wiki.archlinux.org/title/LXDE)] [[_github_](https://github.com/lxde)] [[_wikipedia_](https://en.wikipedia.org/wiki/LXDE))]
* GTK+ 2
  - [reference manual](https://www.manpagez.com/html/gtk2/gtk2-2.24.29/) - v2.24 @ manpagez.com
  - [source code](https://download.gnome.org/sources/gtk%2B/2.24/) [[_github_](https://github.com/GNOME/gtk/tree/2.24.33)] - v2.24
  - [archwiki](https://wiki.archlinux.org/title/GTK)
  - [gtkmm](https://download.gnome.org/sources/gtkmm/2.24/) - v2.24

## Packaging
* [Beginner's Guide to Installing from Source](https://moi.vonos.net/linux/beginners-installing-from-source/)
* [Software Building HOWTO](https://tldp.org/HOWTO/Software-Building-HOWTO.html) - tldp
* [Rationale for Packages](https://linuxfromscratch.org/lfs/view/stable/prologue/package-choices.html) - lfs
* zstd - [[_github_](https://github.com/facebook/zstd)] [[_wikipedia_](https://en.wikipedia.org/wiki/Zstd)]

## Core Utilities
* [gnu bash](https://www.gnu.org/software/bash/) [[_wikipedia_](https://en.wikipedia.org/wiki/Bash_(Unix_shell))]
  - [The Shell Scripting Tutorial](https://www.shellscript.sh/) - shellscript.sh
  - [Bourne Shell Scripting](https://en.wikibooks.org/wiki/Bourne_Shell_Scripting) - wikibooks
  - [BASH Programming - Introduction HOW-TO](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html) - tldp
  - [Advanced Bash-Scripting Guide](https://tldp.org/LDP/abs/html/index.html) - tldp
* [gnu coreutils](https://www.gnu.org/software/coreutils/coreutils.html) [[_wikipedia_](https://en.wikipedia.org/wiki/List_of_GNU_Core_Utilities_commands)] (_or [toybox](http://www.landley.net/toybox/)_)
* [util-linux](https://en.wikipedia.org/wiki/Util-linux) - wikipedia

## Core Development Tools
* [clang](https://clang.llvm.org/) ([_wikipedia_](https://en.wikipedia.org/wiki/Clang))
* [llvm](https://llvm.org/) ([_wikipedia_](https://en.wikipedia.org/wiki/LLVM))
* [lld](https://lld.llvm.org/)
* [gnu make](https://www.gnu.org/software/make/) ([_wikipedia_](https://en.wikipedia.org/wiki/Make_(software)))
* [git](https://git-scm.com/doc) ([_manpage_](https://www.kernel.org/pub/software/scm/git/docs/)) ([_wikipedia_](https://en.wikipedia.org/wiki/Git))

## Booting
* [Booting process of Linux](https://en.wikipedia.org/wiki/Booting_process_of_Linux)
* [From Power Up To Bash Prompt HOWTO](https://tldp.org/HOWTO/From-PowerUp-To-Bash-Prompt-HOWTO.html) - tldp ([_pdf_](https://tldp.org/HOWTO/pdf/From-PowerUp-To-Bash-Prompt-HOWTO.pdf))
* [init](https://en.wikipedia.org/wiki/Init) - wikipedia

## Linux Kernel
* [kernel.org](https://kernel.org/)
  - [Minimal requirements to compile the Kernel](https://www.kernel.org/doc/html/latest/process/changes.html)
  - [Building Linux with Clang/LLVM](https://www.kernel.org/doc/html/latest/kbuild/llvm.html)
* [KernelBuild](https://kernelnewbies.org/KernelBuild) - linux kernel newbies
* [BuildYourOwnKernel](https://wiki.ubuntu.com/Kernel/BuildYourOwnKernel) - ubuntu wiki
* [Kernel/Traditional compilation](https://wiki.archlinux.org/title/Kernel/Traditional_compilation) - arch wiki
