# Bluefin and Aurora
**These images are managed versions of their upstream counterparts.** 

## Bluefin

[![bluefin 39](https://github.com/ublue-os/bluefin/actions/workflows/build-39-bluefin.yml/badge.svg)](https://github.com/ublue-os/bluefin/actions/workflows/build-39-bluefin.yml) [![bluefin 40](https://github.com/ublue-os/bluefin/actions/workflows/build-40-bluefin.yml/badge.svg)](https://github.com/ublue-os/bluefin/actions/workflows/build-40-bluefin.yml)

![image](https://github.com/ublue-os/bluefin/assets/1264109/b093bdec-40dc-48d2-b8ff-fcf0df390e8c)

> "Evolution is a process of constant branching and expansion." - Stephen Jay Gould

Bluefin strives to cover these two use cases. For end users it provides a system as reliable as a Chromebook with near-zero maintainance, with the power of homebrew, flathub, and a container runtime to give you access to all the best software Open Source has to offer. Check [Introduction to Bluefin](https://universal-blue.discourse.group/t/introduction-to-bluefin/41) for a feature walkthrough. 

- [Download Bluefin](https://projectbluefin.io/#scene-picker)

## Aurora

[![aurora 39](https://github.com/ublue-os/bluefin/actions/workflows/build-39-aurora.yml/badge.svg)](https://github.com/ublue-os/bluefin/actions/workflows/build-39-aurora.yml) [![aurora 40](https://github.com/ublue-os/bluefin/actions/workflows/build-40-aurora.yml/badge.svg)](https://github.com/ublue-os/bluefin/actions/workflows/build-40-aurora.yml)

![Screenshot_20240423_211805](https://github.com/ublue-os/bluefin/assets/40402114/1bea1ed8-d97a-402a-957b-e0f338d38230)

Aurora is a delightful KDE desktop experience for end-users that are looking for reliability and developers for the most-hassle free setup. Zero maintenance included.

- [Download Aurora](https://getaurora.dev)

### What's the relationship between Aurora and Bluefin?

Both Aurora and Bluefin strive to offer a curated out of the box experience for users, they only differ in the default desktop and recommended applications: Bluefin uses GNOME, Aurora uses KDE. They are both maintained and built in this repository.  

## Documentation

1. [Discussions and Announcements](https://universal-blue.discourse.group/c/bluefin/6) - strongly recommended!
2. [Administrator's Guide](https://universal-blue.discourse.group/t/bluefin-administrators-guide/40)

### Secure Boot

Secure Boot is supported by default on our systems, providing an additional layer of security. After the first installation, you will be prompted to enroll the secure boot key in the BIOS.

Enter the password `ublue-os` when prompted to enroll the mOS key.

Secure boot is supported with our custom key. The pub key can be found in this repository [here](https://github.com/APoorDev/mOS/blob/main/secure_boot.der).
If you'd like to enroll this key manually, download the key and run the following:

```bash
sudo mokutil --timeout -1
sudo mokutil --import secure_boot.der
```

#### Note

If you encounter an issue with a password being recognized as incorrect, try using the `-` key on the numpad instead.

## Repobeats

![Alt](https://repobeats.axiom.co/api/embed/40b85b252bf6ea25eb90539d1adcea013ccae69a.svg "Repobeats analytics image")

## Star History

<a href="https://star-history.com/#ublue-os/bluefin&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ublue-os/bluefin&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ublue-os/bluefin&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ublue-os/bluefin&type=Date" />
  </picture>
</a>

