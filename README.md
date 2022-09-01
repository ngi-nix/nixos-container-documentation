# Nixos-Container Documentation

https://github.com/ngi-nix/ngi/issues/296

## Todo
- [ ] Improve nixos wiki page https://nixos.wiki/wiki/NixOS_Containers
- [ ] write a manpage
- [ ] add a section to the nixos documentation
- [ ] write a blog post on nixos-summer

## Why nixos containers
- [ ] Benefits of Reproducible containers
- [ ] Differences between nixos-containers and others


https://github.com/NixOS/nixpkgs/issues/10347

Implementation: https://github.com/profpatsch/nixpkgs/blob/master/pkgs/tools/virtualization/nixos-container/nixos-container.pl#L1

Example: https://github.com/NixOS/nixpkgs/blob/634141959076a8ab69ca2cca0f266852256d79ee/nixos/doc/manual/man-nixos-enter.xml

Contributing to the manual: https://github.com/NixOS/nixpkgs/blob/634141959076a8ab69ca2cca0f266852256d79ee/nixos/doc/manual/contributing-to-this-manual.chapter.md

## Subcommands

### destroy
Destroy the specified container.

- start 
- stop 
- terminate 
- status 
### update
Update a currently created container
with a new confiuration, the configuration for the container can be passed in through a number of ways.

#### flags
         --config <string>
         --config-file <path>
         --flake <flakeref>
         --nixos-path <path>



### root-login 
### run 
To run a specific container 
### show-ip
### show-host-key 
### list
List the currently configured containers and their status. 



### create
Create a new nixos container, that can be later started.
#### Flags
        --nixos-path
        --system-path 
        --config 
        --config-file
        --flake
        --ensure-unique-name
        --auto-start
        --bridge
        --port
        --host-address
        --local-address
        --config
        --config-file
        --flake
        --nixos-path 


### login 
Login to a container with the given name.

### Flags
-- help
     