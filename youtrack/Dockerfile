FROM java:8
MAINTAINER Guido Zockoll

RUN wget http://download.jetbrains.com/charisma/youtrack-6.5.16807.jar -O youtrack.jar

EXPOSE 80
CMD ["java", "-Xmx1g", "-XX:MaxPermSize=250m", "-Djava.awt.headless=true", "-jar", "youtrack.jar", "80"]
