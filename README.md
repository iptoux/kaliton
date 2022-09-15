# kaliton
Kali Linux (rolling) Chrome OS chroot Environment 


## What is this?

Kaliton is based/forked on [crouton](https://github.com/dnschneid/crouton) and hard stripped/recoded to
only use an full featured Kali Linux (rolling) on your ChromeBook.

Because kaliton uses [crouton](https://github.com/dnschneid/crouton) as base, you will finde many elements
from it, many are removed and recoded.

## Can i test it?

Yes but, i may be have bugs/errors.

## Install/Usage

Download&install like crouton, after that you can install kali-rolling via `sudo crouton -t headless`.
You can also use the targets **core, default, desktop**

The targets **core, default, headless** coming without an desktop, so all of them start the same console/cli

- start kali (cli) via `sudo kali`
- start kali desktop via `sudo kali -d`

## main/dev branch

On **dev** branch i do activly push test/beta commits, so please only
use the **main** branch for test/usage.