## How to deploy

First clone the repository and update!

```console
git clone git@git-tusher:md-tusher-mollah/starter-academic.git tusher

cd tusher

git submodule update --init --recursive
```

Then delete the public folder if exists! And after that add the submodule by typing the following in the terminal.

```console
git submodule add -f -b master git@git-tusher:md-tusher-mollah/md-tusher-mollah.github.io.git public
```

Now lets push those codes into the repository.

```console
git add .
git commit -m "message"
git push -u origin master
```

We will generate the website now and then push the website into the repository.

```conosole
hugo
cd public
git add .
git commit -m "message"
git push -u origin master
cd ..
```

### Publications

## Import from BibTeX

Python must be installed into the system, then install academic from pip.

```console
pip3 install -U academic
```

Use the cd command to navigate to your website folder in the terminal.

Then import your publications with:

```console
academic import --bibtex <path_to_your/publications.bib>
```



