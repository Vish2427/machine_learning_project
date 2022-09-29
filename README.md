# machine_learning_project

This is first machine learning project

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
2. HEROKU_API_KEY = 228d98de-36ec-4353-852d-277317f2d7ea
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
