# helpful_remainder
## Singularity 
"No space left on device"
```
root# singularity build --sandbox ubuntu_sandbox_dir docker://ubuntu
root# singularity shell --writable ubuntu_sandbox_dir
Singularity ubuntu.img:~> apt-get update
Singularity ubuntu.img:~> apt-get install my_apps
Singularity ubuntu.img:~> exit
root# singularity build ubuntu.img ubuntu_sandbox_dir
```

# Mirroring public to private repo
https://stackoverflow.com/questions/10065526/github-how-to-make-a-fork-of-public-repository-private
