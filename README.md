# Image_scrapper

 ### Image_web_scrapper

### Start Python with Image_scrapper project.

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)


### Creating conda environment

```
conda create -n img_scrapper python==3.8 -y
```
```
conda activate img_scrapper
```
OR 
```
source activate img_scrapper
```

```
pip install -r requirements.txt
```

## To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
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

 ### To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```

## *To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = praveenku32k@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = mlreal

 # BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .

OR

docker build --tag python-docker .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 d930679e4d66  
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```
```
python setup.py install
```
```
pip install ipykernel
```
![Screenshot (4)](https://github.com/Praveenku32k/Image_scrapper/assets/68581081/e59a775c-e563-4e82-af35-873e97d4f1d4)

![Screenshot (2)](https://github.com/Praveenku32k/Image_scrapper/assets/68581081/eeeefaf9-3e5c-4b9e-87eb-d869aa6e2608)


                    ### Thank you...
