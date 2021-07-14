FROM tomcat

RUN apt-get update -y

RUN apt-get install -f

RUN apt-get install git -y

RUN apt-get install nodejs -y

RUN apt-get install npm -y

RUN mkdir -p /tmp/build

WORKDIR /tmp/build/

RUN git clone https://Batista_Ricardo@bitbucket.org/Batista_Ricardo/devops-20-21.git

WORKDIR /tmp/build/devops-20-21/ca4/Part2/demo

RUN chmod u+x gradlew

RUN ./gradlew clean build

RUN cp build/libs/part2-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/

EXPOSE 8080