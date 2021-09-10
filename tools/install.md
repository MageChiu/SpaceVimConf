# install
## linux and macOS
```shell
curl -sLf https://spacevim.org/install.sh | bash
```

get help

```shell
curl -sLf https://spacevim.org/install.sh | bash -s -- -h
```

if got a vimproc error:
```shell
[vimproc] vimproc's DLL: "~/.SpaceVim/bundle/vimproc.vim/lib/vimproc_linux64.so" is not found.
```

please:

```shell
cd ~/.SpaceVim/bundle/vimproc.vim
make
```


