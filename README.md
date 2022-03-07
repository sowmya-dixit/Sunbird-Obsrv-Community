# Overview

Sunbird Obsrv comprises several pluggable tools and microservies that come together to enable observability features on any platform/solution. This includes the ability to capture granular events via telemetry, create measures, and observe various events/actions carried out by the system/users/devices (like IoT devices) on any platform/solution. Sunbird Obsrv can be utilized as an independent building block by adopters or as part of a system that employs other Sunbird building blocks. Sunbird Obsrv comes with a set of microservices, APIs, and some utility SDKs to make it easy for adopters to rapidly enable powerful data processing and aggregation infrastructure to process telemetry data, validate telemetry stream data, as well as aggregate and generate actionable insights via APIs. It also has built-in open data cataloging and publishing capability. It is built keeping extensibility in mind, so that adopters have the flexibility to adapt the telemetry and tools to their specific use-cases.



Sunbird Obsrv is a combination of various tools which provide the capabilities such as streaming, processing and storage of telemetry data and deriving reporting insights from the data.

By configuring the tools based on the requirements at hand, Sunbird Obsrv can be effectively used to enable observability and measurement across a wide variety of solutions. Various possibilities here could include:&#x20;

a. Generation, collection and processing of system data (what happened, when, and how) from activities happening on remote locations such as a satellite

b. Collection of survey data from a nationwide health survey to create a national health index and establish how various states stand with respect to it.

c. Monitoring telecommunication data across systems, when instrumented to generate appropriate data

d. Track uptake and progress data from a platform to gauge program roll-out and success rates

The generation of all necessary data for measurements, its streaming, processing and storage for consumption is what enables observability and trackability in a seamless manner.



Functional capabilities of Sunbird Obsrv:

**Defining what to measure, and how**: An ability to define a flexible specification to capture the user interaction/system data which will help in deriving insights about various metrics to understand or improve the system. The data could be generated from the client apps due to user interactions or from IoT devices to observe/capture a specific phenomenon or from backend systems generating logs of their activities.&#x20;

**Seamless transfer of data from source to store**: An out of the box design to stream and store the telemetry data by decoupling the data generation systems with the data processing systems.&#x20;

**Configurable data cleansing and processing**: An ability to cleanse and transform the user interaction/system data according to the reporting requirements. This is usually performed as a real-time stream processing with addition of metadata of various entities such as user, device and content to the telemetry data.&#x20;

**Out-of-the-box aggregates for common metrics**: Generate a high level summary from the telemetry data to compute measures such as time spent in a session and/or time spent on a content at a granular level such as a device or user.&#x20;

**Tools for user-friendly reporting**: An ability to load both the telemetry data and summarized data into an analytics data store to support queries and reporting requirements in near real-time.





![](<.gitbook/assets/data flow.png>)





**Enabling observability on Sunbird** - watch the video [here](https://www.youtube.com/watch?v=ldK4IJeE4X8)

{% embed url="https://www.youtube.com/watch?v=ldK4IJeE4X8" %}

\




&#x20;_**Sunbird Obsrv**_

**Adopters:** Diksha, iGot, Cowin

**Contributors**: EkStep

**Last Release Date**: 21st Oct, 2021

**Version**: 4.3.0

