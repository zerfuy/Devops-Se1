FROM openjdk:11
COPY src/Main.java /src/Main.java
RUN javac /src/Main.java

FROM openjdk:11-jre
COPY --from=0 /src/Main.class Main.class
RUN java Main