FROM openjdk:8-jdk-alpine

COPY calc.java /app/calc.java

WORKDIR /app

RUN javac calc.java

CMD ["java", "calc"]