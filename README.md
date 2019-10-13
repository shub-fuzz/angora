# angora

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3640)

## Singularity image for Angora (https://github.com/AngoraFuzzer/Angora)


- usage:

```
singularity pull --name angora.sif shub://shub-fuzz/angora
```

- interactive session:
```
singularity shell angora.sif 
```

- start fuzzing
```
singularity exec angora.sif /start_fuzzing [[ -n <# instances> ]  -t ] <target_path> 
```

