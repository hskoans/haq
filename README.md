# Understanding Cabal with Haq

1. Make a directory and add in haskell source code `Haq.hs`
2. Add in build system with `cabal init` so `haq.cabal` and related files get created
3. Initialise git and add in `.gitignore` file optionally
4. `cabal sandbox init` and `cabal install -j`
5. We can now run our built binary with `.cabal-sandbox/bin/haq me`, which would give the stdout response `Haq! me`
