# fhir
FHIR Model w/ proposed EBMonFHIR extensions

This repository is carries the source of additions to the [FHIR R4](https://github.com/hl7/fhir) branch for 
the [EBMonFHIR project](http://wiki.hl7.org/index.php?title=EBMonFHIR).

## Build instructions
```bash
> git clone https://github.com/HL7/fhir.git
> git clone https://github.com/ebmonfhir/fhir.git delta
> cd delta
> git checkout {branch}         <-- if you want to build a branch other than master
> cd ..
> cp -R delta/ fhir/
> cd fhir
> . publish.sh 
```

