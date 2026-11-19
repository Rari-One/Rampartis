# Rampartis — Third-Party Notices

**Product:** Rampartis 1.0.0 for Windows x64  
**Publisher:** Rari.One  
**Notice scope:** Third-party components identified for Rampartis 1.0.0 for Windows x64.

Rampartis is proprietary freeware. Its own use and redistribution permissions are described in [Rampartis Licensing](LICENSE.md) and the [Rampartis Software Terms](EULA.md). The components listed here belong to their respective authors and are subject to their own licenses. Those licenses apply to the covered components and are not replaced by the Rampartis Software Terms.

The dependency inventory was generated from the Windows x64 Rust dependency graph and npm lockfile, not from an extraction of the signed installer. A dependency marked *shipped* below was classified as a runtime dependency by that inventory; this does not establish that every such package contributes bytes to the final binary. The source audit identified no GPL or LGPL components in that graph.

## MPL-2.0 components and source availability

The following components were identified as runtime dependencies under the Mozilla Public License 2.0. The archives linked below are the published crate archives for those exact versions, unmodified from the crates.io registry.

| Component | Version | Source archive |
| --- | --- | --- |
| `cssparser` | 0.37.0 | [Download source](https://static.crates.io/crates/cssparser/cssparser-0.37.0.crate) |
| `dtoa-short` | 0.3.5 | [Download source](https://static.crates.io/crates/dtoa-short/dtoa-short-0.3.5.crate) |
| `option-ext` | 0.2.0 | [Download source](https://static.crates.io/crates/option-ext/option-ext-0.2.0.crate) |
| `selectors` | 0.38.0 | [Download source](https://static.crates.io/crates/selectors/selectors-0.38.0.crate) |

The MPL-covered source is available in the versioned archives above under MPL-2.0. The license text is at [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/). This availability statement concerns only those third-party components, **not** Rampartis's proprietary source code. Recipients retain the rights granted by MPL-2.0 to those components.

**Source-availability verification (completed November 18, 2026, from the distributed crate archives):** the `cssparser` 0.37.0, `dtoa-short` 0.3.5, and `option-ext` 0.2.0 archives each contain a `LICENSE` file carrying the full MPL-2.0 text, and each archive contains the corresponding complete source. The `selectors` 0.38.0 archive contains no `LICENSE` file; its package metadata declares `license = "MPL-2.0"` and its upstream repository is https://github.com/servo/stylo (`selectors/` directory), which carries no `LICENSE` file at the paths checked. The full MPL-2.0 text is therefore reproduced in Appendix A of this document, and the covered source remains available at the versioned archive above and at the upstream repository.

## Other third-party license information

The component table below records package-level SPDX license expressions from the audited inventory. Where a package offers alternative licenses (`OR`), that expression identifies available alternatives; it is not itself an election of a particular license. Where multiple licenses apply together (`AND`), the applicable obligations must be satisfied together.

The applicable full license texts are reproduced in Appendix A of this document, and the per-package copyright attributions for the exact distributed versions are listed in Appendix B. The links in the table below identify the corresponding published packages; they are pointers, not a substitute for the notices in the appendices.

Key license references:
- [MIT](https://spdx.org/licenses/MIT.html)
- [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [BSD 3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [ISC](https://spdx.org/licenses/ISC.html)
- [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
- [Unicode License v3](https://opensource.org/license/unicode-3.0)
- [zlib](https://spdx.org/licenses/Zlib.html)
- [Unlicense](https://unlicense.org/)
- [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
- [0BSD](https://spdx.org/licenses/0BSD.html)

### Unicode-3.0 components

The following audited runtime packages have a `Unicode-3.0` obligation in their recorded license expression:

- `icu_collections` 2.3.0 — `Unicode-3.0`
- `icu_locale_core` 2.3.0 — `Unicode-3.0`
- `icu_normalizer` 2.3.0 — `Unicode-3.0`
- `icu_normalizer_data` 2.3.0 — `Unicode-3.0`
- `icu_properties` 2.3.0 — `Unicode-3.0`
- `icu_properties_data` 2.3.0 — `Unicode-3.0`
- `icu_provider` 2.3.1 — `Unicode-3.0`
- `litemap` 0.8.3 — `Unicode-3.0`
- `potential_utf` 0.1.6 — `Unicode-3.0`
- `tinystr` 0.8.4 — `Unicode-3.0`
- `unicode-ident` 1.0.27 — `(MIT OR Apache-2.0) AND Unicode-3.0`
- `writeable` 0.6.4 — `Unicode-3.0`
- `yoke` 0.8.3 — `Unicode-3.0`
- `zerofrom` 0.1.8 — `Unicode-3.0`
- `zerotrie` 0.2.5 — `Unicode-3.0`
- `zerovec` 0.11.8 — `Unicode-3.0`

The Unicode License v3 requires its copyright and permission notice to accompany copies or associated documentation. The notice below is the text as it appears in the ICU4X packages' `LICENSE` files (verified in `icu_normalizer` 2.3.0), including `Copyright © 2020-2024 Unicode, Inc.` `unicode-ident` 1.0.27 carries the same license terms with the copyright line `Copyright © 1991-2023 Unicode, Inc.`, which is also recorded in Appendix B. The other Unicode-3.0 packages listed above carry the 2020-2024 notice:

```
UNICODE LICENSE V3

COPYRIGHT AND PERMISSION NOTICE

Copyright © 2020-2024 Unicode, Inc.

NOTICE TO USER: Carefully read the following legal agreement. BY
DOWNLOADING, INSTALLING, COPYING OR OTHERWISE USING DATA FILES, AND/OR
SOFTWARE, YOU UNEQUIVOCALLY ACCEPT, AND AGREE TO BE BOUND BY, ALL OF THE
TERMS AND CONDITIONS OF THIS AGREEMENT. IF YOU DO NOT AGREE, DO NOT
DOWNLOAD, INSTALL, COPY, DISTRIBUTE OR USE THE DATA FILES OR SOFTWARE.

Permission is hereby granted, free of charge, to any person obtaining a
copy of data files and any associated documentation (the "Data Files") or
software and any associated documentation (the "Software") to deal in the
Data Files or Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, and/or sell
copies of the Data Files or Software, and to permit persons to whom the
Data Files or Software are furnished to do so, provided that either (a)
this copyright and permission notice appear with all copies of the Data
Files or Software, or (b) this copyright and permission notice appear in
associated Documentation.

THE DATA FILES AND SOFTWARE ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY
KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF
THIRD PARTY RIGHTS.

IN NO EVENT SHALL THE COPYRIGHT HOLDER OR HOLDERS INCLUDED IN THIS NOTICE
BE LIABLE FOR ANY CLAIM, OR ANY SPECIAL INDIRECT OR CONSEQUENTIAL DAMAGES,
OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS,
WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION,
ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THE DATA
FILES OR SOFTWARE.

Except as contained in this notice, the name of a copyright holder shall
not be used in advertising or otherwise to promote the sale, use or other
dealings in these Data Files or Software without prior written
authorization of the copyright holder.

SPDX-License-Identifier: Unicode-3.0
```

### `ring` 0.17.14

`ring` 0.17.14 is recorded as `Apache-2.0 AND ISC`. The audited package includes a crate-root `LICENSE` (a roadmap to the other files), `LICENSE-BoringSSL` (Apache-2.0), `LICENSE-other-bits` (ISC), and `third_party/fiat/LICENSE` (an Apache-2.0 header for fiat-crypto). Their contents, as distributed in the audited archive:

`LICENSE` (crate root):
```
*ring* uses an "ISC" license, like BoringSSL used to use, for new code
files. See LICENSE-other-bits for the text of that license.

See LICENSE-BoringSSL for code that was sourced from BoringSSL under the
Apache 2.0 license. Some code that was sourced from BoringSSL under the ISC
license. In each case, the license info is at the top of the file.

See src/polyfill/once_cell/LICENSE-APACHE and src/polyfill/once_cell/LICENSE-MIT
for the license to code that was sourced from the once_cell project.
```

`third_party/fiat/LICENSE`:
```
The Apache License, Version 2.0 (Apache-2.0)

Copyright 2015-2020 the fiat-crypto authors (see the AUTHORS file)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

`LICENSE-other-bits`:
```
Copyright 2015-2025 Brian Smith.

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION
OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.```

`LICENSE-BoringSSL` reproduces the Apache License 2.0 in full; that text is reproduced in Appendix A. The historical OpenSSL advertising clause was not identified as applicable to this version. Code sourced from the once_cell project, under `src/polyfill/once_cell/`, is licensed MIT OR Apache-2.0; those license texts are reproduced in Appendix A.

### Installer and bundled components

- **NSIS (Nullsoft Scriptable Install System) 3.11:** The locked Tauri CLI 2.12.2 bundler downloads NSIS 3.11 (`crates/tauri-bundler/src/bundle/windows/nsis/mod.rs` at tag `tauri-cli-v2.12.2`). The audited `tauri.conf.json` does not set `bundle.windows.nsis.compression`, so the default compressor applies: LZMA (`NsisCompression::Lzma` is `#[default]` in `tauri-utils` 2.10.1). Per the NSIS 3.11 `COPYING` file (https://github.com/kichik/nsis/blob/v311/COPYING):
  - NSIS source, plug-ins, documentation, examples, header files and graphics, with the exception of the compression modules and where otherwise noted, are licensed under the zlib/libpng license. Copyright (C) 1999-2025 Contributors. The zlib license text is reproduced in Appendix A.
  - The LZMA compression module for NSIS is licensed under the Common Public License version 1.0. The full CPL-1.0 text, as included in that `COPYING` file, is reproduced in Appendix A. Recipients may obtain the corresponding source for that module from the NSIS 3.11 sources (https://github.com/kichik/nsis/tree/v311) or from the NSIS project at https://nsis.sourceforge.io/. This availability statement concerns only that third-party module, not Rampartis's proprietary source. NSIS 3.11 `COPYING` also includes the following special exception:

    > Igor Pavlov and Amir Szekely, the authors of the LZMA compression module for NSIS, expressly permit you to statically or dynamically link your code (or bind by name) to the files from the LZMA compression module for NSIS without subjecting your linked code to the terms of the Common Public license version 1.0. Any modifications or additions to files from the LZMA compression module for NSIS, however, are subject to the terms of the Common Public License version 1.0.

  The same bundler source lists the plugins it packages (`NSIS_PLUGIN_FILES`): `NSISdl.dll`, `StartMenu.dll`, `System.dll`, and `nsDialogs.dll` (stock NSIS plugins, under the zlib/libpng license except where NSIS `COPYING` notes otherwise), and `nsis_tauri_utils.dll` version 0.5.3. The `nsis-tauri-utils` workspace at tag `nsis_tauri_utils-v0.5.3` declares `license = "MIT or Apache-2.0"`; its `LICENSE_MIT` file carries `Copyright (c) 2019 - 2022 Tauri Programme within The Commons Conservancy`. The MIT and Apache-2.0 texts are reproduced in Appendix A. The plugin and version list above is taken from the reviewed source of what was packed (the locked Tauri CLI 2.12.2 bundler).
- **Microsoft Edge WebView2 Evergreen Bootstrapper:** included with the installer configuration (`embedBootstrapper` per the Tauri bundle settings). If the runtime is absent, installation may download it from Microsoft. Microsoft software terms apply; see the WebView2 documentation at https://developer.microsoft.com/en-us/microsoft-edge/webview2/ and https://learn.microsoft.com/en-us/microsoft-edge/webview2/. The precise redistributable terms ship with the runtime. The packaged configuration is as reviewed in the source (`tauri.conf.json`: WebView2 embedBootstrapper).
- **Microsoft Visual C++ runtime:** app-local runtime components are configured for redistribution (`bundleVCRuntime` per the Tauri bundle settings). Microsoft's applicable redistributable terms apply; see https://learn.microsoft.com/en-us/cpp/windows/redistributing-visual-cpp-files. The packaged configuration is as reviewed in the source (`tauri.conf.json`: `bundleVCRuntime`).
- **SQLite amalgamation:** SQLite is public domain; the Rust `rusqlite`/`libsqlite3-sys` wrappers have their own licenses as listed below.
- **Rampartis artwork and installer hooks:** first-party Rari.One material, not third-party open-source components.
- **Segoe UI/system-ui:** a system font reference, not a font redistributed with Rampartis.

## Audited runtime dependency inventory

The table below lists the runtime-classified third-party Rust and npm dependencies identified for Rampartis 1.0.0, excluding build-only and development-only dependencies: **266 packages (264 Rust, 2 npm)**. Version and license expressions reflect the release dependency inventory; source links identify the corresponding published packages. First-party application components are not included.

| Ecosystem | Component | Version | License expression | Package source |
| --- | --- | --- | --- | --- |
| cargo | `adler2` | `2.0.1` | `0BSD OR MIT OR Apache-2.0` | [Source](https://crates.io/crates/adler2/2.0.1) |
| cargo | `aho-corasick` | `1.1.5` | `Unlicense OR MIT` | [Source](https://crates.io/crates/aho-corasick/1.1.5) |
| cargo | `alloc-no-stdlib` | `3.0.0` | `BSD-3-Clause` | [Source](https://crates.io/crates/alloc-no-stdlib/3.0.0) |
| cargo | `alloc-stdlib` | `0.3.0` | `BSD-3-Clause` | [Source](https://crates.io/crates/alloc-stdlib/0.3.0) |
| cargo | `anyhow` | `1.0.104` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/anyhow/1.0.104) |
| cargo | `arrayvec` | `0.7.8` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/arrayvec/0.7.8) |
| cargo | `atomic-waker` | `1.1.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/atomic-waker/1.1.2) |
| cargo | `base64` | `0.23.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/base64/0.23.1) |
| cargo | `bit-set` | `0.8.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/bit-set/0.8.0) |
| cargo | `bit-vec` | `0.8.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/bit-vec/0.8.0) |
| cargo | `bitflags` | `1.3.2` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/bitflags/1.3.2) |
| cargo | `bitflags` | `2.13.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/bitflags/2.13.2) |
| cargo | `blake3` | `1.8.7` | `CC0-1.0 OR Apache-2.0 OR Apache-2.0 WITH LLVM-exception` | [Source](https://crates.io/crates/blake3/1.8.7) |
| cargo | `block-buffer` | `0.10.4` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/block-buffer/0.10.4) |
| cargo | `brotli` | `9.0.0` | `BSD-3-Clause AND MIT` | [Source](https://crates.io/crates/brotli/9.0.0) |
| cargo | `brotli-decompressor` | `6.0.1` | `BSD-3-Clause/MIT` | [Source](https://crates.io/crates/brotli-decompressor/6.0.1) |
| cargo | `bs58` | `0.5.1` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/bs58/0.5.1) |
| cargo | `byteorder` | `1.5.0` | `Unlicense OR MIT` | [Source](https://crates.io/crates/byteorder/1.5.0) |
| cargo | `bytes` | `1.12.1` | `MIT` | [Source](https://crates.io/crates/bytes/1.12.1) |
| cargo | `camino` | `1.2.6` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/camino/1.2.6) |
| cargo | `cargo-platform` | `0.1.9` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/cargo-platform/0.1.9) |
| cargo | `cargo_metadata` | `0.19.2` | `MIT` | [Source](https://crates.io/crates/cargo_metadata/0.19.2) |
| cargo | `cfb` | `0.14.0` | `MIT` | [Source](https://crates.io/crates/cfb/0.14.0) |
| cargo | `cfg-if` | `1.0.5` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/cfg-if/1.0.5) |
| cargo | `chrono` | `0.4.45` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/chrono/0.4.45) |
| cargo | `constant_time_eq` | `0.4.2` | `CC0-1.0 OR MIT-0 OR Apache-2.0` | [Source](https://crates.io/crates/constant_time_eq/0.4.2) |
| cargo | `constant_time_eq` | `0.6.1` | `CC0-1.0 OR MIT-0 OR Apache-2.0` | [Source](https://crates.io/crates/constant_time_eq/0.6.1) |
| cargo | `cookie` | `0.18.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/cookie/0.18.2) |
| cargo | `cpufeatures` | `0.2.17` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/cpufeatures/0.2.17) |
| cargo | `cpufeatures` | `0.3.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/cpufeatures/0.3.1) |
| cargo | `crc32fast` | `1.5.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/crc32fast/1.5.2) |
| cargo | `crossbeam-channel` | `0.5.17` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/crossbeam-channel/0.5.17) |
| cargo | `crossbeam-utils` | `0.8.23` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/crossbeam-utils/0.8.23) |
| cargo | `crypto-common` | `0.1.7` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/crypto-common/0.1.7) |
| cargo | `cssparser` | `0.37.0` | `MPL-2.0` | [Source](https://crates.io/crates/cssparser/0.37.0) |
| cargo | `ctor` | `1.0.13` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/ctor/1.0.13) |
| cargo | `darling` | `0.24.1` | `MIT` | [Source](https://crates.io/crates/darling/0.24.1) |
| cargo | `darling_core` | `0.24.1` | `MIT` | [Source](https://crates.io/crates/darling_core/0.24.1) |
| cargo | `defmt` | `1.1.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/defmt/1.1.1) |
| cargo | `defmt-parser` | `1.0.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/defmt-parser/1.0.0) |
| cargo | `deranged` | `0.5.8` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/deranged/0.5.8) |
| cargo | `derive_more` | `2.1.1` | `MIT` | [Source](https://crates.io/crates/derive_more/2.1.1) |
| cargo | `digest` | `0.10.7` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/digest/0.10.7) |
| cargo | `dirs` | `7.0.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/dirs/7.0.0) |
| cargo | `dirs-sys` | `0.5.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/dirs-sys/0.5.0) |
| cargo | `dom_query` | `0.28.0` | `MIT` | [Source](https://crates.io/crates/dom_query/0.28.0) |
| cargo | `dpi` | `0.1.2` | `Apache-2.0 AND MIT` | [Source](https://crates.io/crates/dpi/0.1.2) |
| cargo | `dtoa` | `1.0.11` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/dtoa/1.0.11) |
| cargo | `dtoa-short` | `0.3.5` | `MPL-2.0` | [Source](https://crates.io/crates/dtoa-short/0.3.5) |
| cargo | `dunce` | `1.0.5` | `CC0-1.0 OR MIT-0 OR Apache-2.0` | [Source](https://crates.io/crates/dunce/1.0.5) |
| cargo | `dyn-clone` | `1.0.20` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/dyn-clone/1.0.20) |
| cargo | `equivalent` | `1.0.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/equivalent/1.0.2) |
| cargo | `erased-serde` | `0.4.10` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/erased-serde/0.4.10) |
| cargo | `fallible-iterator` | `0.3.0` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/fallible-iterator/0.3.0) |
| cargo | `fallible-streaming-iterator` | `0.1.9` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/fallible-streaming-iterator/0.1.9) |
| cargo | `fastrand` | `2.5.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/fastrand/2.5.0) |
| cargo | `fdeflate` | `0.3.7` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/fdeflate/0.3.7) |
| cargo | `flate2` | `1.1.10` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/flate2/1.1.10) |
| cargo | `fnv` | `1.0.7` | `Apache-2.0 / MIT` | [Source](https://crates.io/crates/fnv/1.0.7) |
| cargo | `foldhash` | `0.2.0` | `Zlib` | [Source](https://crates.io/crates/foldhash/0.2.0) |
| cargo | `form_urlencoded` | `1.2.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/form_urlencoded/1.2.2) |
| cargo | `fs2` | `0.4.3` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/fs2/0.4.3) |
| cargo | `futures-channel` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-channel/0.3.34) |
| cargo | `futures-core` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-core/0.3.34) |
| cargo | `futures-io` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-io/0.3.34) |
| cargo | `futures-sink` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-sink/0.3.34) |
| cargo | `futures-task` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-task/0.3.34) |
| cargo | `futures-util` | `0.3.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/futures-util/0.3.34) |
| cargo | `generic-array` | `0.14.7` | `MIT` | [Source](https://crates.io/crates/generic-array/0.14.7) |
| cargo | `getrandom` | `0.2.17` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/getrandom/0.2.17) |
| cargo | `getrandom` | `0.3.4` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/getrandom/0.3.4) |
| cargo | `getrandom` | `0.4.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/getrandom/0.4.3) |
| cargo | `glob` | `0.3.4` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/glob/0.3.4) |
| cargo | `hashbrown` | `0.12.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/hashbrown/0.12.3) |
| cargo | `hashbrown` | `0.17.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/hashbrown/0.17.1) |
| cargo | `hashlink` | `0.12.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/hashlink/0.12.2) |
| cargo | `heck` | `0.5.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/heck/0.5.0) |
| cargo | `hex` | `0.4.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/hex/0.4.3) |
| cargo | `html5ever` | `0.39.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/html5ever/0.39.0) |
| cargo | `http` | `1.5.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/http/1.5.0) |
| cargo | `http-body` | `1.1.0` | `MIT` | [Source](https://crates.io/crates/http-body/1.1.0) |
| cargo | `http-body-util` | `0.1.5` | `MIT` | [Source](https://crates.io/crates/http-body-util/0.1.5) |
| cargo | `httparse` | `1.10.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/httparse/1.10.1) |
| cargo | `hyper` | `1.12.0` | `MIT` | [Source](https://crates.io/crates/hyper/1.12.0) |
| cargo | `hyper-rustls` | `0.27.10` | `Apache-2.0 OR ISC OR MIT` | [Source](https://crates.io/crates/hyper-rustls/0.27.10) |
| cargo | `hyper-util` | `0.1.21` | `MIT` | [Source](https://crates.io/crates/hyper-util/0.1.21) |
| cargo | `ico` | `0.5.0` | `MIT` | [Source](https://crates.io/crates/ico/0.5.0) |
| cargo | `icu_collections` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_collections/2.3.0) |
| cargo | `icu_locale_core` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_locale_core/2.3.0) |
| cargo | `icu_normalizer` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_normalizer/2.3.0) |
| cargo | `icu_normalizer_data` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_normalizer_data/2.3.0) |
| cargo | `icu_properties` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_properties/2.3.0) |
| cargo | `icu_properties_data` | `2.3.0` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_properties_data/2.3.0) |
| cargo | `icu_provider` | `2.3.1` | `Unicode-3.0` | [Source](https://crates.io/crates/icu_provider/2.3.1) |
| cargo | `ident_case` | `1.0.1` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/ident_case/1.0.1) |
| cargo | `idna` | `1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/idna/1.1.0) |
| cargo | `idna_adapter` | `1.2.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/idna_adapter/1.2.2) |
| cargo | `indexmap` | `1.9.3` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/indexmap/1.9.3) |
| cargo | `indexmap` | `2.14.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/indexmap/2.14.2) |
| cargo | `infer` | `0.22.0` | `MIT` | [Source](https://crates.io/crates/infer/0.22.0) |
| cargo | `ipnet` | `2.12.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/ipnet/2.12.2) |
| cargo | `itoa` | `1.0.18` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/itoa/1.0.18) |
| cargo | `jiff` | `0.2.38` | `Unlicense OR MIT` | [Source](https://crates.io/crates/jiff/0.2.38) |
| cargo | `jiff-core` | `0.1.1` | `Unlicense OR MIT` | [Source](https://crates.io/crates/jiff-core/0.1.1) |
| cargo | `jiff-tzdb` | `0.1.9` | `Unlicense OR MIT` | [Source](https://crates.io/crates/jiff-tzdb/0.1.9) |
| cargo | `jiff-tzdb-platform` | `0.1.3` | `Unlicense OR MIT` | [Source](https://crates.io/crates/jiff-tzdb-platform/0.1.3) |
| cargo | `json-patch` | `4.2.0` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/json-patch/4.2.0) |
| cargo | `jsonptr` | `0.7.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/jsonptr/0.7.1) |
| cargo | `keyboard-types` | `0.8.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/keyboard-types/0.8.3) |
| cargo | `libc` | `0.2.190` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/libc/0.2.190) |
| cargo | `libsqlite3-sys` | `0.39.1` | `MIT` | [Source](https://crates.io/crates/libsqlite3-sys/0.39.1) |
| cargo | `litemap` | `0.8.3` | `Unicode-3.0` | [Source](https://crates.io/crates/litemap/0.8.3) |
| cargo | `lock_api` | `0.4.14` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/lock_api/0.4.14) |
| cargo | `log` | `0.4.34` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/log/0.4.34) |
| cargo | `markup5ever` | `0.39.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/markup5ever/0.39.0) |
| cargo | `memchr` | `2.8.3` | `Unlicense OR MIT` | [Source](https://crates.io/crates/memchr/2.8.3) |
| cargo | `mime` | `0.3.17` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/mime/0.3.17) |
| cargo | `minisign-verify` | `0.3.0` | `MIT` | [Source](https://crates.io/crates/minisign-verify/0.3.0) |
| cargo | `miniz_oxide` | `0.8.9` | `MIT OR Zlib OR Apache-2.0` | [Source](https://crates.io/crates/miniz_oxide/0.8.9) |
| cargo | `miniz_oxide` | `0.9.1` | `MIT OR Zlib OR Apache-2.0` | [Source](https://crates.io/crates/miniz_oxide/0.9.1) |
| cargo | `mio` | `1.2.4` | `MIT` | [Source](https://crates.io/crates/mio/1.2.4) |
| cargo | `muda` | `0.20.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/muda/0.20.0) |
| cargo | `new_debug_unreachable` | `1.0.6` | `MIT` | [Source](https://crates.io/crates/new_debug_unreachable/1.0.6) |
| cargo | `num-conv` | `0.2.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/num-conv/0.2.2) |
| cargo | `num-traits` | `0.2.19` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/num-traits/0.2.19) |
| cargo | `once_cell` | `1.21.4` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/once_cell/1.21.4) |
| cargo | `option-ext` | `0.2.0` | `MPL-2.0` | [Source](https://crates.io/crates/option-ext/0.2.0) |
| cargo | `parking_lot` | `0.12.5` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/parking_lot/0.12.5) |
| cargo | `parking_lot_core` | `0.9.12` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/parking_lot_core/0.9.12) |
| cargo | `percent-encoding` | `2.3.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/percent-encoding/2.3.2) |
| cargo | `phf` | `0.13.1` | `MIT` | [Source](https://crates.io/crates/phf/0.13.1) |
| cargo | `phf_generator` | `0.13.1` | `MIT` | [Source](https://crates.io/crates/phf_generator/0.13.1) |
| cargo | `phf_shared` | `0.13.1` | `MIT` | [Source](https://crates.io/crates/phf_shared/0.13.1) |
| cargo | `pin-project-lite` | `0.2.17` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/pin-project-lite/0.2.17) |
| cargo | `plist` | `1.10.1` | `MIT` | [Source](https://crates.io/crates/plist/1.10.1) |
| cargo | `png` | `0.17.16` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/png/0.17.16) |
| cargo | `png` | `0.18.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/png/0.18.1) |
| cargo | `potential_utf` | `0.1.6` | `Unicode-3.0` | [Source](https://crates.io/crates/potential_utf/0.1.6) |
| cargo | `powerfmt` | `0.2.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/powerfmt/0.2.1) |
| cargo | `precomputed-hash` | `0.1.1` | `MIT` | [Source](https://crates.io/crates/precomputed-hash/0.1.1) |
| cargo | `proc-macro2` | `1.0.107` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/proc-macro2/1.0.107) |
| cargo | `quick-xml` | `0.42.0` | `MIT` | [Source](https://crates.io/crates/quick-xml/0.42.0) |
| cargo | `quote` | `1.0.47` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/quote/1.0.47) |
| cargo | `raw-window-handle` | `0.6.2` | `MIT OR Apache-2.0 OR Zlib` | [Source](https://crates.io/crates/raw-window-handle/0.6.2) |
| cargo | `ref-cast` | `1.0.27` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/ref-cast/1.0.27) |
| cargo | `regex` | `1.13.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/regex/1.13.1) |
| cargo | `regex-automata` | `0.4.18` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/regex-automata/0.4.18) |
| cargo | `regex-syntax` | `0.8.11` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/regex-syntax/0.8.11) |
| cargo | `reqwest` | `0.13.5` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/reqwest/0.13.5) |
| cargo | `rfd` | `0.16.0` | `MIT` | [Source](https://crates.io/crates/rfd/0.16.0) |
| cargo | `ring` | `0.17.14` | `Apache-2.0 AND ISC` | [Source](https://crates.io/crates/ring/0.17.14) |
| cargo | `rusqlite` | `0.41.0` | `MIT` | [Source](https://crates.io/crates/rusqlite/0.41.0) |
| cargo | `rustc-hash` | `2.1.3` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/rustc-hash/2.1.3) |
| cargo | `rustls` | `0.23.46` | `Apache-2.0 OR ISC OR MIT` | [Source](https://crates.io/crates/rustls/0.23.46) |
| cargo | `rustls-pki-types` | `1.16.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/rustls-pki-types/1.16.0) |
| cargo | `rustls-platform-verifier` | `0.7.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/rustls-platform-verifier/0.7.1) |
| cargo | `rustls-webpki` | `0.103.17` | `ISC` | [Source](https://crates.io/crates/rustls-webpki/0.103.17) |
| cargo | `same-file` | `1.0.6` | `Unlicense/MIT` | [Source](https://crates.io/crates/same-file/1.0.6) |
| cargo | `schemars` | `0.8.22` | `MIT` | [Source](https://crates.io/crates/schemars/0.8.22) |
| cargo | `schemars` | `0.9.0` | `MIT` | [Source](https://crates.io/crates/schemars/0.9.0) |
| cargo | `schemars` | `1.2.2` | `MIT` | [Source](https://crates.io/crates/schemars/1.2.2) |
| cargo | `scopeguard` | `1.2.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/scopeguard/1.2.0) |
| cargo | `selectors` | `0.38.0` | `MPL-2.0` | [Source](https://crates.io/crates/selectors/0.38.0) |
| cargo | `semver` | `1.0.28` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/semver/1.0.28) |
| cargo | `serde` | `1.0.229` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde/1.0.229) |
| cargo | `serde-untagged` | `0.1.9` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde-untagged/0.1.9) |
| cargo | `serde_core` | `1.0.229` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde_core/1.0.229) |
| cargo | `serde_derive_internals` | `0.29.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde_derive_internals/0.29.1) |
| cargo | `serde_json` | `1.0.154` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde_json/1.0.154) |
| cargo | `serde_spanned` | `1.1.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde_spanned/1.1.2) |
| cargo | `serde_with` | `3.24.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serde_with/3.24.0) |
| cargo | `serialize-to-javascript` | `0.1.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/serialize-to-javascript/0.1.2) |
| cargo | `servo_arc` | `0.4.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/servo_arc/0.4.3) |
| cargo | `sha2` | `0.10.9` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/sha2/0.10.9) |
| cargo | `simd-adler32` | `0.3.10` | `MIT` | [Source](https://crates.io/crates/simd-adler32/0.3.10) |
| cargo | `siphasher` | `1.0.4` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/siphasher/1.0.4) |
| cargo | `slab` | `0.4.12` | `MIT` | [Source](https://crates.io/crates/slab/0.4.12) |
| cargo | `smallvec` | `1.16.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/smallvec/1.16.3) |
| cargo | `socket2` | `0.6.5` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/socket2/0.6.5) |
| cargo | `softbuffer` | `0.4.8` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/softbuffer/0.4.8) |
| cargo | `stable_deref_trait` | `1.2.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/stable_deref_trait/1.2.1) |
| cargo | `string_cache` | `0.9.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/string_cache/0.9.0) |
| cargo | `strsim` | `0.11.1` | `MIT` | [Source](https://crates.io/crates/strsim/0.11.1) |
| cargo | `subtle` | `2.6.1` | `BSD-3-Clause` | [Source](https://crates.io/crates/subtle/2.6.1) |
| cargo | `syn` | `2.0.119` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/syn/2.0.119) |
| cargo | `syn` | `3.0.8` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/syn/3.0.8) |
| cargo | `sync_wrapper` | `1.0.2` | `Apache-2.0` | [Source](https://crates.io/crates/sync_wrapper/1.0.2) |
| cargo | `synstructure` | `0.14.0` | `MIT` | [Source](https://crates.io/crates/synstructure/0.14.0) |
| cargo | `tao` | `0.37.1` | `Apache-2.0` | [Source](https://crates.io/crates/tao/0.37.1) |
| cargo | `tauri` | `2.12.3` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri/2.12.3) |
| cargo | `tauri-codegen` | `2.7.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-codegen/2.7.2) |
| cargo | `tauri-plugin-dialog` | `2.8.2` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-plugin-dialog/2.8.2) |
| cargo | `tauri-plugin-fs` | `2.7.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-plugin-fs/2.7.0) |
| cargo | `tauri-plugin-updater` | `2.14.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-plugin-updater/2.14.1) |
| cargo | `tauri-runtime` | `2.12.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-runtime/2.12.1) |
| cargo | `tauri-runtime-wry` | `2.12.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-runtime-wry/2.12.1) |
| cargo | `tauri-utils` | `2.10.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tauri-utils/2.10.1) |
| cargo | `tempfile` | `3.27.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/tempfile/3.27.0) |
| cargo | `tendril` | `0.5.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/tendril/0.5.1) |
| cargo | `thiserror` | `2.0.21` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/thiserror/2.0.21) |
| cargo | `time` | `0.3.55` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/time/0.3.55) |
| cargo | `time-core` | `0.1.9` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/time-core/0.1.9) |
| cargo | `tinystr` | `0.8.4` | `Unicode-3.0` | [Source](https://crates.io/crates/tinystr/0.8.4) |
| cargo | `tinyvec` | `1.13.3` | `Zlib OR Apache-2.0 OR MIT` | [Source](https://crates.io/crates/tinyvec/1.13.3) |
| cargo | `tokio` | `1.53.2` | `MIT` | [Source](https://crates.io/crates/tokio/1.53.2) |
| cargo | `tokio-rustls` | `0.26.6` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/tokio-rustls/0.26.6) |
| cargo | `tokio-util` | `0.7.20` | `MIT` | [Source](https://crates.io/crates/tokio-util/0.7.20) |
| cargo | `toml` | `1.1.8+spec-1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/toml/1.1.8+spec-1.1.0) |
| cargo | `toml_datetime` | `1.1.2+spec-1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/toml_datetime/1.1.2+spec-1.1.0) |
| cargo | `toml_parser` | `1.1.5+spec-1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/toml_parser/1.1.5+spec-1.1.0) |
| cargo | `toml_writer` | `1.1.3+spec-1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/toml_writer/1.1.3+spec-1.1.0) |
| cargo | `tower` | `0.5.3` | `MIT` | [Source](https://crates.io/crates/tower/0.5.3) |
| cargo | `tower-http` | `0.6.11` | `MIT` | [Source](https://crates.io/crates/tower-http/0.6.11) |
| cargo | `tower-layer` | `0.3.3` | `MIT` | [Source](https://crates.io/crates/tower-layer/0.3.3) |
| cargo | `tower-service` | `0.3.3` | `MIT` | [Source](https://crates.io/crates/tower-service/0.3.3) |
| cargo | `tracing` | `0.1.44` | `MIT` | [Source](https://crates.io/crates/tracing/0.1.44) |
| cargo | `tracing-core` | `0.1.36` | `MIT` | [Source](https://crates.io/crates/tracing-core/0.1.36) |
| cargo | `tray-icon` | `0.25.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/tray-icon/0.25.1) |
| cargo | `try-lock` | `0.2.5` | `MIT` | [Source](https://crates.io/crates/try-lock/0.2.5) |
| cargo | `typed-path` | `0.13.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/typed-path/0.13.0) |
| cargo | `typeid` | `1.0.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/typeid/1.0.3) |
| cargo | `typenum` | `1.20.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/typenum/1.20.1) |
| cargo | `unicode-ident` | `1.0.27` | `(MIT OR Apache-2.0) AND Unicode-3.0` | [Source](https://crates.io/crates/unicode-ident/1.0.27) |
| cargo | `unicode-segmentation` | `1.13.3` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/unicode-segmentation/1.13.3) |
| cargo | `untrusted` | `0.9.0` | `ISC` | [Source](https://crates.io/crates/untrusted/0.9.0) |
| cargo | `url` | `2.5.8` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/url/2.5.8) |
| cargo | `urlpattern` | `0.6.0` | `MIT` | [Source](https://crates.io/crates/urlpattern/0.6.0) |
| cargo | `utf8_iter` | `1.0.4` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/utf8_iter/1.0.4) |
| cargo | `uuid` | `1.28.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/uuid/1.28.0) |
| cargo | `walkdir` | `2.5.0` | `Unlicense/MIT` | [Source](https://crates.io/crates/walkdir/2.5.0) |
| cargo | `want` | `0.3.2` | `MIT` | [Source](https://crates.io/crates/want/0.3.2) |
| cargo | `web-time` | `1.1.0` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/web-time/1.1.0) |
| cargo | `web_atoms` | `0.2.6` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/web_atoms/0.2.6) |
| cargo | `webview2-com` | `0.39.1` | `MIT` | [Source](https://crates.io/crates/webview2-com/0.39.1) |
| cargo | `webview2-com-sys` | `0.39.1` | `MIT` | [Source](https://crates.io/crates/webview2-com-sys/0.39.1) |
| cargo | `winapi` | `0.3.9` | `MIT/Apache-2.0` | [Source](https://crates.io/crates/winapi/0.3.9) |
| cargo | `winapi-util` | `0.1.11` | `Unlicense OR MIT` | [Source](https://crates.io/crates/winapi-util/0.1.11) |
| cargo | `window-vibrancy` | `0.8.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/window-vibrancy/0.8.1) |
| cargo | `windows` | `0.62.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows/0.62.2) |
| cargo | `windows-collections` | `0.3.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-collections/0.3.2) |
| cargo | `windows-core` | `0.62.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-core/0.62.2) |
| cargo | `windows-future` | `0.3.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-future/0.3.2) |
| cargo | `windows-link` | `0.2.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-link/0.2.1) |
| cargo | `windows-numerics` | `0.3.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-numerics/0.3.1) |
| cargo | `windows-registry` | `0.6.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-registry/0.6.1) |
| cargo | `windows-result` | `0.4.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-result/0.4.1) |
| cargo | `windows-strings` | `0.5.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-strings/0.5.1) |
| cargo | `windows-sys` | `0.60.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-sys/0.60.2) |
| cargo | `windows-sys` | `0.61.2` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-sys/0.61.2) |
| cargo | `windows-targets` | `0.53.5` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-targets/0.53.5) |
| cargo | `windows-threading` | `0.2.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-threading/0.2.1) |
| cargo | `windows-version` | `0.1.7` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows-version/0.1.7) |
| cargo | `windows_x86_64_msvc` | `0.53.1` | `MIT OR Apache-2.0` | [Source](https://crates.io/crates/windows_x86_64_msvc/0.53.1) |
| cargo | `winnow` | `1.0.4` | `MIT` | [Source](https://crates.io/crates/winnow/1.0.4) |
| cargo | `writeable` | `0.6.4` | `Unicode-3.0` | [Source](https://crates.io/crates/writeable/0.6.4) |
| cargo | `wry` | `0.57.0` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/wry/0.57.0) |
| cargo | `yoke` | `0.8.3` | `Unicode-3.0` | [Source](https://crates.io/crates/yoke/0.8.3) |
| cargo | `zerofrom` | `0.1.8` | `Unicode-3.0` | [Source](https://crates.io/crates/zerofrom/0.1.8) |
| cargo | `zeroize` | `1.9.1` | `Apache-2.0 OR MIT` | [Source](https://crates.io/crates/zeroize/1.9.1) |
| cargo | `zerotrie` | `0.2.5` | `Unicode-3.0` | [Source](https://crates.io/crates/zerotrie/0.2.5) |
| cargo | `zerovec` | `0.11.8` | `Unicode-3.0` | [Source](https://crates.io/crates/zerovec/0.11.8) |
| cargo | `zip` | `9.6.0` | `MIT` | [Source](https://crates.io/crates/zip/9.6.0) |
| cargo | `zlib-rs` | `0.6.8` | `Zlib` | [Source](https://crates.io/crates/zlib-rs/0.6.8) |
| cargo | `zmij` | `1.0.23` | `MIT` | [Source](https://crates.io/crates/zmij/1.0.23) |
| npm | `@tauri-apps/api` | `2.12.3` | `Apache-2.0 OR MIT` | [Source](https://www.npmjs.com/package/@tauri-apps%2Fapi/v/2.12.3) |
| npm | `@tauri-apps/plugin-dialog` | `2.8.2` | `MIT OR Apache-2.0` | [Source](https://www.npmjs.com/package/@tauri-apps%2Fplugin-dialog/v/2.8.2) |

## Dependency inventory scope

The inventory lists runtime-classified third-party dependencies from the Windows x64 dependency graph and lockfiles. Build-only and development-only packages are excluded from the table unless otherwise identified as redistributed components.

Third-party components retain their respective license rights. This document does not license Rampartis's proprietary source code.

For licensing questions or requests concerning third-party component source, see [Support](SUPPORT.md).

---

## Appendix A — License texts

The full texts of the licenses that apply to the components listed above. Where a license text below shows a placeholder for the copyright holder, the holder for each package is given in Appendix B. The Unicode License v3 text is reproduced in full in the Unicode-3.0 section above rather than repeated here.

### MIT License

```
MIT License

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### Apache License 2.0

```
Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

"License" shall mean the terms and conditions for use, reproduction, and distribution as defined by Sections 1 through 9 of this document.

"Licensor" shall mean the copyright owner or entity authorized by the copyright owner that is granting the License.

"Legal Entity" shall mean the union of the acting entity and all other entities that control, are controlled by, or are under common control with that entity. For the purposes of this definition, "control" means (i) the power, direct or indirect, to cause the direction or management of such entity, whether by contract or otherwise, or (ii) ownership of fifty percent (50%) or more of the outstanding shares, or (iii) beneficial ownership of such entity.

"You" (or "Your") shall mean an individual or Legal Entity exercising permissions granted by this License.

"Source" form shall mean the preferred form for making modifications, including but not limited to software source code, documentation source, and configuration files.

"Object" form shall mean any form resulting from mechanical transformation or translation of a Source form, including but not limited to compiled object code, generated documentation, and conversions to other media types.

"Work" shall mean the work of authorship, whether in Source or Object form, made available under the License, as indicated by a copyright notice that is included in or attached to the work (an example is provided in the Appendix below).

"Derivative Works" shall mean any work, whether in Source or Object form, that is based on (or derived from) the Work and for which the editorial revisions, annotations, elaborations, or other modifications represent, as a whole, an original work of authorship. For the purposes of this License, Derivative Works shall not include works that remain separable from, or merely link (or bind by name) to the interfaces of, the Work and Derivative Works thereof.

"Contribution" shall mean any work of authorship, including the original version of the Work and any modifications or additions to that Work or Derivative Works thereof, that is intentionally submitted to Licensor for inclusion in the Work by the copyright owner or by an individual or Legal Entity authorized to submit on behalf of the copyright owner. For the purposes of this definition, "submitted" means any form of electronic, verbal, or written communication sent to the Licensor or its representatives, including but not limited to communication on electronic mailing lists, source code control systems, and issue tracking systems that are managed by, or on behalf of, the Licensor for the purpose of discussing and improving the Work, but excluding communication that is conspicuously marked or otherwise designated in writing by the copyright owner as "Not a Contribution."

"Contributor" shall mean Licensor and any individual or Legal Entity on behalf of whom a Contribution has been received by Licensor and subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable copyright license to reproduce, prepare Derivative Works of, publicly display, publicly perform, sublicense, and distribute the Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in this section) patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work, where such license applies only to those patent claims licensable by such Contributor that are necessarily infringed by their Contribution(s) alone or by combination of their Contribution(s) with the Work to which such Contribution(s) was submitted. If You institute patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Work or a Contribution incorporated within the Work constitutes direct or contributory patent infringement, then any patent licenses granted to You under this License for that Work shall terminate as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the Work or Derivative Works thereof in any medium, with or without modifications, and in Source or Object form, provided that You meet the following conditions:

     (a) You must give any other recipients of the Work or Derivative Works a copy of this License; and

     (b) You must cause any modified files to carry prominent notices stating that You changed the files; and

     (c) You must retain, in the Source form of any Derivative Works that You distribute, all copyright, patent, trademark, and attribution notices from the Source form of the Work, excluding those notices that do not pertain to any part of the Derivative Works; and

     (d) If the Work includes a "NOTICE" text file as part of its distribution, then any Derivative Works that You distribute must include a readable copy of the attribution notices contained within such NOTICE file, excluding those notices that do not pertain to any part of the Derivative Works, in at least one of the following places: within a NOTICE text file distributed as part of the Derivative Works; within the Source form or documentation, if provided along with the Derivative Works; or, within a display generated by the Derivative Works, if and wherever such third-party notices normally appear. The contents of the NOTICE file are for informational purposes only and do not modify the License. You may add Your own attribution notices within Derivative Works that You distribute, alongside or as an addendum to the NOTICE text from the Work, provided that such additional attribution notices cannot be construed as modifying the License.

     You may add Your own copyright statement to Your modifications and may provide additional or different license terms and conditions for use, reproduction, or distribution of Your modifications, or for any such Derivative Works as a whole, provided Your use, reproduction, and distribution of the Work otherwise complies with the conditions stated in this License.

5. Submission of Contributions. Unless You explicitly state otherwise, any Contribution intentionally submitted for inclusion in the Work by You to the Licensor shall be under the terms and conditions of this License, without any additional terms or conditions. Notwithstanding the above, nothing herein shall supersede or modify the terms of any separate license agreement you may have executed with Licensor regarding such Contributions.

6. Trademarks. This License does not grant permission to use the trade names, trademarks, service marks, or product names of the Licensor, except as required for reasonable and customary use in describing the origin of the Work and reproducing the content of the NOTICE file.

7. Disclaimer of Warranty. Unless required by applicable law or agreed to in writing, Licensor provides the Work (and each Contributor provides its Contributions) on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the appropriateness of using or redistributing the Work and assume any risks associated with Your exercise of permissions under this License.

8. Limitation of Liability. In no event and under no legal theory, whether in tort (including negligence), contract, or otherwise, unless required by applicable law (such as deliberate and grossly negligent acts) or agreed to in writing, shall any Contributor be liable to You for damages, including any direct, indirect, special, incidental, or consequential damages of any character arising as a result of this License or out of the use or inability to use the Work (including but not limited to damages for loss of goodwill, work stoppage, computer failure or malfunction, or any and all other commercial damages or losses), even if such Contributor has been advised of the possibility of such damages.

9. Accepting Warranty or Additional Liability. While redistributing the Work or Derivative Works thereof, You may choose to offer, and charge a fee for, acceptance of support, warranty, indemnity, or other liability obligations and/or rights consistent with this License. However, in accepting such obligations, You may act only on Your own behalf and on Your sole responsibility, not on behalf of any other Contributor, and only if You agree to indemnify, defend, and hold each Contributor harmless for any liability incurred by, or claims asserted against, such Contributor by reason of your accepting any such warranty or additional liability.

END OF TERMS AND CONDITIONS

APPENDIX: How to apply the Apache License to your work.

To apply the Apache License to your work, attach the following boilerplate notice, with the fields enclosed by brackets "[]" replaced with your own identifying information. (Don't include the brackets!)  The text should be enclosed in the appropriate comment syntax for the file format. We also recommend that a file or class name and description of purpose be included on the same "printed page" as the copyright notice for easier identification within third-party archives.

Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### BSD 3-Clause License

The copyright holder for each BSD-3-Clause package is recorded in Appendix B.

```
Copyright (c) <year> <copyright holders>

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### ISC License

```
ISC License:

Copyright (c) 2004-2010 by Internet Systems Consortium, Inc. ("ISC")
Copyright (c) 1995-2003 by Internet Software Consortium

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND ISC DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL ISC BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

### Mozilla Public License 2.0

```
Mozilla Public License Version 2.0 

1. Definitions

     1.1. "Contributor" means each individual or legal entity that creates, contributes to the creation of, or owns Covered Software.

     1.2. "Contributor Version" means the combination of the Contributions of others (if any) used by a Contributor and that particular Contributor's Contribution.

     1.3. "Contribution" means Covered Software of a particular Contributor.

     1.4. "Covered Software" means Source Code Form to which the initial Contributor has attached the notice in Exhibit A, the Executable Form of such Source Code Form, and Modifications of such Source Code Form, in each case including portions thereof.

     1.5. "Incompatible With Secondary Licenses" means

          (a) that the initial Contributor has attached the notice described in Exhibit B to the Covered Software; or

          (b) that the Covered Software was made available under the terms of version 1.1 or earlier of the License, but not also under the terms of a Secondary License.

     1.6. "Executable Form" means any form of the work other than Source Code Form.

     1.7. "Larger Work" means a work that combines Covered Software with other material, in a separate file or files, that is not Covered Software.

     1.8. "License" means this document.

     1.9. "Licensable" means having the right to grant, to the maximum extent possible, whether at the time of the initial grant or subsequently, any and all of the rights conveyed by this License.

     1.10. "Modifications" means any of the following:

          (a) any file in Source Code Form that results from an addition to, deletion from, or modification of the contents of Covered Software; or

          (b) any new file in Source Code Form that contains any Covered Software.

     1.11. "Patent Claims" of a Contributor means any patent claim(s), including without limitation, method, process, and apparatus claims, in any patent Licensable by such Contributor that would be infringed, but for the grant of the License, by the making, using, selling, offering for sale, having made, import, or transfer of either its Contributions or its Contributor Version.

     1.12. "Secondary License" means either the GNU General Public License, Version 2.0, the GNU Lesser General Public License, Version 2.1, the GNU Affero General Public License, Version 3.0, or any later versions of those licenses.

     1.13. "Source Code Form" means the form of the work preferred for making modifications.

     1.14. "You" (or "Your") means an individual or a legal entity exercising rights under this License. For legal entities, "You" includes any entity that controls, is controlled by, or is under common control with You. For purposes of this definition, "control" means (a) the power, direct or indirect, to cause the direction or management of such entity, whether by contract or otherwise, or (b) ownership of more than fifty percent (50%) of the outstanding shares or beneficial ownership of such entity.

2. License Grants and Conditions 

     2.1. Grants
     Each Contributor hereby grants You a world-wide, royalty-free, non-exclusive license:

          (a) under intellectual property rights (other than patent or trademark) Licensable by such Contributor to use, reproduce, make available, modify, display, perform, distribute, and otherwise exploit its Contributions, either on an unmodified basis, with Modifications, or as part of a Larger Work; and

          (b) under Patent Claims of such Contributor to make, use, sell, offer for sale, have made, import, and otherwise transfer either its Contributions or its Contributor Version.

     2.2. Effective Date
     The licenses granted in Section 2.1 with respect to any Contribution become effective for each Contribution on the date the Contributor first distributes such Contribution.

     2.3. Limitations on Grant Scope
     The licenses granted in this Section 2 are the only rights granted under this License. No additional rights or licenses will be implied from the distribution or licensing of Covered Software under this License. Notwithstanding Section 2.1(b) above, no patent license is granted by a Contributor:

          (a) for any code that a Contributor has removed from Covered Software; or

          (b) for infringements caused by: (i) Your and any other third party's modifications of Covered Software, or (ii) the combination of its Contributions with other software (except as part of its Contributor Version); or

          (c) under Patent Claims infringed by Covered Software in the absence of its Contributions.

     This License does not grant any rights in the trademarks, service marks, or logos of any Contributor (except as may be necessary to comply with the notice requirements in Section 3.4).

     2.4. Subsequent Licenses
     No Contributor makes additional grants as a result of Your choice to distribute the Covered Software under a subsequent version of this License (see Section 10.2) or under the terms of a Secondary License (if permitted under the terms of Section 3.3).

     2.5. Representation
     Each Contributor represents that the Contributor believes its Contributions are its original creation(s) or it has sufficient rights to grant the rights to its Contributions conveyed by this License.

     2.6. Fair Use
     This License is not intended to limit any rights You have under applicable copyright doctrines of fair use, fair dealing, or other equivalents.

     2.7. Conditions
     Sections 3.1, 3.2, 3.3, and 3.4 are conditions of the licenses granted in Section 2.1.

3. Responsibilities

     3.1. Distribution of Source Form
     All distribution of Covered Software in Source Code Form, including any Modifications that You create or to which You contribute, must be under the terms of this License. You must inform recipients that the Source Code Form of the Covered Software is governed by the terms of this License, and how they can obtain a copy of this License. You may not attempt to alter or restrict the recipients' rights in the Source Code Form.

     3.2. Distribution of Executable Form
     If You distribute Covered Software in Executable Form then:

          (a) such Covered Software must also be made available in Source Code Form, as described in Section 3.1, and You must inform recipients of the Executable Form how they can obtain a copy of such Source Code Form by reasonable means in a timely manner, at a charge no more than the cost of distribution to the recipient; and

          (b) You may distribute such Executable Form under the terms of this License, or sublicense it under different terms, provided that the license for the Executable Form does not attempt to limit or alter the recipients' rights in the Source Code Form under this License.

     3.3. Distribution of a Larger Work
     You may create and distribute a Larger Work under terms of Your choice, provided that You also comply with the requirements of this License for the Covered Software. If the Larger Work is a combination of Covered Software with a work governed by one or more Secondary Licenses, and the Covered Software is not Incompatible With Secondary Licenses, this License permits You to additionally distribute such Covered Software under the terms of such Secondary License(s), so that the recipient of the Larger Work may, at their option, further distribute the Covered Software under the terms of either this License or such Secondary License(s).

     3.4. Notices
     You may not remove or alter the substance of any license notices (including copyright notices, patent notices, disclaimers of warranty, or limitations of liability) contained within the Source Code Form of the Covered Software, except that You may alter any license notices to the extent required to remedy known factual inaccuracies.
 
     3.5. Application of Additional Terms
     You may choose to offer, and to charge a fee for, warranty, support, indemnity or liability obligations to one or more recipients of Covered Software. However, You may do so only on Your own behalf, and not on behalf of any Contributor. You must make it absolutely clear that any such warranty, support, indemnity, or liability obligation is offered by You alone, and You hereby agree to indemnify every Contributor for any liability incurred by such Contributor as a result of warranty, support, indemnity or liability terms You offer. You may include additional disclaimers of warranty and limitations of liability specific to any jurisdiction.

4. Inability to Comply Due to Statute or Regulation 
If it is impossible for You to comply with any of the terms of this License with respect to some or all of the Covered Software due to statute, judicial order, or regulation then You must: (a) comply with the terms of this License to the maximum extent possible; and (b) describe the limitations and the code they affect. Such description must be placed in a text file included with all distributions of the Covered Software under this License. Except to the extent prohibited by statute or regulation, such description must be sufficiently detailed for a recipient of ordinary skill to be able to understand it.

5. Termination 

     5.1. The rights granted under this License will terminate automatically if You fail to comply with any of its terms. However, if You become compliant, then the rights granted under this License from a particular Contributor are reinstated (a) provisionally, unless and until such Contributor explicitly and finally terminates Your grants, and (b) on an ongoing basis, if such Contributor fails to notify You of the non-compliance by some reasonable means prior to 60 days after You have come back into compliance. Moreover, Your grants from a particular Contributor are reinstated on an ongoing basis if such Contributor notifies You of the non-compliance by some reasonable means, this is the first time You have received notice of non-compliance with this License from such Contributor, and You become compliant prior to 30 days after Your receipt of the notice.

     5.2. If You initiate litigation against any entity by asserting a patent infringement claim (excluding declaratory judgment actions, counter-claims, and cross-claims) alleging that a Contributor Version directly or indirectly infringes any patent, then the rights granted to You by any and all Contributors for the Covered Software under Section 2.1 of this License shall terminate.

     5.3. In the event of termination under Sections 5.1 or 5.2 above, all end user license agreements (excluding distributors and resellers) which have been validly granted by You or Your distributors under this License prior to termination shall survive termination.

6. Disclaimer of Warranty 
Covered Software is provided under this License on an "as is" basis, without warranty of any kind, either expressed, implied, or statutory, including, without limitation, warranties that the Covered Software is free of defects, merchantable, fit for a particular purpose or non-infringing. The entire risk as to the quality and performance of the Covered Software is with You. Should any Covered Software prove defective in any respect, You (not any Contributor) assume the cost of any necessary servicing, repair, or correction. This disclaimer of warranty constitutes an essential part of this License. No use of any Covered Software is authorized under this License except under this disclaimer. 

7. Limitation of Liability 
Under no circumstances and under no legal theory, whether tort (including negligence), contract, or otherwise, shall any Contributor, or anyone who distributes Covered Software as permitted above, be liable to You for any direct, indirect, special, incidental, or consequential damages of any character including, without limitation, damages for lost profits, loss of goodwill, work stoppage, computer failure or malfunction, or any and all other commercial damages or losses, even if such party shall have been informed of the possibility of such damages. This limitation of liability shall not apply to liability for death or personal injury resulting from such party's negligence to the extent applicable law prohibits such limitation. Some jurisdictions do not allow the exclusion or limitation of incidental or consequential damages, so this exclusion and limitation may not apply to You. 

8. Litigation 
Any litigation relating to this License may be brought only in the courts of a jurisdiction where the defendant maintains its principal place of business and such litigation shall be governed by laws of that jurisdiction, without reference to its conflict-of-law provisions. Nothing in this Section shall prevent a party's ability to bring cross-claims or counter-claims.

9. Miscellaneous 
This License represents the complete agreement concerning the subject matter hereof. If any provision of this License is held to be unenforceable, such provision shall be reformed only to the extent necessary to make it enforceable. Any law or regulation which provides that the language of a contract shall be construed against the drafter shall not be used to construe this License against a Contributor.

10. Versions of the License 

     10.1. New Versions
     Mozilla Foundation is the license steward. Except as provided in Section 10.3, no one other than the license steward has the right to modify or publish new versions of this License. Each version will be given a distinguishing version number.

     10.2. Effect of New Versions
     You may distribute the Covered Software under the terms of the version of the License under which You originally received the Covered Software, or under the terms of any subsequent version published by the license steward.

     10.3. Modified Versions
     If you create software not governed by this License, and you want to create a new license for such software, you may create and use a modified version of this License if you rename the license and remove any references to the name of the license steward (except to note that such modified license differs from this License).

     10.4. Distributing Source Code Form that is Incompatible With Secondary Licenses
     If You choose to distribute Source Code Form that is Incompatible With Secondary Licenses under the terms of this version of the License, the notice described in Exhibit B of this License must be attached.

Exhibit A - Source Code Form License Notice 

     This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at http://mozilla.org/MPL/2.0/.

If it is not possible or desirable to put the notice in a particular file, then You may include the notice in a location (such as a LICENSE file in a relevant directory) where a recipient would be likely to look for such a notice.

You may add additional accurate notices of copyright ownership.

Exhibit B - "Incompatible With Secondary Licenses" Notice 

     This Source Code Form is "Incompatible With Secondary Licenses", as defined by the Mozilla Public License, v. 2.0.
```

### zlib License

```
zlib License

This software is provided 'as-is', without any express or implied warranty.  In no event will the authors be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:

     1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.
  
     2. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.
  
     3. This notice may not be removed or altered from any source distribution.
```

### The Unlicense

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>
```
### Creative Commons CC0 1.0 Universal

```
Creative Commons CC0 1.0 Universal

<<beginOptional;name=ccOptionalIntro>> CREATIVE COMMONS CORPORATION IS NOT A LAW FIRM AND DOES NOT PROVIDE LEGAL SERVICES. DISTRIBUTION OF THIS DOCUMENT DOES NOT CREATE AN ATTORNEY-CLIENT RELATIONSHIP. CREATIVE COMMONS PROVIDES THIS INFORMATION ON AN "AS-IS" BASIS. CREATIVE COMMONS MAKES NO WARRANTIES REGARDING THE USE OF THIS DOCUMENT OR THE INFORMATION OR WORKS PROVIDED HEREUNDER, AND DISCLAIMS LIABILITY FOR DAMAGES RESULTING FROM THE USE OF THIS DOCUMENT OR THE INFORMATION OR WORKS PROVIDED HEREUNDER.  <<endOptional>>

Statement of Purpose

The laws of most jurisdictions throughout the world automatically confer exclusive Copyright and Related Rights (defined below) upon the creator and subsequent owner(s) (each and all, an "owner") of an original work of authorship and/or a database (each, a "Work").

Certain owners wish to permanently relinquish those rights to a Work for the purpose of contributing to a commons of creative, cultural and scientific works ("Commons") that the public can reliably and without fear of later claims of infringement build upon, modify, incorporate in other works, reuse and redistribute as freely as possible in any form whatsoever and for any purposes, including without limitation commercial purposes. These owners may contribute to the Commons to promote the ideal of a free culture and the further production of creative, cultural and scientific works, or to gain reputation or greater distribution for their Work in part through the use and efforts of others.

For these and/or other purposes and motivations, and without any expectation of additional consideration or compensation, the person associating CC0 with a Work (the "Affirmer"), to the extent that he or she is an owner of Copyright and Related Rights in the Work, voluntarily elects to apply CC0 to the Work and publicly distribute the Work under its terms, with knowledge of his or her Copyright and Related Rights in the Work and the meaning and intended legal effect of CC0 on those rights.

1. Copyright and Related Rights. A Work made available under CC0 may be protected by copyright and related or neighboring rights ("Copyright and Related Rights"). Copyright and Related Rights include, but are not limited to, the following:

     i. the right to reproduce, adapt, distribute, perform, display, communicate, and translate a Work;

     ii. moral rights retained by the original author(s) and/or performer(s);

     iii. publicity and privacy rights pertaining to a person's image or likeness depicted in a Work;

     iv. rights protecting against unfair competition in regards to a Work, subject to the limitations in paragraph 4(a), below;

     v. rights protecting the extraction, dissemination, use and reuse of data in a Work;

     vi. database rights (such as those arising under Directive 96/9/EC of the European Parliament and of the Council of 11 March 1996 on the legal protection of databases, and under any national implementation thereof, including any amended or successor version of such directive); and

     vii. other similar, equivalent or corresponding rights throughout the world based on applicable law or treaty, and any national implementations thereof.

2. Waiver. To the greatest extent permitted by, but not in contravention of, applicable law, Affirmer hereby overtly, fully, permanently, irrevocably and unconditionally waives, abandons, and surrenders all of Affirmer's Copyright and Related Rights and associated claims and causes of action, whether now known or unknown (including existing as well as future claims and causes of action), in the Work (i) in all territories worldwide, (ii) for the maximum duration provided by applicable law or treaty (including future time extensions), (iii) in any current or future medium and for any number of copies, and (iv) for any purpose whatsoever, including without limitation commercial, advertising or promotional purposes (the "Waiver"). Affirmer makes the Waiver for the benefit of each member of the public at large and to the detriment of Affirmer's heirs and successors, fully intending that such Waiver shall not be subject to revocation, rescission, cancellation, termination, or any other legal or equitable action to disrupt the quiet enjoyment of the Work by the public as contemplated by Affirmer's express Statement of Purpose.

3. Public License Fallback. Should any part of the Waiver for any reason be judged legally invalid or ineffective under applicable law, then the Waiver shall be preserved to the maximum extent permitted taking into account Affirmer's express Statement of Purpose. In addition, to the extent the Waiver is so judged Affirmer hereby grants to each affected person a royalty-free, non transferable, non sublicensable, non exclusive, irrevocable and unconditional license to exercise Affirmer's Copyright and Related Rights in the Work (i) in all territories worldwide, (ii) for the maximum duration provided by applicable law or treaty (including future time extensions), (iii) in any current or future medium and for any number of copies, and (iv) for any purpose whatsoever, including without limitation commercial, advertising or promotional purposes (the "License"). The License shall be deemed effective as of the date CC0 was applied by Affirmer to the Work. Should any part of the License for any reason be judged legally invalid or ineffective under applicable law, such partial invalidity or ineffectiveness shall not invalidate the remainder of the License, and in such case Affirmer hereby affirms that he or she will not (i) exercise any of his or her remaining Copyright and Related Rights in the Work or (ii) assert any associated claims and causes of action with respect to the Work, in either case contrary to Affirmer's express Statement of Purpose.

4. Limitations and Disclaimers.

     a. No trademark or patent rights held by Affirmer are waived, abandoned, surrendered, licensed or otherwise affected by this document.

     b. Affirmer offers the Work as-is and makes no representations or warranties of any kind concerning the Work, express, implied, statutory or otherwise, including without limitation warranties of title, merchantability, fitness for a particular purpose, non infringement, or the absence of latent or other defects, accuracy, or the present or absence of errors, whether or not discoverable, all to the greatest extent permissible under applicable law.

     c. Affirmer disclaims responsibility for clearing rights of other persons that may apply to the Work or any use thereof, including without limitation any person's Copyright and Related Rights in the Work. Further, Affirmer disclaims responsibility for obtaining any necessary consents, permissions or other rights required for any use of the Work.

     d. Affirmer understands and acknowledges that Creative Commons is not a party to this document and has no duty or obligation with respect to this CC0 or use of the Work.
```

### BSD Zero Clause License

```
Copyright (C) 2006 by Rob Landley <rob@landley.net>

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

### ring — `LICENSE` (crate root, as distributed)

```
*ring* uses an "ISC" license, like BoringSSL used to use, for new code
files. See LICENSE-other-bits for the text of that license.

See LICENSE-BoringSSL for code that was sourced from BoringSSL under the
Apache 2.0 license. Some code that was sourced from BoringSSL under the ISC
license. In each case, the license info is at the top of the file.

See src/polyfill/once_cell/LICENSE-APACHE and src/polyfill/once_cell/LICENSE-MIT
for the license to code that was sourced from the once_cell project.
```

### ring — `third_party/fiat/LICENSE` (Apache-2.0 header, as distributed)

```
The Apache License, Version 2.0 (Apache-2.0)

Copyright 2015-2020 the fiat-crypto authors (see the AUTHORS file)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### ring — `LICENSE-other-bits` (ISC-style, as distributed)

```
Copyright 2015-2025 Brian Smith.

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION
OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

---

### Common Public License Version 1.0

The following text is the Common Public License Version 1.0 as included in the NSIS 3.11 `COPYING` file, applicable to the NSIS LZMA compression module.

```
COMMON PUBLIC LICENSE VERSION 1.0
---------------------------------

THE ACCOMPANYING PROGRAM IS PROVIDED UNDER THE TERMS OF THIS COMMON PUBLIC LICENSE ("AGREEMENT"). ANY USE, REPRODUCTION OR DISTRIBUTION OF THE PROGRAM CONSTITUTES RECIPIENT'S ACCEPTANCE OF THIS AGREEMENT.

1. DEFINITIONS

"Contribution" means:

      a) in the case of the initial Contributor, the initial code and documentation distributed under this Agreement, and
      b) in the case of each subsequent Contributor:

      i) changes to the Program, and

      ii) additions to the Program;

      where such changes and/or additions to the Program originate from and are distributed by that particular Contributor. A Contribution 'originates' from a Contributor if it was added to the Program by such Contributor itself or anyone acting on such Contributor's behalf. Contributions do not include additions to the Program which: (i) are separate modules of software distributed in conjunction with the Program under their own license agreement, and (ii) are not derivative works of the Program. 

"Contributor" means any person or entity that distributes the Program.

"Licensed Patents " mean patent claims licensable by a Contributor which are necessarily infringed by the use or sale of its Contribution alone or when combined with the Program.

"Program" means the Contributions distributed in accordance with this Agreement.

"Recipient" means anyone who receives the Program under this Agreement, including all Contributors.

2. GRANT OF RIGHTS

      a) Subject to the terms of this Agreement, each Contributor hereby grants Recipient a non-exclusive, worldwide, royalty-free copyright license to reproduce, prepare derivative works of, publicly display, publicly perform, distribute and sublicense the Contribution of such Contributor, if any, and such derivative works, in source code and object code form.

      b) Subject to the terms of this Agreement, each Contributor hereby grants Recipient a non-exclusive, worldwide, royalty-free patent license under Licensed Patents to make, use, sell, offer to sell, import and otherwise transfer the Contribution of such Contributor, if any, in source code and object code form. This patent license shall apply to the combination of the Contribution and the Program if, at the time the Contribution is added by the Contributor, such addition of the Contribution causes such combination to be covered by the Licensed Patents. The patent license shall not apply to any other combinations which include the Contribution. No hardware per se is licensed hereunder. 

      c) Recipient understands that although each Contributor grants the licenses to its Contributions set forth herein, no assurances are provided by any Contributor that the Program does not infringe the patent or other intellectual property rights of any other entity. Each Contributor disclaims any liability to Recipient for claims brought by any other entity based on infringement of intellectual property rights or otherwise. As a condition to exercising the rights and licenses granted hereunder, each Recipient hereby assumes sole responsibility to secure any other intellectual property rights needed, if any. For example, if a third party patent license is required to allow Recipient to distribute the Program, it is Recipient's responsibility to acquire that license before distributing the Program.

      d) Each Contributor represents that to its knowledge it has sufficient copyright rights in its Contribution, if any, to grant the copyright license set forth in this Agreement. 

3. REQUIREMENTS

A Contributor may choose to distribute the Program in object code form under its own license agreement, provided that:

      a) it complies with the terms and conditions of this Agreement; and

      b) its license agreement:

      i) effectively disclaims on behalf of all Contributors all warranties and conditions, express and implied, including warranties or conditions of title and non-infringement, and implied warranties or conditions of merchantability and fitness for a particular purpose; 

      ii) effectively excludes on behalf of all Contributors all liability for damages, including direct, indirect, special, incidental and consequential damages, such as lost profits; 

      iii) states that any provisions which differ from this Agreement are offered by that Contributor alone and not by any other party; and

      iv) states that source code for the Program is available from such Contributor, and informs licensees how to obtain it in a reasonable manner on or through a medium customarily used for software exchange. 

When the Program is made available in source code form:

      a) it must be made available under this Agreement; and 

      b) a copy of this Agreement must be included with each copy of the Program. 

Contributors may not remove or alter any copyright notices contained within the Program.

Each Contributor must identify itself as the originator of its Contribution, if any, in a manner that reasonably allows subsequent Recipients to identify the originator of the Contribution.

4. COMMERCIAL DISTRIBUTION

Commercial distributors of software may accept certain responsibilities with respect to end users, business partners and the like. While this license is intended to facilitate the commercial use of the Program, the Contributor who includes the Program in a commercial product offering should do so in a manner which does not create potential liability for other Contributors. Therefore, if a Contributor includes the Program in a commercial product offering, such Contributor ("Commercial Contributor") hereby agrees to defend and indemnify every other Contributor ("Indemnified Contributor") against any losses, damages and costs (collectively "Losses") arising from claims, lawsuits and other legal actions brought by a third party against the Indemnified Contributor to the extent caused by the acts or omissions of such Commercial Contributor in connection with its distribution of the Program in a commercial product offering. The obligations in this section do not apply to any claims or Losses relating to any actual or alleged intellectual property infringement. In order to qualify, an Indemnified Contributor must: a) promptly notify the Commercial Contributor in writing of such claim, and b) allow the Commercial Contributor to control, and cooperate with the Commercial Contributor in, the defense and any related settlement negotiations. The Indemnified Contributor may participate in any such claim at its own expense.

For example, a Contributor might include the Program in a commercial product offering, Product X. That Contributor is then a Commercial Contributor. If that Commercial Contributor then makes performance claims, or offers warranties related to Product X, those performance claims and warranties are such Commercial Contributor's responsibility alone. Under this section, the Commercial Contributor would have to defend claims against the other Contributors related to those performance claims and warranties, and if a court requires any other Contributor to pay any damages as a result, the Commercial Contributor must pay those damages.

5. NO WARRANTY

EXCEPT AS EXPRESSLY SET FORTH IN THIS AGREEMENT, THE PROGRAM IS PROVIDED ON AN "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED INCLUDING, WITHOUT LIMITATION, ANY WARRANTIES OR CONDITIONS OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. Each Recipient is solely responsible for determining the appropriateness of using and distributing the Program and assumes all risks associated with its exercise of rights under this Agreement, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and unavailability or interruption of operations.

6. DISCLAIMER OF LIABILITY

EXCEPT AS EXPRESSLY SET FORTH IN THIS AGREEMENT, NEITHER RECIPIENT NOR ANY CONTRIBUTORS SHALL HAVE ANY LIABILITY FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING WITHOUT LIMITATION LOST PROFITS), HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OR DISTRIBUTION OF THE PROGRAM OR THE EXERCISE OF ANY RIGHTS GRANTED HEREUNDER, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

7. GENERAL

If any provision of this Agreement is invalid or unenforceable under applicable law, it shall not affect the validity or enforceability of the remainder of the terms of this Agreement, and without further action by the parties hereto, such provision shall be reformed to the minimum extent necessary to make such provision valid and enforceable.

If Recipient institutes patent litigation against a Contributor with respect to a patent applicable to software (including a cross-claim or counterclaim in a lawsuit), then any patent licenses granted by that Contributor to such Recipient under this Agreement shall terminate as of the date such litigation is filed. In addition, if Recipient institutes patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Program itself (excluding combinations of the Program with other software or hardware) infringes such Recipient's patent(s), then such Recipient's rights granted under Section 2(b) shall terminate as of the date such litigation is filed.

All Recipient's rights under this Agreement shall terminate if it fails to comply with any of the material terms or conditions of this Agreement and does not cure such failure in a reasonable period of time after becoming aware of such noncompliance. If all Recipient's rights under this Agreement terminate, Recipient agrees to cease use and distribution of the Program as soon as reasonably practicable. However, Recipient's obligations under this Agreement and any licenses granted by Recipient relating to the Program shall continue and survive.

Everyone is permitted to copy and distribute copies of this Agreement, but in order to avoid inconsistency the Agreement is copyrighted and may only be modified in the following manner. The Agreement Steward reserves the right to publish new versions (including revisions) of this Agreement from time to time. No one other than the Agreement Steward has the right to modify this Agreement. IBM is the initial Agreement Steward. IBM may assign the responsibility to serve as the Agreement Steward to a suitable separate entity. Each new version of the Agreement will be given a distinguishing version number. The Program (including Contributions) may always be distributed subject to the version of the Agreement under which it was received. In addition, after a new version of the Agreement is published, Contributor may elect to distribute the Program (including its Contributions) under the new version. Except as expressly stated in Sections 2(a) and 2(b) above, Recipient receives no rights or licenses to the intellectual property of any Contributor under this Agreement, whether expressly, by implication, estoppel or otherwise. All rights in the Program not expressly granted under this Agreement are reserved.

This Agreement is governed by the laws of the State of New York and the intellectual property laws of the United States of America. No party to this Agreement will bring a legal action under this Agreement more than one year after the cause of action arose. Each party waives its rights to a jury trial in any resulting litigation.
```

## Appendix B — Per-package copyright attributions

Copyright attributions as they appear in the distributed license files of the exact package versions listed in the inventory table. Where a package's distributed license file carries no copyright attribution line, that is stated. License expressions are as audited.

### `@tauri-apps/api` 2.12.3 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `@tauri-apps/plugin-dialog` 2.8.2 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `adler2` 2.0.1 — `0BSD OR MIT OR Apache-2.0`

- Copyright (C) Jonas Schievink <jonasschievink@gmail.com>

### `aho-corasick` 1.1.5 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `alloc-no-stdlib` 3.0.0 — `BSD-3-Clause`

- Copyright (c) 2016 Dropbox, Inc.

### `alloc-stdlib` 0.3.0 — `BSD-3-Clause`

- Copyright (c) 2016 Dropbox, Inc.

Note: License file obtained from the upstream repository (https://github.com/dropbox/rust-alloc-no-stdlib, master branch); absent from the distributed crate archive.

### `anyhow` 1.0.104 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `arrayvec` 0.7.8 — `MIT OR Apache-2.0`

- Copyright (c) Ulrik Sverdrup "bluss" 2015-2023

### `atomic-waker` 1.1.2 — `Apache-2.0 OR MIT`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `base64` 0.23.1 — `MIT OR Apache-2.0`

- Copyright (c) 2025 Alice Maz, Marshall Pierce

### `bit-set` 0.8.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2023 The Rust Project Developers

### `bit-vec` 0.8.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2023 The Rust Project Developers

### `bitflags` 1.3.2 — `MIT/Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `bitflags` 2.13.2 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `blake3` 1.8.7 — `CC0-1.0 OR Apache-2.0 OR Apache-2.0 WITH LLVM-exception`

- Copyright 2019 Jack O'Connor and Samuel Neves

### `block-buffer` 0.10.4 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2019 The RustCrypto Project Developers

### `brotli` 9.0.0 — `BSD-3-Clause AND MIT`

- Copyright (c) 2016 Dropbox, Inc.

- Copyright (c) 2009, 2010, 2013-2016 by the Brotli Authors.

### `brotli-decompressor` 6.0.1 — `BSD-3-Clause/MIT`

- Copyright (c) 2016 Dropbox, Inc.

### `bs58` 0.5.1 — `MIT/Apache-2.0`

- Copyright (c) 2016 The roaring-rs developers.

### `byteorder` 1.5.0 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `bytes` 1.12.1 — `MIT`

- Copyright (c) 2018 Carl Lerche

### `camino` 1.2.6 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `cargo-platform` 0.1.9 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `cargo_metadata` 0.19.2 — `MIT`

- No copyright attribution line in the distributed license file.

### `cfb` 0.14.0 — `MIT`

- Copyright (c) 2017 Matthew D. Steele

### `cfg-if` 1.0.5 — `MIT OR Apache-2.0`

- Copyright (c) 2014 Alex Crichton

### `chrono` 0.4.45 — `MIT OR Apache-2.0`

- Copyright (c) 2014, Kang Seonghoon.

### `constant_time_eq` 0.4.2 — `CC0-1.0 OR MIT-0 OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `constant_time_eq` 0.6.1 — `CC0-1.0 OR MIT-0 OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `cookie` 0.18.2 — `MIT OR Apache-2.0`

- Copyright 2017 Sergio Benitez

- Copyright 2014 Alex Chricton

- Copyright (c) 2017 Sergio Benitez

- Copyright (c) 2014 Alex Crichton

### `cpufeatures` 0.2.17 — `MIT OR Apache-2.0`

- Copyright (c) 2020-2025 The RustCrypto Project Developers

### `cpufeatures` 0.3.1 — `MIT OR Apache-2.0`

- Copyright (c) 2020-2026 The RustCrypto Project Developers

### `crc32fast` 1.5.2 — `MIT OR Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2018 Sam Rijs, Alex Crichton and contributors

### `crossbeam-channel` 0.5.17 — `MIT OR Apache-2.0`

- Copyright (c) 2019 The Crossbeam Project Developers

- Copyright (c) 2009 The Go Authors. All rights reserved.

### `crossbeam-utils` 0.8.23 — `MIT OR Apache-2.0`

- Copyright (c) 2019 The Crossbeam Project Developers

### `crypto-common` 0.1.7 — `MIT OR Apache-2.0`

- Copyright (c) 2021 RustCrypto Developers

### `cssparser` 0.37.0 — `MPL-2.0`

- No copyright attribution line in the distributed license file.

### `ctor` 1.0.13 — `Apache-2.0 OR MIT`

- Copyright {yyyy} {name of copyright owner}

### `darling` 0.24.1 — `MIT`

- Copyright (c) 2017 Ted Driggs

### `darling_core` 0.24.1 — `MIT`

- Copyright (c) 2017 Ted Driggs

### `defmt` 1.1.1 — `MIT OR Apache-2.0`

- Copyright (c) Ferrous Systems

### `defmt-parser` 1.0.0 — `MIT OR Apache-2.0`

- Copyright (c) Ferrous Systems

Note: License file obtained from the upstream repository (https://github.com/knurling-rs/defmt, main branch); absent from the distributed crate archive. (The crate is dual-licensed MIT OR Apache-2.0; the Apache-2.0 text is in Appendix A.)

### `deranged` 0.5.8 — `MIT OR Apache-2.0`

- Copyright 2024 Jacob Pratt et al.

- Copyright (c) 2024 Jacob Pratt et al.

### `derive_more` 2.1.1 — `MIT`

- Copyright (c) 2016 Jelte Fennema

### `digest` 0.10.7 — `MIT OR Apache-2.0`

- Copyright (c) 2017 Artyom Pavlov

### `dirs` 7.0.0 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2019 dirs-rs contributors

### `dirs-sys` 0.5.0 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2019 dirs-rs contributors

### `dom_query` 0.28.0 — `MIT`

- Copyright (c) 2023 Mykola Humanov

### `dpi` 0.1.2 — `Apache-2.0 AND MIT`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2018 Jorge Aparicio

- Copyright © 2005-2020 Rich Felker, et al.

- Copyright © 1993,2004 Sun Microsystems or

- Copyright © 2003-2011 David Schultz or

### `dtoa` 1.0.11 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `dtoa-short` 0.3.5 — `MPL-2.0`

- No copyright attribution line in the distributed license file.

### `dunce` 1.0.5 — `CC0-1.0 OR MIT-0 OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `dyn-clone` 1.0.20 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `equivalent` 1.0.2 — `Apache-2.0 OR MIT`

- Copyright (c) 2016--2023

### `erased-serde` 0.4.10 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `fallible-iterator` 0.3.0 — `MIT/Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2015 The rust-openssl-verify Developers

### `fallible-streaming-iterator` 0.1.9 — `MIT/Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2016 The fallible-streaming-iterator Developers

### `fastrand` 2.5.0 — `Apache-2.0 OR MIT`

- No copyright attribution line in the distributed license file.

### `fdeflate` 0.3.7 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `flate2` 1.1.10 — `MIT OR Apache-2.0`

- Copyright (c) 2014-2026 Alex Crichton

### `fnv` 1.0.7 — `Apache-2.0 / MIT`

- Copyright (c) 2017 Contributors

### `foldhash` 0.2.0 — `Zlib`

- Copyright (c) 2024 Orson Peters

### `form_urlencoded` 1.2.2 — `MIT OR Apache-2.0`

- Copyright (c) 2013-2016 The rust-url developers

### `fs2` 0.4.3 — `MIT/Apache-2.0`

- Copyright (c) 2015 The Rust Project Developers

### `futures-channel` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `futures-core` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `futures-io` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `futures-sink` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `futures-task` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `futures-util` 0.3.34 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Alex Crichton

- Copyright (c) 2017 The Tokio Authors

### `generic-array` 0.14.7 — `MIT`

- Copyright (c) 2015 Bartłomiej Kamiński

### `getrandom` 0.2.17 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2024 The rust-random Project Developers

- Copyright (c) 2014 The Rust Project Developers

### `getrandom` 0.3.4 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2025 The rust-random Project Developers

- Copyright (c) 2014 The Rust Project Developers

### `getrandom` 0.4.3 — `MIT OR Apache-2.0`

- Copyright (c) 2018-2026 The rust-random Project Developers

- Copyright (c) 2014 The Rust Project Developers

### `glob` 0.3.4 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `hashbrown` 0.12.3 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Amanieu d'Antras

### `hashbrown` 0.17.1 — `MIT OR Apache-2.0`

- Copyright (c) 2016 Amanieu d'Antras

### `hashlink` 0.12.2 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `heck` 0.5.0 — `MIT OR Apache-2.0`

- Copyright (c) 2015 The Rust Project Developers

### `hex` 0.4.3 — `MIT OR Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2013-2014 The Rust Project Developers.

- Copyright (c) 2015-2020 The rust-hex Developers

### `html5ever` 0.39.0 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The html5ever Project Developers

### `http` 1.5.0 — `MIT OR Apache-2.0`

- Copyright 2017 http-rs authors

- Copyright (c) 2017 http-rs authors

### `http-body` 1.1.0 — `MIT`

- Copyright (c) 2019-2026 Sean McArthur & Hyper Contributors

### `http-body-util` 0.1.5 — `MIT`

- Copyright (c) 2019-2026 Sean McArthur & Hyper Contributors

### `httparse` 1.10.1 — `MIT OR Apache-2.0`

- Copyright (c) 2015-2025 Sean McArthur

### `hyper` 1.12.0 — `MIT`

- Copyright (c) 2014-2026 Sean McArthur

### `hyper-rustls` 0.27.10 — `Apache-2.0 OR ISC OR MIT`

- Copyright (c) 2016, Joseph Birr-Pixton <jpixton@gmail.com>

- Copyright (c) 2016 Joseph Birr-Pixton <jpixton@gmail.com>

### `hyper-util` 0.1.21 — `MIT`

- Copyright (c) 2023-2025 Sean McArthur

### `ico` 0.5.0 — `MIT`

- Copyright (c) 2018 Matthew D. Steele

### `icu_collections` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_locale_core` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_normalizer` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_normalizer_data` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_properties` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_properties_data` 2.3.0 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `icu_provider` 2.3.1 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `ident_case` 1.0.1 — `MIT/Apache-2.0`

- No copyright attribution line in the distributed license file.

### `idna` 1.1.0 — `MIT OR Apache-2.0`

- Copyright (c) 2013-2025 The rust-url developers

### `idna_adapter` 1.2.2 — `Apache-2.0 OR MIT`

- Copyright (c) The rust-url developers

### `indexmap` 1.9.3 — `Apache-2.0 OR MIT`

- Copyright (c) 2016--2017

### `indexmap` 2.14.2 — `Apache-2.0 OR MIT`

- Copyright (c) 2016--2017

### `infer` 0.22.0 — `MIT`

- Copyright (c) 2019 Bojan

### `ipnet` 2.12.2 — `MIT OR Apache-2.0`

- Copyright 2017 Juniper Networks, Inc.

### `itoa` 1.0.18 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `jiff` 0.2.38 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `jiff-core` 0.1.1 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `jiff-tzdb` 0.1.9 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `jiff-tzdb-platform` 0.1.3 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `json-patch` 4.2.0 — `MIT/Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2017 Ivan Dubrov

### `jsonptr` 0.7.1 — `MIT OR Apache-2.0`

- Copyright 2024 Chance Dinkins

- Copyright (c) 2022 Chance Dinkins

### `keyboard-types` 0.8.3 — `MIT OR Apache-2.0`

- Copyright (c) 2017 Pyfisch

### `libc` 0.2.190 — `MIT OR Apache-2.0`

- Copyright (c) The Rust Project Developers

### `libsqlite3-sys` 0.39.1 — `MIT`

- Copyright (c) 2014 The rusqlite developers

### `litemap` 0.8.3 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `lock_api` 0.4.14 — `MIT OR Apache-2.0`

- Copyright (c) 2016 The Rust Project Developers

### `log` 0.4.34 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `markup5ever` 0.39.0 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The html5ever Project Developers

### `memchr` 2.8.3 — `Unlicense OR MIT`

- Copyright (c) 2015 Andrew Gallant

### `mime` 0.3.17 — `MIT OR Apache-2.0`

- Copyright (c) 2014 Sean McArthur

### `minisign-verify` 0.3.0 — `MIT`

- Copyright (c) 2019-2025 Frank Denis

- Copyright (c) 2006-2009 Graydon Hoare

- Copyright (c) 2009-2013 Mozilla Foundation

### `miniz_oxide` 0.8.9 — `MIT OR Zlib OR Apache-2.0`

- Copyright 2013-2014 RAD Game Tools and Valve Software

- Copyright 2010-2014 Rich Geldreich and Tenacious Software LLC

- Copyright (c) 2017 Frommi

- Copyright (c) 2017-2024 oyvindln

- Copyright (c) 2020 Frommi

### `miniz_oxide` 0.9.1 — `MIT OR Zlib OR Apache-2.0`

- Copyright 2013-2014 RAD Game Tools and Valve Software

- Copyright 2010-2014 Rich Geldreich and Tenacious Software LLC

- Copyright (c) 2017 Frommi

- Copyright (c) 2017-2024 oyvindln

- Copyright (c) 2020 Frommi

### `mio` 1.2.4 — `MIT`

- Copyright (c) 2014 Carl Lerche and other MIO contributors

### `muda` 0.20.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2022-2022 Tauri Programme within The Commons Conservancy

### `new_debug_unreachable` 1.0.6 — `MIT`

- Copyright (c) 2015 Jonathan Reem

### `num-conv` 0.2.2 — `MIT OR Apache-2.0`

- Copyright (c) Jacob Pratt

### `num-traits` 0.2.19 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `once_cell` 1.21.4 — `MIT OR Apache-2.0`
- No copyright attribution line in the distributed license file.

### `option-ext` 0.2.0 — `MPL-2.0`

- No copyright attribution line in the distributed license file.

### `parking_lot` 0.12.5 — `MIT OR Apache-2.0`

- Copyright (c) 2016 The Rust Project Developers

### `parking_lot_core` 0.9.12 — `MIT OR Apache-2.0`

- Copyright (c) 2016 The Rust Project Developers

### `percent-encoding` 2.3.2 — `MIT OR Apache-2.0`

- Copyright (c) 2013-2025 The rust-url developers

### `phf` 0.13.1 — `MIT`

- Copyright (c) 2014-2022 Steven Fackler, Yuki Okushi

### `phf_generator` 0.13.1 — `MIT`

- Copyright (c) 2014-2022 Steven Fackler, Yuki Okushi

### `phf_shared` 0.13.1 — `MIT`

- Copyright (c) 2014-2022 Steven Fackler, Yuki Okushi

### `pin-project-lite` 0.2.17 — `Apache-2.0 OR MIT`

- No copyright attribution line in the distributed license file.

### `plist` 1.10.1 — `MIT`

- Copyright (c) 2015 Edward Barnard

### `png` 0.17.16 — `MIT OR Apache-2.0`

- Copyright (c) 2015 nwin

### `png` 0.18.1 — `MIT OR Apache-2.0`

- Copyright (c) 2015 nwin

### `potential_utf` 0.1.6 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `powerfmt` 0.2.1 — `MIT OR Apache-2.0`

- Copyright 2023 Jacob Pratt et al.

- Copyright (c) 2023 Jacob Pratt et al.

### `precomputed-hash` 0.1.1 — `MIT`

- Copyright (c) 2017 Emilio Cobos Álvarez

### `proc-macro2` 1.0.107 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `quick-xml` 0.42.0 — `MIT`

- Copyright (c) 2016 Johann Tuffe

### `quote` 1.0.47 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `raw-window-handle` 0.6.2 — `MIT OR Apache-2.0 OR Zlib`

- Copyright (c) 2019 Osspial

- Copyright (c) 2020 Osspial

### `ref-cast` 1.0.27 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `regex` 1.13.1 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `regex-automata` 0.4.18 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

### `regex-syntax` 0.8.11 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The Rust Project Developers

- Copyright © 1991-2018 Unicode, Inc. All rights reserved.

### `reqwest` 0.13.5 — `MIT OR Apache-2.0`

- Copyright 2016 Sean McArthur

- Copyright (c) 2016-2026 Sean McArthur

### `rfd` 0.16.0 — `MIT`

- Copyright (c) 2022 Bartłomiej Maryńczak

### `ring` 0.17.14 — `Apache-2.0 AND ISC`

- Copyright 2015-2020 the fiat-crypto authors (see the AUTHORS file)

- Copyright (c) 2009 The Go Authors. All rights reserved.

- Copyright 2015 The Chromium Authors. All rights reserved.

- Copyright 2015-2025 Brian Smith.

### `rusqlite` 0.41.0 — `MIT`

- Copyright (c) 2014 The rusqlite developers

### `rustc-hash` 2.1.3 — `Apache-2.0 OR MIT`

- No copyright attribution line in the distributed license file.

### `rustls` 0.23.46 — `Apache-2.0 OR ISC OR MIT`

- Copyright (c) 2016, Joseph Birr-Pixton <jpixton@gmail.com>

- Copyright (c) 2016 Joseph Birr-Pixton <jpixton@gmail.com>

### `rustls-pki-types` 1.16.0 — `MIT OR Apache-2.0`

- Copyright 2023 Dirkjan Ochtman

- Copyright (c) 2023 Dirkjan Ochtman <dirkjan@ochtman.nl>

### `rustls-platform-verifier` 0.7.1 — `MIT OR Apache-2.0`

- Copyright (c) 2022 1Password

### `rustls-webpki` 0.103.17 — `ISC`

- Copyright 2015 Brian Smith.

### `same-file` 1.0.6 — `Unlicense/MIT`

- Copyright (c) 2017 Andrew Gallant

### `schemars` 0.8.22 — `MIT`

- Copyright (c) 2019 Graham Esau

### `schemars` 0.9.0 — `MIT`

- Copyright (c) 2019 Graham Esau

### `schemars` 1.2.2 — `MIT`

- Copyright (c) 2019 Graham Esau

### `scopeguard` 1.2.0 — `MIT OR Apache-2.0`

- Copyright (c) 2016-2019 Ulrik Sverdrup "bluss" and scopeguard developers

### `selectors` 0.38.0 — `MPL-2.0`

- No copyright attribution line in the distributed license file.

Note: No LICENSE file in the distributed crate archive. The package metadata declares license = "MPL-2.0"; upstream repository https://github.com/servo/stylo (selectors/ directory) carries no LICENSE file at the paths checked. The full MPL-2.0 text is reproduced in Appendix A.

### `semver` 1.0.28 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde` 1.0.229 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde-untagged` 0.1.9 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde_core` 1.0.229 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde_derive_internals` 0.29.1 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde_json` 1.0.154 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `serde_spanned` 1.1.2 — `MIT OR Apache-2.0`

- Copyright Individual contributors

- Copyright (c) Individual contributors

### `serde_with` 3.24.0 — `MIT OR Apache-2.0`

- Copyright (c) 2015

### `serialize-to-javascript` 0.1.2 — `MIT OR Apache-2.0`

- Copyright (c) 2021 Chip Reed

### `servo_arc` 0.4.3 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `sha2` 0.10.9 — `MIT OR Apache-2.0`

- Copyright (c) 2006-2009 Graydon Hoare

- Copyright (c) 2009-2013 Mozilla Foundation

- Copyright (c) 2016 Artyom Pavlov

### `simd-adler32` 0.3.10 — `MIT`

- Copyright (c) [2021] [Marvin Countryman]

### `siphasher` 1.0.4 — `MIT OR Apache-2.0`

- Copyright 2012-2016 The Rust Project Developers.

- Copyright 2016-2026 Frank Denis.

### `slab` 0.4.12 — `MIT`

- Copyright (c) 2019 Carl Lerche

### `smallvec` 1.16.3 — `MIT OR Apache-2.0`

- Copyright (c) 2018 The Servo Project Developers

### `socket2` 0.6.5 — `MIT OR Apache-2.0`

- Copyright (c) 2014 Alex Crichton

### `softbuffer` 0.4.8 — `MIT OR Apache-2.0`

- Copyright 2022 Kirill Chibisov

### `stable_deref_trait` 1.2.1 — `MIT OR Apache-2.0`

- Copyright (c) 2017 Robert Grosse

### `string_cache` 0.9.0 — `MIT OR Apache-2.0`

- Copyright (c) 2012-2013 Mozilla Foundation

### `strsim` 0.11.1 — `MIT`

- Copyright (c) 2015 Danny Guo

- Copyright (c) 2016 Titus Wormer <tituswormer@gmail.com>

- Copyright (c) 2018 Akash Kurdekar

### `subtle` 2.6.1 — `BSD-3-Clause`

- Copyright (c) 2016-2017 Isis Agora Lovecruft, Henry de Valence. All rights reserved.

- Copyright (c) 2016-2024 Isis Agora Lovecruft. All rights reserved.

### `syn` 2.0.119 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `syn` 3.0.8 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `sync_wrapper` 1.0.2 — `Apache-2.0`

- No copyright attribution line in the distributed license file.

### `synstructure` 0.14.0 — `MIT`

- Copyright 2016 Nika Layzell

### `tao` 0.37.1 — `Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

### `tauri` 2.12.3 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-codegen` 2.7.2 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-plugin-dialog` 2.8.2 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-plugin-fs` 2.7.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-plugin-updater` 2.14.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-runtime` 2.12.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-runtime-wry` 2.12.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tauri-utils` 2.10.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2017 - Present Tauri Apps Contributors

### `tempfile` 3.27.0 — `MIT OR Apache-2.0`

- Copyright (c) 2015 Steven Allen

### `tendril` 0.5.1 — `MIT OR Apache-2.0`

- Copyright (c) 2015 Keegan McAllister

### `thiserror` 2.0.21 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `time` 0.3.55 — `MIT OR Apache-2.0`

- Copyright (c) Jacob Pratt et al.

### `time-core` 0.1.9 — `MIT OR Apache-2.0`

- Copyright (c) Jacob Pratt et al.

### `tinystr` 0.8.4 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `tinyvec` 1.13.3 — `Zlib OR Apache-2.0 OR MIT`

- Copyright (c) 2019 Daniel "Lokathor" Gee.

### `tokio` 1.53.2 — `MIT`

- Copyright (c) Tokio Contributors

### `tokio-rustls` 0.26.6 — `MIT OR Apache-2.0`

- Copyright 2017 quininer kel

- Copyright (c) 2017 quininer kel

### `tokio-util` 0.7.20 — `MIT`

- Copyright (c) Tokio Contributors

### `toml` 1.1.8+spec-1.1.0 — `MIT OR Apache-2.0`

- Copyright Individual contributors

- Copyright (c) Individual contributors

### `toml_datetime` 1.1.2+spec-1.1.0 — `MIT OR Apache-2.0`

- Copyright Individual contributors

- Copyright (c) Individual contributors

### `toml_parser` 1.1.5+spec-1.1.0 — `MIT OR Apache-2.0`

- Copyright Individual contributors

- Copyright (c) Individual contributors

### `toml_writer` 1.1.3+spec-1.1.0 — `MIT OR Apache-2.0`

- Copyright Individual contributors

- Copyright (c) Individual contributors

### `tower` 0.5.3 — `MIT`

- Copyright (c) 2019 Tower Contributors

### `tower-http` 0.6.11 — `MIT`

- Copyright (c) 2019-2021 Tower Contributors

### `tower-layer` 0.3.3 — `MIT`

- Copyright (c) 2019 Tower Contributors

### `tower-service` 0.3.3 — `MIT`

- Copyright (c) 2019 Tower Contributors

### `tracing` 0.1.44 — `MIT`

- Copyright (c) 2019 Tokio Contributors

### `tracing-core` 0.1.36 — `MIT`

- Copyright (c) 2014 Mathijs van de Nes

### `tray-icon` 0.25.1 — `MIT OR Apache-2.0`

- Copyright (c) 2022-2022 Tauri Programme within The Commons Conservancy

### `try-lock` 0.2.5 — `MIT`

- Copyright (c) 2018-2023 Sean McArthur

- Copyright (c) 2016 Alex Crichton

### `typed-path` 0.13.0 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `typeid` 1.0.3 — `MIT OR Apache-2.0`

- No copyright attribution line in the distributed license file.

### `typenum` 1.20.1 — `MIT OR Apache-2.0`

- Copyright 2014 Paho Lurie-Gregg

- Copyright (c) 2014 Paho Lurie-Gregg

### `unicode-ident` 1.0.27 — `(MIT OR Apache-2.0) AND Unicode-3.0`

- Copyright © 1991-2023 Unicode, Inc.

### `unicode-segmentation` 1.13.3 — `MIT OR Apache-2.0`

- Copyright (c) 2015 The Rust Project Developers

### `untrusted` 0.9.0 — `ISC`

- Copyright 2015-2016 Brian Smith.

### `url` 2.5.8 — `MIT OR Apache-2.0`

- Copyright (c) 2013-2025 The rust-url developers

### `urlpattern` 0.6.0 — `MIT`

- Copyright (c) 2021 the Deno authors

### `utf8_iter` 1.0.4 — `Apache-2.0 OR MIT`

- Copyright Mozilla Foundation

### `uuid` 1.28.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2014 The Rust Project Developers

- Copyright (c) 2018 Ashley Mannix, Christopher Armstrong, Dylan DPC, Hunar Roop Kahlon

### `walkdir` 2.5.0 — `Unlicense/MIT`

- Copyright (c) 2015 Andrew Gallant

### `want` 0.3.2 — `MIT`

- Copyright (c) 2018-2019 Sean McArthur

### `web-time` 1.1.0 — `MIT OR Apache-2.0`

- Copyright 2023 dAxpeDDa

- Copyright (c) 2023 dAxpeDDa

### `web_atoms` 0.2.6 — `MIT OR Apache-2.0`

- Copyright (c) 2014 The html5ever Project Developers

### `webview2-com` 0.39.1 — `MIT`

- Copyright (c) 2021 Bill Avery

Note: License file obtained from the upstream repository (https://github.com/wravery/webview2-rs, main branch); absent from the distributed crate archive.

### `webview2-com-sys` 0.39.1 — `MIT`

- Copyright (c) 2021 Bill Avery

Note: License file obtained from the upstream repository (https://github.com/wravery/webview2-rs, main branch); absent from the distributed crate archive. (Both webview2 crates share this repository and license file.)

### `winapi` 0.3.9 — `MIT/Apache-2.0`

- Copyright {yyyy} {name of copyright owner}

- Copyright (c) 2015-2018 The winapi-rs Developers

### `winapi-util` 0.1.11 — `Unlicense OR MIT`

- Copyright (c) 2017 Andrew Gallant

### `window-vibrancy` 0.8.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2020-2022 Tauri Programme within The Commons Conservancy

### `windows` 0.62.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-collections` 0.3.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-core` 0.62.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-future` 0.3.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-link` 0.2.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-numerics` 0.3.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-registry` 0.6.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-result` 0.4.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-strings` 0.5.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-sys` 0.60.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-sys` 0.61.2 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-targets` 0.53.5 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-threading` 0.2.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows-version` 0.1.7 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `windows_x86_64_msvc` 0.53.1 — `MIT OR Apache-2.0`

- Copyright (c) Microsoft Corporation.

### `winnow` 1.0.4 — `MIT`

- No copyright attribution line in the distributed license file.

### `writeable` 0.6.4 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `wry` 0.57.0 — `Apache-2.0 OR MIT`

- Copyright (c) 2020-2023 Ngo Iok Ui & Tauri Programme within The Commons Conservancy

### `yoke` 0.8.3 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `zerofrom` 0.1.8 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `zeroize` 1.9.1 — `Apache-2.0 OR MIT`

- Copyright (c) 2018-2026 The RustCrypto Project Developers

### `zerotrie` 0.2.5 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `zerovec` 0.11.8 — `Unicode-3.0`

- Copyright © 2020-2024 Unicode, Inc.

### `zip` 9.6.0 — `MIT`

- Copyright (c) 2014 Mathijs van de Nes

### `zlib-rs` 0.6.8 — `Zlib`

- (C) 2024 Trifecta Tech Foundation

### `zmij` 1.0.23 — `MIT`

- No copyright attribution line in the distributed license file.