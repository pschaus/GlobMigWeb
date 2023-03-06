# website

To compile locally (macos assuming python is installed)


Make sure sphinx is installed, if not you can do

```
python -m pip install --upgrade pip
pip install -r requirements.txt                                              
```

To generate the website do

```
make html
open _build/html/index #open the webpage in default browser                                           
```

Any push in the main branch will trigger a github action that will generate the
html website and push the result at the root of `gh-pages` branch.
This branch is served with github pages at url https://nicogol.github.io/GlobMigWeb/ .
