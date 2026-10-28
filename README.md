
# iOS 27.2 Carrier Bundles

This repo contains the Carrier Bundles currently bundled with iOS version 27.2 for the iPhone 18 Pro.
## Last Extraction Metadata

#### Last Extraction Time
`2026-10-28 08:41:56 UTC`

#### iOS Build Info

| iOS Version | iOS Build | iOS Build Timestamp |
| :-------- | :------- | :------------------ |
| 27.2 | 24B119 | 14 Oct 2026 04:06:28 UTC |

#### iOS Device Info

| Device Name | Device Identifier |
| :-------- | :------- |
| iPhone 18 Pro | iPhone19,2 |

## Folder Explanations

#### Carrier Bundles
This folder contains the Carrier Bundles specific to each carrier.

On the iOS filesystem, this folder can be found at:
```
/System/Library/Carrier Bundles/iPhone
```

These files are in Apple's binary plist format, so you will need an editor that can handle these kinds of files to view them.

[The Apple Wiki](https://theapplewiki.com/) has further information on [Carrier Bundles](https://theapplewiki.com/wiki/Carrier_Bundle).

#### Country Bundles
This folder contains the Carrier Bundles that apply to all carriers within a country.

On the iOS filesystem, this folder can be found at:
```
/System/Library/CountryBundles/iPhone/
```

These files are in Apple's binary plist format, so you will need an editor that can handle these kinds of files to view them.

## Acknowledgements
 - [blacktop/ipsw](https://github.com/blacktop/ipsw)
 - [sgan81/apfs-fuse](https://github.com/sgan81/apfs-fuse)