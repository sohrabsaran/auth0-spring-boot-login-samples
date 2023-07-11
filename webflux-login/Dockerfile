WORKDIR /tmp
ADD . /tmp

RUN gradlew build

CMD ["gradle", "clean", "bootRun"]
EXPOSE 3000
