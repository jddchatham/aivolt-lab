# AI Volt Lab — dashboard

Dashboard front end for the Tang Primer 25K / ADS1115 voltmeter.
Companion to the `aivolt` launcher; adds the fingerprint DB browsing
and bitstream management (proven vs auto-ranging).

## Install

```sh
cp aivolt-lab ~/.local/bin/ && chmod +x ~/.local/bin/aivolt-lab
```

Requires the same project folder and hardware as `aivolt`:
`~/Desktop/a.i. tang engineering` (see the `aivolt` repo or BitNet4's
`aivolt/aivolt-project/`), openFPGALoader, Tang Primer 25K + ADS1115
on /dev/ttyUSB1.

## Use

```sh
aivolt-lab
```

Same 15 V safety limit as `aivolt`.
