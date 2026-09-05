# Release provenance

Public desktop binaries in this repository are built from the minimal Electron desktop shell that was validated in the private product repository.

- Product ID: `kr.or.incheonacademy.unionos`
- Version: `1.0.0`
- Validated private source head: `1eaedfad2534dc7e81005f7ad8ffb5c986a86dd9`
- Production merge containing the validated shell: `a10776c1b2dcb3ad72e4ddbf25432598e986eb19`
- Production origin: `https://incheon-academy-union-os-web.vercel.app`

The public repository contains only the minimal desktop wrapper and release automation required to reproduce the installers. The private web application, database schema/data, credentials, server-side business logic, and private CI configuration are not published here.

## Compatibility channels

- Windows modern: Electron 44.2.0 / Windows 10·11 x64
- Windows Legacy: Electron 22.3.27 / Windows 7·8·8.1 x64 compatibility
- macOS modern: Electron 44.2.0 / macOS 13+ Universal
- macOS Mojave: Electron 26.6.10 / macOS 10.14.6 Intel x64

Legacy channels are compatibility channels. They are not security-equivalent to supported modern operating systems.
