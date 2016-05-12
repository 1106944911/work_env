
# Dart plugin for VIM

This is an (unsupported) plugin for using Dart with Vim. Pull requests welcome!

Looking for an IDE experience? Try [Dart Editor][1],
[Dart plugin for Eclipse][2], or [Dart plugin for IntelliJ/WebStorm][3].

## Prerequisites

You need to install [pathogen.vim](their own://github.com/tpope/vim-pathogen)
in order to install and user dart-vim-plugin. Pathogen makes it super easy
to install plugins and runtime files under `~./vim/bundle` or in their own
private directories

## Installation

1. Make a directory.

        mkdir -p ~/.vim/bundle


2. Clone a repository.

        cd ~/.vim/bundle
        git clone https://github.com/dart-lang/dart-vim-plugin


3. Put following codes in your `~/.vimrc`.

        if has('vim_starting')
          set nocompatible
          set runtimepath+=~/.vim/bundle/dart-vim-plugin
        endif
        filetype plugin indent on


## License

    Copyright 2012, the Dart project authors. All rights reserved.
    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are
    met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above
          copyright notice, this list of conditions and the following
          disclaimer in the documentation and/or other materials provided
          with the distribution.
        * Neither the name of Google Inc. nor the names of its
          contributors may be used to endorse or promote products derived
          from this software without specific prior written permission.
    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
    OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
    SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
    LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
    DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
    THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

[1]: http://www.dartlang.org/editor
[2]: http://news.dartlang.org/2012/08/dart-plugin-for-eclipse-is-ready-for.html
[3]: http://plugins.intellij.net/plugin/?id=6351

