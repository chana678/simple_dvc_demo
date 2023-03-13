create env

```zsh
conda create -n wineq python=3.7 -y
```

activate env

```zsh
conda activate wineq
```

created a req file

install the req

```zsh
pip install -r requirements.txt
```

download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```zsh
git init
```

```zsh
dvc init
```

```zsh
dvc add data_given/winequality.csv
```

```zsh
git add .
```

```zsh
git commit -m "first commit"
```

oneliner updates for readme

```zsh
git add . && git commit -m "update Readme.md"
```

```zsh
git remote add origin https://github.com/chana678/simple_dvc_demo.git

git push -u origin main
```

tox command -

```zsh
tox
```

for rebuilding -

```zsh
tox -r
```

pytest command -

```zsh
pytest -v
```

setup commands -

```zsh
pip install -e .
```

build your own package commands -

```zsh
python setup.py sdist bdist_wheel
```
