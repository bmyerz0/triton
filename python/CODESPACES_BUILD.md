1. install torch 2 for cpus; do not include torchaudio/video (might need to uninstall if already there) because they conflict with 2.0 for cpu
2. clone triton
3. editable install
Note that I needed to turn down the parallelism for cmake due to likely running out of memory

