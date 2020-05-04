# TrackNTrace
Landing Page for all Repositories used for creating of EPCIS-IoT based Product Tracking &amp; Tracing.

## Repositories
The repositories listed here are in accordance to the Bottom-Top Approach to the proposed architecture in the research papers.

| Repository                                | Purpose                                                                                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| [EPCIS-IoT-Arduino](https://github.com/iotfablab/EPCIS-IoT-Arduino) | Arduino Library to Program ESP32 Microcontrollers with BME280 and sending information via MQTT to a Broker |
| [tiguitto for nimble-platform](https://github.com/nimble-platform/tiguitto) | Complete Telegraf + InfluxDB + Grafana + Mosquitto MQTT broker with Parsing configuration for EPCIS-IoT |
| [EPCIS-IoT-detection-mechanism](https://github.com/shantanoo-desai/EPCIS-IoT-detection-mechanism) | Automated Script in python3.x to contextually merge EPCDocuments and IoT information |
| [tracking-iot-blockchain-service](https://github.com/shantanoo-desai/tracking-iot-blockchain-service) | RESTful Service for Validating EPCIS-IoT Data w/Blockchain & quering IoT Data |
| [Tracking Microservice for NIMBLE Platform](https://github.com/nimble-platform/tracking-service) | Microservice to provide product tracking information for NIMBLE Platform Frontend |
| [Oliot EPCIS for NIMBLE Platform](https://github.com/nimble-platform/epcis) | Oliot EPCIS for the NIMBLE Platform |


### Deprecated Repositories
Use the [nimble-platform/tiguitto](https://github.com/nimble-platform/tiguitto) to use Telegraf as a parsing mechanism for Published MQTT information on a MQTT Broker.

| Deprecated Repositories                   | Purpose                                                                                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| [EPCIS-IoT-Parser](https://github.com/iotfablab/EPCIS-IoT-Parser)  | Python3.x Parser for parsing incoming MQTT Messages and adding relevant EPC meta-data to IoT Sensor data |
| [epcis-iot-backend](https://github.com/shantanoo-desai/epcis-iot-backend) | GraphQL backend for configuring EPCIS Sites and mapping EPCIS and IoT information used by the Parser |
| [epcis-iot-backend](https://github.com/shantanoo-desai/ng-epcis-iot) | Generic Frontend in Angular to interact with GraphQL endpoint to perform CRUD application for Sites       |


## Information
* [NIMBLE-Project Website](https://www.nimble-project.org/)
* [NIMBLE-Project GitHub Organization](https://github.com/nimble-platform)

> NIMBLE Project has received funding from the European Union's H2020 research and innovation programme under Grant Agreement No. 723810

## Development Team

- [Shantanoo Desai](mailto:des@biba.uni-bremen.de)
- [Quan Deng](mailto:dqu@biba.uni-bremen.de)
- [Stefan Wellsandt](mailto:wel@biba.uni-bremen.de)


## Scientific Papers

> Desai S., Deng Q., Wellsandt S., Thoben KD. (2019) An Architecture of IoT-Based Product Tracking with Blockchain in Multi-sided B2B Platform. In: Ameri F., Stecke K., von Cieminski G., Kiritsis D. (eds) Advances in Production Management Systems. Production Management for the Factory of the Future. APMS 2019. IFIP Advances in Information and Communication Technology, vol 566. Springer, Cham
[DOI: 10.1007/978-3-030-30000-5_57](https://doi.org/10.1007/978-3-030-30000-5_57)

## Work In Progress

Scientific Paper on the complete implementation. (Paper Accepted in Conference)