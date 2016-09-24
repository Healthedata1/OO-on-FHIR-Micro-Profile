####  OO-on-FHIR Microbiological Culture and Susceptability

- [Logical Model of Micro Report Structure](microsusc-logical.html)

#### Mappings:
- [Mapping to FHIR Profiles](microsusc-mappings.html#Profiles)
- [Mapping to HL7 v2 LRI IG](microsusc-mappings.html#LRI)

#### Profiles

Profile|Derived from|Core Resource
---|---|---
[MicroReport](microreport.html)|[US-Core DiagnosticReport],[USLAB DiagnosticReport]|DiagnosticReport
[Gram Stain Observations](gramstain-component.html)|[US-Core Observation],[USLAB Coded Observation]|Observation
[AOE Observations](aoe-observation.html)|[US-Core Observation],[USLAB Coded Observation],[USLAB Numeric Observation]|Observation
[Other Micro Observations](other-observation.html)|[US-Core Observation],[USLAB Observation Panel]|Observation
Organism Observation|[US-Core Observation],[USLAB Observation Panel]|Observation
Organism Growth Observations|[US-Core Observation],[USLAB Numeric Observation]|Observation
Organism Colony Count Observations|[US-Core Observation],[USLAB Observation Panel]|Observation
Micro ABX Susceptibility Coded Observations|[US-Core Observation],[USLAB Coded Observation]|Observation
Micro ABX Susceptibility Numeric Observations|[US-Core Observation],[USLAB Numeric Observation]|Observation

[US-Core DiagnosticReport]: (http://hl7.org/FHIR/us/daf/2016Sep/daf-core-diagnosticreport.html)
[US-Core Observation]: (http://hl7.org/FHIR/us/daf/2016Sep/daf-core-resultobs.html)
[USLAB DiagnosticReport]: (http://hl7.org/fhir/uslab/uslab-dr.html)
[USLAB Coded Observation]:  (http://hl7.org/fhir/uslab/uslab-obsquantity.html)
[USLAB Numeric Observation]:  (http://hl7.org/fhir/uslab/uslab-obscode.html)