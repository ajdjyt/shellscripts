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


Linux:
1. update - arch based update script, using powerpill and yay

Monitoring
1. gputop - live nvidia-smi

Misc 
1. appimage-manager - script to add aliases for all appimages in ~/apps
    use by sourcing it in your rc file
2. adb-power - calls adb to emulate a power button press on the connected device

Windows
1. vmware-on.bat - turns on vmware services
2. servkill.bat - kills background processes on windows which i find unnessacry
3. hyprv - toggles the value for hyprv hypervisor in windows, also supports arguments as {off,on}
4. sounds.bat - opens the legacy sound menu for sound devices
5. valorant.bat - launches valorant
6. shares.bat - mounts shares vault and bat from proxmox

Tailscale
1. tsup - start tailscale (routes are from ajlive)

