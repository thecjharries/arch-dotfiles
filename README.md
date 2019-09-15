# `arch-dotfiles`

So my Fedora box finally had enough and I thought starting Arch from scratch would be a brilliant idea. I spent most of this weekend relearning how to do all this stuff. It's going to take me some time to get this in a pretty form.

Also I'll have to be way more strategic if I wanna script the early stages of an Arch build.

## Execution Order

1. [general system stuff](./general-setup.yml)
2. [user config scaffolding](./config-setup.yml)
3. [package manage setup](./package-setup.yml)
4. all the other stuff in a specific order

## Things I want to eventually get around to

* https://htr3n.github.io/2018/07/faster-zsh/
* https://docs.gitignore.io/use/advanced-command-line
* https://wiki.archlinux.org/index.php/Zsh

## Things I did manually and need to automate

* Drive encryption (I repartitioned everything more than five times before I finally had a successful boot; but that's half on the next thing)
* Grub/boot config (I spend six hours trying to make this machine boot from UEFI before I finally realized all of legacy OSs are on MBR drives)
* User roles (not hard or long to do)
* Networking (I spent an hour trying to figure out dhcpcd and spent another thirty minutes trying to pull apart systemd-networkd config before I moved on)
* Terminator (pretty easy to come back around to)

## Things I'm still missing

* Polybar
* Rofi
* A complete systemd flow (Polybar's partially responsible of where I expect it to booot but basically not is set up right)
* Easy to use audio controls
* Sublime (not a big now that I got sucked into vim)
* Vagrant
* Docker
* Kubernetes

## Things I still need to build

* JetBrains config updates (pulling old things forward when something catastrophic happens)
* Most of my shell post-framework
* More drive encryption
* Better organization
* Lots of documentation so I don't forget
* Way more generators so I can script this the next time it happens
* New themes because I didn't any of the ones with me
