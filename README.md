<img src="readme/flag_of_Mumbai.png" alt="Mumbai Flag" width="500"/>

# The Bahmni Mumbai Distribution

_The Bahmni Mumbai distribution packages common configurations and metadata to use [Bahmni](https://www.bahmni.org/) in Mumbai._

-----

This repository maintains the 'distro POM' for the _Bahmni Mumbai Distribution_.

It downloads and brings in one place all artifacts needed by the distribution, simply run:
```bash
mvn clean package
```
### Target inventory:

* `bahmni_emr/`
<br/>The target version of the front-end apps that makes 'Bahmni EMR'.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/mekomsolutions/bahmni-config-mumbai)) to be consumed by Bahmni Apps.
* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/mekomsolutions/openmrs-config-mumbai)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.
