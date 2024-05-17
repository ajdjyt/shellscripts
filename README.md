# Shell scripts

This repo contains scripts i use on linux systems, 


nvedit will auto populate docker directory ~/docker with the following structure

```sh
docker
├── containers
└── volumes
```
and if in wsl

```sh
/mnt
├── d
│   └── docker
│       ├── containers
│       └── volumes
```

Docker helping scripts:
1. up - up compose
2. down - down compose
3. logs - logs of compose or con name
4. reup - down compose and up again
5. nvedit - edit config in nvim
6. concd - cd to container directory 
7. nvenv - edit env file for container
8. editn - edit config in nano
9. conrm - delete all containers of given image
10. execute - run arg2 in con arg1
11. editc - legacy edit file i left in because i forget i moved to better naming scheme 
12. editnv - same as editc
13. start - start con arg2 in compose arg1

Monitoring
1. gputop - live nvidia-smi

Misc 
1. appimage-manager - script to add aliases for all appimages in ~/apps
    use by sourcing it in your rc file

Tailscale
1. tsup - start tailscale (routes are from ajlive)

