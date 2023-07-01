## ML Project with DVC

### created a environment in gitbash terminal
```
conda create -p venv python=3.8 -y

source activate ./venv

```
### Install all necessary libraries
```
pip install -r requirements.txt
```

### create neccesary files 
```
touch .gitignore

touch README.md
```
### basic commands
```
dvc init

dvc repro

dvc dag

dvc add <file name>

git add <file_names> && git commit -m "file added successfully

dvc remote add myremote <any_remote_location>

dvc push
```

### Official dvc documentation
```
https://dvc.org/doc
```
