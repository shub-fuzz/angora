Singularity image for Angora (https://github.com/AngoraFuzzer/Angora)

[![singularity-deploy](https://github.com/shub-fuzz/angora/actions/workflows/builder.yml/badge.svg?branch=main)](https://github.com/shub-fuzz/angora/actions/workflows/builder.yml)
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3645)



- usage:

```
singularity pull --name angora.sif https://github.com/shub-fuzz/angora/releases/download/0.0.1/shub-fuzz-angora.1604.sif

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

