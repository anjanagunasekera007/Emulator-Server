# Emulator Server

The emulator server is responsible for starting all the backend servers

## Installation

`mvn clean compile assembly:single`

## Running

`java -jar target/emulator-service-1.0.0-SNAPSHOT-jar-with-dependencies.jar your_ip_address`

Here replace `your_ip_address` with your ip where the servers would be running. 
