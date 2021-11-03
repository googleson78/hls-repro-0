## repro instructions
```sh
> haskell-language-server-wrapper --version
haskell-language-server version: 1.4.0.0 (GHC: 8.10.4) (PATH: /home/googleson78/.ghcup/bin/haskell-language-server-wrapper-1.4.0) (GIT has
h: 253547816ee216c53ee7dacc0ad3cac43e863d30)
```
```sh
haskell-language-server-9.0.1 --version
haskell-language-server version: 1.4.0.0 (GHC: 9.0.1) (PATH: /home/googleson78/.ghcup/bin/haskell-language-server-9.0.1~1.4.0) (GIT hash:
253547816ee216c53ee7dacc0ad3cac43e863d30)
```

Run `haskell-language-server-wrapper`.

Error is
```
haskell-language-server-9.0.1: allocatestack.c:384: advise_stack_range: Assertion `freesize < size' failed.
haskell-language-server-wrapper: callProcess: /home/googleson78/.ghcup/bin/haskell-language-server-9.0.1 (exit -6): failed
```
