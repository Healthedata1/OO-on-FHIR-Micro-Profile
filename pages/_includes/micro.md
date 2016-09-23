####  OO-on-FHIR Microbiological Culture and Susceptability

- [Logical Model of Micro Report Structure](microsusc-logical.html)

#### Mappings:
- [Mapping to FHIR Profiles](microsusc-mappings.html#Profiles)
- [Mapping to HL7 v2 LRI IG](microsusc-mappings.html#LRI)

#### Profiles

Profile|Derived from|Core Resource
---|---|---
[MicroReport](microreport.html)|[US-Core DiagnosticReport],[USLAB DiagnosticReport]|DiagnosticReport
Organism Observation|[US-Core Observation],[USLAB Observation Panel]|Observation
[Gram Stain Observations](gscomp.html)|[US-Core Observation],[USLAB Coded Observation]|Observation
Organism Growth Observations|[US-Core Observation],[USLAB Numeric Observation]|Observation
Organism Colony Count Observations|[US-Core Observation],[USLAB Observation Panel]|Observation
Othe Micro Observations|[US-Core Observation],[USLAB Observation Panel]|Observation
Micro ABX Susceptibility Coded Observations|[US-Core Observation],[USLAB Coded Observation]|Observation
Micro ABX Susceptibility Numeric Observations|[US-Core Observation],[USLAB Numeric Observation]|Observation

