docker build -t greeter:v1 -f lessons/02-docker-basics/homework.md

docker run -d --name greeter -p 9000:8000 greeter:v1

docker run -d --name greeter -p 9000:8000 -e GREETING=Shalom greeter:v1

Shalom Rivka
                                                                                                                                                     #יוגדרו כ cached
FROM

WORKDIR

COPY requirements.txt 

RUN pip install 

                                                                                                                                                          #ירוצו מחדש
COPY . 

EXPOSEו-CMD
