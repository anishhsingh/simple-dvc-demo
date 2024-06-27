create env


```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirement.txt
```
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit:"
```
```bash
git add .
```
```bash
git commit -m "updated README.md"
```
```bash
git remote add origin https://github.com/anishhsingh/simple-dvc-demo.git
git branch -M main
git push -u origin main
```