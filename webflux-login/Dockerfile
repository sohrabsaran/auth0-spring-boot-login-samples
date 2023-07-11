WORKDIR /tmp
ADD . /tmp

RUN ./gradlew build

CMD ["./gradlew", "clean", "bootRun"]
EXPOSE 3000
