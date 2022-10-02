# machine_learning_project

This is first machine learning project

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment

```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```

or

```

conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git

```
git add .
```

OR

```
git add <file_name>
```

> Note:To ignore file or folder from git we canwrite name of file/folder in .gitignore file

To cheeck the git status

```

git status

```

To check all version maintained by git

```

git log

```

To create version/commit all changes by git

```

git commit -m "message"

```

To send version/changes to git hub

```

git push origin main

```

To check remote url

```

git remote -v

```

To check branch

```

git branch

```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = ranbirrathore150@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = app-ml-project

BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must br lowercase

To list docker image

```
docker images
```

Run docker image

```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running conatines in docker

```
docker ps
```

To stop docker conatiner

```
docker stop <conatiner_id>
```

Install automatically all packages that mentioned in setup.py,

> Note: No need to run now pip install -r requirments.txt

```
python setup.py install
```

Install ipynb kernal

```
pip install ipykernel
```
