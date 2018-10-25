# SKUL
### Exploration into enhanced LUKS key entry

## Goal
### Entering a password can be very dangerous if key loggers exist. TPMs exist on modern motherboards and enable data to be stored securely. These facts can be combined by synthesizing a user key with a TPM secured key to create a composite key to decrypt LUKS partitions. To open the TPM module, the machine-stored key can be opened with a number of alternative credentials such as Yubikey, Securecard, iris, fingerprint, etc.

## Purpose
### I don't already know how to implement this concept, but I would like to discuss the concept with others that are willing to help.

## Destination
### I would like to either create somekind of a Github gist or perhaps a package to be freely distributable and coherent enough to implement such that a intermediate Archlinux level user may install linux in a secure fashion. Alternatively, Less manual distributions, such as Fedora, could implement this concept as an automated option.
