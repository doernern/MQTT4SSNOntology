# MQTT4SSN Ontology

[![Format](https://img.shields.io/badge/Format-JSON_LD-blue.svg)](https://doernern.github.io/MQTT4SSNOntology/documentation/ontology.jsonld) [![Format](https://img.shields.io/badge/Format-RDF/XML-blue.svg)](https://doernern.github.io/MQTT4SSNOntology/documentation/ontology.owl) [![Format](https://img.shields.io/badge/Format-N_Triples-blue.svg)](https://doernern.github.io/MQTT4SSNOntology/documentation/ontology.nt) [![Format](https://img.shields.io/badge/Format-TTL-blue.svg)](https://doernern.github.io/MQTT4SSNOntology/documentation/ontology.ttl)

MQTT4SSN is an ontology representing the MQTT transport protocol, containing the transmitted data. It extends the W3C SSN/SOSA ontology with the MQTT transport protocol component and uses the WoT MQTT to RDF draft as an ontology design pattern.

## Key Features

The ontology captures the essential elements of MQTT, such as the network entities broker and client, the various control packets and their payloads, the topics that organize communication, and the interrelations between these components. The ontology covers the following key features:

* Supports main MQTT control packets: PUBLISH, SUBSCRUBE and UNSUBSCRIBE
* Enables representation of heterogeneous payload formats and character encodings
* Alignment with the well-established W3C SSN/SOSA ontology
* Models the relation between MQTT topic naming and SOSA elements such as FeatureOfInterest, Property, Actuation, ActuationCollection, Observation, and ObservationCollection

## Visualization

[![Visualize with](https://img.shields.io/badge/Visualize_with-WebVowl-blue.svg)](https://doernern.github.io/MQTT4SSNOntology/documentation/webvowl/index.html#)

<img src="./figures/ControlPacketHierarchy.png" width="50%">
<img src="./figures/NetworkInfrastructure.png" width="40%">
<img src="./figures/TopicPayload.png" width="50%">
<img src="./figures/TopicSubjects.png" width="30%">

## How to cite
Please cite the MQTT4SSN ontology as follows:

Niklas Doerner, Maria Maleshkova (2025): MQTT4SSN Ontology. https://doi.org/10.5281/zenodo.16704302

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16805970.svg)](https://doi.org/10.5281/zenodo.16704302) 

## License
All resources are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International.

[![License](https://img.shields.io/badge/License-https://creativecommons.org/licenses/by_nc_sa/4.0/-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)