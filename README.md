<img src="readme/CHIDA_logo.png" alt="CHIDA Logo" width="500"/>

# CHIDA Hospital distribution

>The CHIDA Hospital at IDADEE serves children and adults in the community. The modern 15-bed hospital provides reliable and affordable health care for all; no patient is ever turned away due to lack of finances. On average, 78 patients visit CHIDA every day, and the 30 community health workers on staff serve an additional 200 patients.
>
><img src="readme/gradient logo.png" alt="Pittsburgh Kids Fundation Logo" width="120"/>
><br>
>https://www.pittsburghkidsfoundation.org/haiti

-----

This repository maintains the 'distro POM' for the _CHIDA distribution_.

It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `bahmni_emr/`
<br/>The target version of the front-end apps that makes 'Bahmni EMR'.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/mekomsolutions/bahmni-config-chida)) to be consumed by Bahmni Apps.
* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/mekomsolutions/openmrs-config-chida)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.
