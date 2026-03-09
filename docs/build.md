# OxiOS Build Guide

## Base
Debian 13 (Trixie) Stable

## Build Tools
- live-build
- debootstrap

## Planned Build Command
lb config \
  --distribution trixie \
  --architectures amd64 \
  --binary-images iso-hybrid \
  --archive-areas "main contrib non-free non-free-firmware" \
  --debian-installer false
