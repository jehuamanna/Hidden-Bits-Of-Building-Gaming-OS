# Hidden-Bits-Of-Building-Gaming-OS
Steps to build an Gaming Operation in Linux 

# Motivation
One of the main drawbacks of gaming in Linux, especially playing multiplayer is, no native support for anti-cheats in Linux Kernel. Even if you apply kernel patches or apply kernel modules for anti-cheat, users can still recompile the kernel and play games dishonestly.

## Solution
Immutable Operating Systems. This concept is similar to how Andoid Operating System works. It has a base OS or system files which is immutable (read only). On top of that we have user applications running which cannot modify the underlying system.

To make this happen we use the concept of container in building the Operating System.

We will make use of OCI (Open Container Initative).


# Image Format Specification Of OCI

This specification defines an OCI Image, consisting of a `manifest`, an `image index` (optional), a set of `filesystem layers`, and a `configuration`.

The goal of this specification is to enable the creation of interoperable tools for building, transporting, and preparing a container image to run.
