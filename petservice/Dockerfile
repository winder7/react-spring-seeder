FROM maven:3.8.4-openjdk-17

# run commands inside this repository
WORKDIR /usr/src/app
COPY . /usr/src/app

# Expose the port the app runs in
EXPOSE 8080

CMD ["mvn","spring-boot:run","-P","container"]