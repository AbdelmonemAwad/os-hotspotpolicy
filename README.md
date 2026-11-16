<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/images/readme/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="docs/images/readme/banner-light.svg">
  <img src="docs/images/readme/banner-light.svg" alt="os-hotspotpolicy - One policy for each captive portal zone" width="100%">
</picture>

<p align="center">
  <img alt="status: planned" src="https://img.shields.io/badge/status-planned-lightgrey.svg?style=flat-square">
  <a href="https://github.com/AbdelmonemAwad/os-hotspotpolicy/actions/workflows/checks.yml"><img alt="checks on main" src="https://img.shields.io/github/actions/workflow/status/AbdelmonemAwad/os-hotspotpolicy/checks.yml?branch=main&amp;style=flat-square&amp;label=checks"></a>
  <a href="LICENSE"><img alt="licence: BSD-2-Clause" src="https://img.shields.io/badge/licence-BSD--2--Clause-blue.svg?style=flat-square"></a>
  <a href="https://github.com/AbdelmonemAwad/os-xgs-npu"><img alt="part of os-xgs-npu" src="https://img.shields.io/badge/part%20of-os--xgs--npu-9a6700.svg?style=flat-square"></a>
</p>

# Hotspot Policy for OPNsense

One policy per captive portal zone - rules, shaping and inspection - set in one place.

> **Planned - nothing here runs yet.** This repository was opened on 2026-11-16 to hold
> Hotspot Policy as a plugin of its own. No code has been written or moved into it, and there is no
> release.

## What it is to do

- a policy per zone, set on one page;
- the zone's rules, shaping and Suricata settings applied from it;
- what each zone applies, shown in one table.

## Where it fits

It is one part of the [os-xgs-npu](https://github.com/AbdelmonemAwad/os-xgs-npu) project, which puts OPNsense on Sophos XGS hardware, and works the way its other plugins do: changes by pull request, a release installed from **XGS: Updates**, its Arabic in [opnsense-arabic](https://github.com/AbdelmonemAwad/opnsense-arabic)'s catalogue.

## Licence

BSD 2-Clause - see [LICENSE](LICENSE).
