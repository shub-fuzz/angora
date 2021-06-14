Singularity image for Angora (https://github.com/AngoraFuzzer/Angora)

[![singularity-deploy](https://github.com/shub-fuzz/angora/actions/workflows/builder.yml/badge.svg?branch=main)](https://github.com/shub-fuzz/angora/actions/workflows/builder.yml)
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3645)

- __What__ is [Singularity](https://sylabs.io/singularity/)??  
  A containerization system primarily used by the scientific community on high-performance computing (HPC).
  On many University HPC systems, docker is not allowed, but singularity is availble because it runs with 
  user level permisions.  
- __Why__?  
  Fuzzing on HPC!  
  Universities have trememdous resources available in HPC clusters that can be used to support 
  large-scale fuzzing evaluations.



- usage:

```
singularity pull --name angora.sif https://github.com/shub-fuzz/angora/releases/download/0.0.2/shub-fuzz-angora.1604.sif

singularity shell angora.sif
```

- interactive session:
```
singularity shell angora.sif 
```

- start fuzzing
```
singularity exec angora.sif /start_fuzzing [[ -n <# instances> ]  -t ] <target_path> 
```

