# B45 Labs | Wayfinder – Third-Party Notices

**Last updated:** 2026-11-14
**Applies to:** B45 Labs | Wayfinder v0.0.1 (Autodesk Navisworks Manage 2026 build)

This document lists the third-party components redistributed with the
B45 Labs | Wayfinder installer and their applicable licenses.

B45 Labs' own assemblies (`B45Labs.Wayfinder.dll`, which contains the
`B45Wayfinder.Core` library) are proprietary and are not listed here. Platform
components (the Autodesk Navisworks API and the Microsoft .NET Framework) are
referenced where present on the user's machine and are **not** redistributed by
this installer. Newtonsoft.Json is used through the copy that Autodesk
Navisworks already loads and is **not** redistributed by this installer.

---

## Redistributed third-party libraries

| Component | Version | License | Source |
|---|---:|---|---|
| BouncyCastle.Cryptography (`BouncyCastle.Cryptography.dll`) | 2.5.0 | MIT | https://github.com/bcgit/bc-csharp |

BouncyCastle.Cryptography is used to verify the Ed25519 signature of the
Tips & Tricks content and of the update message before they are used. It is
redistributed in unmodified binary form.

---

## Web services used by the add-in (not redistributed)

| Service | Used for |
|---|---|
| ipwhois.app | Coarse region lookup (continent, country, region), only while "Share usage data to help improve B45 Labs" is on. See [PRIVACY.md](PRIVACY.md). |

---

## License texts

### MIT License

Applies to BouncyCastle.Cryptography.

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Copyright holder:
- BouncyCastle.Cryptography: Copyright (c) 2000-2024 The Legion of the Bouncy Castle Inc. (https://www.bouncycastle.org)

---

## Questions

For questions about licensing or third-party components in B45 Labs | Wayfinder,
contact:

- **Vendor:** B45 Labs
- **Email:** support@b45labs.com
