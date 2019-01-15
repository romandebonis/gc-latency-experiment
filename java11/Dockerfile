FROM openjdk:11-jdk
COPY Main.java .
RUN javac Main.java
ENTRYPOINT ["java", "-Xmx512m", "-XX:+PrintFlagsFinal", "-verbosegc", "-XX:+UnlockExperimentalVMOptions", "-XX:+UseZGC", "Main"]
