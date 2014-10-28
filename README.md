homebrew-gnuradio
=================

Delicious and foamy --HEAD only tap of the latest development version of gnuradio! Yay! Builds clean on Mac OS X Yosemite 10.10 using Xcode 6.1 command line tools (clang/llvm).  

Disable virtualenv if you use it, and:

```sh
brew install python

pip install --upgrade setuptools
pip install --upgrade pip

pip install numpy -U scipy -U matplotlib -U
```

That's all the prepwork, and if you missed a python dependency, while homebrew cannot install it for you, this tap will notice and inform you what dependencies, if any, you need to install using pip.

Anyway, you're ready to 
```sh
brew tap metacollin/gnuradio
brew install --HEAD gnuradio --with-qt --with-docs
```
and optionally
```sh
brew install --HEAD rtl-sdr #Osmocom rtl-sdr support
```

Omit `--with-qt` and `--with-docs` at your descretion.  This is a very dependency heavy recipe, so if you're starting from scratch, make sure have access to food because you'll probably need a snack before it's done.  I like nutella on toast, personally.

Awwwww yisssss.
