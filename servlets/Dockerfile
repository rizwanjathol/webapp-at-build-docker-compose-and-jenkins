FROM openjdk:13

RUN mkdir -p /app

WORKDIR /app

COPY . /constants ./app.jar/

#EXPOSE 3000

CMD [ "java", "-jar", "./app.jar" ]

EXPOSE 3000
