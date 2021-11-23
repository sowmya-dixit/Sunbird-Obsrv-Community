# Telemetry Service

Telemetry Service is a highly scalable micro service which allows various components in the Sunbird platform to send the event level data generated from various activities in the platform. These event level data could be either from clients such as the user apps or from micro services such as Sunbird Lern.

#### Key Features:

1. Horizontally Scalable: The service can be scaled horizontally to handle increase in Telemetry data traffic as the operations are idempotent.
2. Configurable storage: The service supports disk storage, Apache Kafka, Apache Cassandra as data storage.
3. In-built compression: Efficient use of network bandwidth by compressing the messages sent to the data storage.



**API Documentation:**

The API documentation for the Telemetry service can be found [here](http://docs.sunbird.org/latest/apis/telemetryapi/index.html).



**Code Repo:**

The source code for the Telemetry service can be found [here](https://github.com/project-sunbird/sunbird-telemetry-service).
