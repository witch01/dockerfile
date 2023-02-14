FROM openjdk:8-jdk-alpine

COPY game.java /app/
WORKDIR /app/

RUN javac game.java

CMD ["java", "game"]