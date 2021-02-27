<div align="center" id="top">
  <img src="./.github/app.gif" alt="MP logo" />

  &#xa0;

<!-- <a href="https://mpdocs.netlify.app">Demo</a> -->
</div>

# MPOS - System Architecture

## 💻 Workstation

We maintain GNU/UNIX-like and Windows 10 configurations.

We try to stay away from GUI apps, and overly complicated window managers. Just some frilly toothpicks for your sandwich. Less is more.

* [mp-Workstation](magrathea-gnu-x64.md) - GNU/Linux x64 Based
* [mp-Workstation-Win](magrathea-win-x64.md) - Supports Windows 10 x64 Home Edition and up

## 🖥️ HA Server Cluster

The cluster hardware can be any old hardware or a shiny new penny.
The MagicPuddle started on a single Lenovo laptop the screen was barely attached, we have since upgraded to some more modern hardware.
You can also use RaspberryPi to make an 'OctaPi' or 'DecaPi' cluster.

### 💻️ Workstation

You can connect a scalable amount of workstations to each cluster and node.
See [SSH](ssh/ssh.md) for more information.

### Linux Clustering

* BlackPearl  - Cluster Head - MPOS
* BigRed      - Node 0 - MPOS
* DeathStar   - Node 1 - MPOS

### 📱 Android with Termux Clustering

* Galaxy Head - Node 2
  * Galaxy 0
  * Galaxy 1
  * Galaxy 2
  * Galaxy 3

* *Legacy Head* - Node 3
  * Legacy 0
  * Legacy 1

## 📦 System Packages

The following packages come preinstalled on all versions except for 'bare-bones' versions and/or where otherwise stated.

### PKG list

### Magic Puddle Base PKGs

* base
* base-devel
* wget
* curl
* vim

&#xa0;

&#xa0;

<div align="center" id="top">
  <a href="#top">Back to top</a>

---

Made with ❤️ + ☕ + 🥪 By: [MeatShifter](https://github.com/meatshifter) \
for the [MagicPuddle](magicpuddle.netlify.com)
</div>
