# Orbit VM

A responsive Indonesian-friendly dashboard interface for managing a virtual-machine workspace. The VM cards and resource values are intentionally marked as unconfigured: this repository contains a front-end website, not a hypervisor or Windows image, so it does not pretend to run a real Windows 10 VM.

## Run locally

Open `index.html` in a browser, or serve this directory with any static web server.

## To run real virtual machines

A real deployment needs an actual virtualization host (for example, Proxmox VE or a libvirt/KVM server), a secure server-side API that communicates with the host, available compute/storage/network resources, and properly licensed installation media. The browser must not contain hypervisor credentials. Connect the UI to that backend before exposing create/start/console actions as operational.

The current controls provide honest setup guidance and the tools/search/navigation are front-end interactions only; no VM is created, started, or billed.
