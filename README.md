# Sunbird Obsrv

_Obsrv_ as a Sunbird building block comprises of several components that come together to enable the ability to measure and observe various actions and activities carried out by the system/ users. _Obsrv_ can be utilised as an independent building block that allows for measurement, or as part of a system that employs different Sunbird blocks to enable  various workflows.&#x20;

It offers powerful data processing and aggregation infrastructure to process telemetry data generated by users & systems, validate the data, as well as aggregate and generate insights. It also has built-in open data cataloging and publishing capability. It is built keeping extensibility in mind, so that adopters have the flexibility to adapt the telemetry and tools to their specific use-cases.



![](<.gitbook/assets/data flow.png>)



Enabling observability on Sunbird - watch the video [here](https://www.youtube.com/watch?v=ldK4IJeE4X8)

\


**OVERVIEW**

Sunbird allows for generation and consumption of usage data in order to be able to carry out any required analysis. The data flow on the platform is as illustrated below.



The client apps and micro services within Sunbird are instrumented to generate Telemetry data to capture usage and various actions to derive insights. The data pipeline will process the Telemetry event stream data in near real-time by application of a series of validation, de-duplication, transformation and denormalization steps. The Telemetry data is synced at various points in the data pipeline to a configurable cloud storage which acts as the persistent data storage.

A generic summarized dataset is generated from the Telemetry data which will comprise of commonly used summaries such as session summary. The summarized dataset is an aggregated dataset which can be used to generate custom derived datasets required for custom workflows.

The telemetry event data is then synced to a configurable analytic data store to build a access layer to the data sets. The adopters are free to choose any analytics data store and/or visualisation tools (Sunbird supports Druid and Superset out-of-the-box) of their choice to build canned reports and dashboards to slice and dice the data.

Sunbird Obsrv is a combination of various tools which provide the capabilities such as streaming, processing and storage of telemetry data and deriving reporting insights from the data.

![Data analytics architecture](<.gitbook/assets/DataPipeline BB HighLevel Diagram.png>)

&#x20;

_<mark style="color:blue;">Obsrv</mark>_ <mark style="color:blue;">can be leveraged to:</mark>

* Allow for `capture of telemetry` as per chosen specifications from an agricultural monitoring system, and `processing and analysis of the resulting data` to optimise output
* Aggregation of anonymised health data from across platforms, and its `analysis` to arrive at health indicators and patterns at population scale.&#x20;
* Analysis of `streams of weather data` from satellites to better `predict` weather patterns.

****

**\[Diagram to be added : architecture diagram of the BB representing the technology stack/tools and connectivity between them?]**

****

_Obsrv_ allows for extensive configurability so as to enable creation of various custom workflows. Refer to the pages for different components on the left panel to see details of what configurations are available for each.



**Adopters: **Diksha, iGot, Cowin

**Contributors**: EkStep

**Last Release Date**: 21st Oct, 2021

**Version**: 4.3.0

