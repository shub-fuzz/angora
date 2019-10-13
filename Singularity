Bootstrap: docker
From: registry.gitlab.com/rode0day/fuzzer-testing/angora_runnner:16.04

%labels
    MAINTAINER Josh Bundt
    DockerTagID 25c832b76

%environment
    AFL_SKIP_CPUFREQ=1
    LC_ALL=C
    LANG=C
    export AFL_SKIP_CPUFREQ LC_ALL LANG

%runscript
    exec /start_fuzzing "$@"

