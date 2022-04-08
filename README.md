# confit-spark
Conf.it conference spark training


File to download:

Zip version:

https://drive.google.com/file/d/1vjlFg5kuQ0jme2RQqtJqmk-vFbJdiZQK/view?usp=sharing

Tar version:

https://drive.google.com/file/d/1w8vNjaagQlzTQS31tHOhMWJA7_oX37Io/view?usp=sharing

Unzip the file `tar xvf file.tar.gz`

Make sure the file is unziped in the file of this project


Launch the docker:
```bash
docker run -it --rm -p 8888:8888 -p 4040:4040 -m 4g -v "$PWD":/home/jovyan/work --platform linux/amd64 almondsh/almond:0.10.9-scala-2.12.12
```
