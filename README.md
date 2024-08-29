<p align="center">
  <img src="https://github.com/tobhe/rpki-client-snap/blob/candidate/rpki-icon.png" alt="rpki-client logo" />
</p>

# rpki-client snap package

<a href="https://snapcraft.io/rpki-client"><img src="https://snapcraft.io/rpki-client/badge.svg" alt="Snap Status"></a>
<a href="https://github.com/tobhe/rpki-client-snap/actions/workflows/main.yml"><img src="https://github.com/tobhe/rpki-client-snap/actions/workflows/main.yml/badge.svg"></a>

**A free, easy-to-use implementation of RPKI**

rpki-client is a FREE, easy-to-use implementation of the Resource Public Key Infrastructure (RPKI) for Relying Parties (RP) to facilitate validation of BGP announcements. The program queries the global RPKI repository system and validates untrusted network inputs. The program outputs validated ROA payloads and BGPsec Router keys in configuration formats suitable for OpenBGPD and BIRD, or in CSV or JSON format for consumption by other routing stacks.

This snap installs a service that runs hourly and by default outputs validated payloads in OpenBGPD compatible format to `/var/snap/rpki-client/common/out`.

## Installation

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/rpki-client)

or simply:

```
snap install rpki-client
```
