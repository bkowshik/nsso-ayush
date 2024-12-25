# nsso-ayush


## Hyperlinks
- https://microdata.gov.in/NADA43/index.php/catalog/219/


## Dataset

Reference: `DDI-IND-MOSPI-NSSO-AYUSH22-23`

> Nesstar is a platform for data publishing, exploration, and analysis, often used for managing social science research data. Unfortunately, Nesstar does not have a direct Python SDK or library.

This dataset is published using Nesstar and the downloaded Microdata has the following files.

```bash
$ ls -lh
total 493296
-rw-rw-rw-@ 1 bkowshik  staff   237M  9 Dec 15:22 DDI-IND-MOSPI-NSSO-AYUSH22-23.Nesstar
-rw-rw-rw-@ 1 bkowshik  staff   1.0M 11 Nov 15:38 Guide to dowdload microdata.pdf
-rwxrwxrwx@ 1 bkowshik  staff   2.5M 11 Nov 15:38 NesstarExplorerInstaller.exe
```

## Apple Mac Setup

Using the following steps, I got Nesstar Explorer working on Apple MacBook Pro M2.

```bash
# Install stable version of wine.
$ brew install --cask --no-quarantine wine-stable

# Install Rosetta.
$ softwareupdate --install-rosetta --agree-to-license

# Install gstreamer.
$ brew install --cask gstreamer-development
```

Finally, open `wine-stable` from Spotlight on Mac and select the `.Nesstar` file to open in Nesstar Explorer. 🎉

_NOTE: Nesstar Explorer supports exporting the dataset in tab-delimited format._

![](images/nesstar-explorer-mac.png)
