# kaliton
Kali Linux (rolling) Chrome OS chroot Environment 


## What is this?

Kaliton is based/forked on [crouton](https://github.com/dnschneid/crouton) and hard stripped/recoded for the usage of an full featured Kali Linux (rolling) on your ChromeBook. Kaliton's target's, are a few of the meta-packages](https://www.kali.org/docs/general-use/metapackages/) from original kali linux.

Because kaliton uses [crouton](https://github.com/dnschneid/crouton) as base, you will finde elements
from it, many are removed and recoded.

[Kaliton](https://github.com/iptoux/kaliton) has it's own starter, called **kali**. The installer will be recalled [kaliton](https://github.com/iptoux/kaliton) in the near future. 


## Can i test it? And what targets available?

Yes but, it may be have [bugs/errors](https://github.com/iptoux/kaliton/issues). Many things are on my "todo", you can use the "_alpha_" in my [main branch](https://github.com/iptoux/kaliton).

**Currently the following targets are included:**

starting an VT-cli (original was start_cli)
- core -> kali-linux-core
- default -> kali-linux-default
- headless -> kali-linux-headless

starting (should do) xfce desktop
- desktop (xfce) -> kali-desktop-xfce

The targets **core, default, headless** coming without an desktop, so all of them start the same console/cli.


## Install/Usage

Download & install like crouton, after that you can install kali-rolling via `sudo kaliton -t default`.
You can also use the targets **core, headless, desktop**

- Download [Kaliton](https://github.com/iptoux/kaliton/raw/releases/crouton)
- Pop open a shell (Ctrl+Alt+T, type `shell` and hit enter)
- Make executable and install with `sudo install -Dt /usr/local/bin -m 755 ~/Downloads/kaliton`
- Install Kali Linux (rolling) via `sudo kaliton -t default`

---

- start kali (cli) via `sudo kali`
- start kali desktop via `sudo kali -d`

## main/dev/releases/testing branch

On **main** branch you will find any latest 'stable' version. You can install it and use all main features.
On **dev** branch you will find any latest 'working' version, with new added features.

The **releases** branch contains the latest 'stable' binary of the Kaliton installer (from main branch).
The **testing** branch is only for development tests and new ideas/concepts. **Errors/Bugs** included!