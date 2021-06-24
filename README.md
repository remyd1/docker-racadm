# Containerized Dell RACADM client

## Why?

So I can make changes to iDRACs everywhere from my MacBook.

## Usage

docker run -it justinclayton/racadm -r <ip> -u <user> -p <pass> <command> [args...]

## Singularity Note

This Dell program needs to be run as root.

```bash
sudo singularity build racadm.sif Singularity.def
sudo singularity run racadm.sif -r <ip> -u <user> -p <pass> <command> [args...]
```
