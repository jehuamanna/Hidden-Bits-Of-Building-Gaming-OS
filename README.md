# Hidden-Bits-Of-Building-Gaming-OS
Steps to build an Gaming Operating System using Linux 

# Motivation
The lack of native Linux kernel support for anti-cheat software is one of the primary disadvantages of Linux gaming, particularly multiplayer gaming. Users can still recompile the kernel and play games dishonestly even if they apply kernel patches or kernel modules for anti-cheat.

Immutable operating systems are the solution. This idea is comparable to that of the Andoid operating system. Its system files are read-only and unchangeable. Additionally, there are user apps operating that are unable to alter the underlying system.

In order to accomplish this, we built the operating system using the container concept.

OCI (Open Container Initiative) will be utilized.


# Image Format Specification Of OCI

This specification defines an OCI Image, consisting of a `manifest`, an `image index` (optional), a set of `filesystem layers`, and a `configuration`.

The goal of this specification is to enable the creation of interoperable tools for building, transporting, and preparing a container image to run.
