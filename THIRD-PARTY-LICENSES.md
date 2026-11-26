# Third-party licenses / Лицензи на чужди компоненти

TEKSO uses the open source components below. Each one keeps its own license; this list is generated from the build metadata (cargo metadata).

TEKSO ползва изброените компоненти с отворен код. Всеки запазва своя лиценз; списъкът е изведен автоматично от данните на компилацията.

## Fonts shipped in the app

All of these families are licensed under the SIL Open Font License, Version 1.1 (https://openfontlicense.org) and shipped unmodified. The Liberation families and Carlito are used by OCR with the `editable` mode (visible text in the closest matching font) and are in the app's resources (`fonts/` and `licenses/fonts/`). Source Serif 4 (the font of new documents), Carlito and Liberation Mono are also built into the app for editing and PDF export.

| Font | Files | Copyright | License |
|---|---|---|---|
| Liberation Sans, Liberation Serif, Liberation Mono 2.1.5 | 12 (Regular, Bold, Italic, Bold Italic of each) | Digitized data copyright (c) 2010 Google Corporation with Reserved Font Arimo, Tinos and Cousine. Copyright (c) 2012 Red Hat, Inc. with Reserved Font Name Liberation. | SIL OFL 1.1, source https://github.com/liberationfonts/liberation-fonts |
| Source Serif 4 (4.005) | 4 (Regular, Bold, Italic, Bold Italic) | Copyright 2014 - 2023 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source' | SIL OFL 1.1, source https://github.com/adobe-fonts/source-serif |
| Carlito | 4 (Regular, Bold, Italic, Bold Italic) | Copyright 2013 The Carlito Project Authors (https://github.com/googlefonts/carlito), with Reserved Font Name "Carlito" | SIL OFL 1.1, source https://github.com/googlefonts/carlito |

The font files in the app are not changed and not sold on their own. A PDF written by OCR embeds only the glyphs it uses (a subset); that is the usual way fonts are embedded in documents.

## Hyphenation patterns / Модели за сричкопренасяне

Hyphenation uses the `hypher` crate with patterns from the tex-hyphen project for Bulgarian (Copyright (C) 2000, 2004, 2017 Anton Zinoviev), English, German, French, Russian, Ukrainian, Spanish and Italian, each under its own license. The NOTICE file of hypher is reproduced verbatim at the end of this document.

Сричкопренасянето ползва crate `hypher` с модели от проекта tex-hyphen за български (Copyright (C) 2000, 2004, 2017 Anton Zinoviev), английски, немски, френски, руски, украински, испански и италиански, всеки под своя лиценз. Файлът NOTICE на hypher е даден дословно в края на този документ.

## Components / Компоненти

| Component | Version | License | Source |
|---|---|---|---|
| adler2 | 2.0.1 | 0BSD OR MIT OR Apache-2.0 | https://github.com/oyvindln/adler2 |
| aes | 0.8.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| aes | 0.9.3 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| aho-corasick | 1.1.5 | Unlicense OR MIT | https://github.com/BurntSushi/aho-corasick |
| alloc-no-stdlib | 2.0.4 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| alloc-no-stdlib | 3.0.0 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| alloc-stdlib | 0.2.4 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| alloc-stdlib | 0.3.0 | BSD-3-Clause | https://github.com/dropbox/rust-alloc-no-stdlib |
| android_system_properties | 0.1.6 | MIT OR Apache-2.0 | https://github.com/nical/android_system_properties |
| anyhow | 1.0.104 | MIT OR Apache-2.0 | https://github.com/dtolnay/anyhow |
| anymap3 | 1.1.0 | BlueOak-1.0.0 OR MIT OR Apache-2.0 | https://github.com/reivilibre/anymap3 |
| arrayref | 0.3.9 | BSD-2-Clause | https://github.com/droundy/arrayref |
| arrayvec | 0.7.8 | MIT OR Apache-2.0 | https://github.com/bluss/arrayvec |
| ascii | 1.1.0 | Apache-2.0 OR MIT | https://github.com/tomprogrammer/rust-ascii |
| async-broadcast | 0.7.2 | MIT OR Apache-2.0 | https://github.com/smol-rs/async-broadcast |
| async-channel | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-channel |
| async-executor | 1.14.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-executor |
| async-io | 2.6.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-io |
| async-lock | 3.4.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-lock |
| async-process | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-process |
| async-recursion | 1.2.0 | MIT OR Apache-2.0 | https://github.com/dcchut/async-recursion |
| async-signal | 0.2.14 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-signal |
| async-task | 4.7.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/async-task |
| async-trait | 0.1.92 | MIT OR Apache-2.0 | https://github.com/dtolnay/async-trait |
| atk | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| atk-sys | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| atomic-waker | 1.1.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/atomic-waker |
| autocfg | 1.5.1 | Apache-2.0 OR MIT | https://github.com/cuviper/autocfg |
| base16ct | 0.2.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/base16ct |
| base64 | 0.21.7 | MIT OR Apache-2.0 | https://github.com/marshallpierce/rust-base64 |
| base64 | 0.22.1 | MIT OR Apache-2.0 | https://github.com/marshallpierce/rust-base64 |
| base64 | 0.23.1 | MIT OR Apache-2.0 | https://github.com/marshallpierce/rust-base64 |
| base64ct | 1.8.3 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats |
| bit-set | 0.8.0 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-set |
| bit-set | 0.11.1 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-vec |
| bit-vec | 0.8.0 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-vec |
| bit-vec | 0.10.2 | Apache-2.0 OR MIT | https://github.com/contain-rs/bit-vec |
| bitflags | 1.3.2 | MIT/Apache-2.0 | https://github.com/bitflags/bitflags |
| bitflags | 2.13.2 | MIT OR Apache-2.0 | https://github.com/bitflags/bitflags |
| block-buffer | 0.10.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block-buffer | 0.12.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block-padding | 0.3.3 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block-padding | 0.4.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| block2 | 0.6.2 | MIT | https://github.com/madsmtm/objc2 |
| blocking | 1.7.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/blocking |
| borsh | 1.8.1 | MIT OR Apache-2.0 | https://github.com/near/borsh-rs |
| borsh-derive | 1.8.1 | Apache-2.0 | https://github.com/near/borsh-rs |
| brotli | 8.0.4 | BSD-3-Clause AND MIT | https://github.com/dropbox/rust-brotli |
| brotli | 9.0.0 | BSD-3-Clause AND MIT | https://github.com/dropbox/rust-brotli |
| brotli-decompressor | 5.0.3 | BSD-3-Clause/MIT | https://github.com/dropbox/rust-brotli-decompressor |
| brotli-decompressor | 6.0.1 | BSD-3-Clause/MIT | https://github.com/dropbox/rust-brotli-decompressor |
| bs58 | 0.5.1 | MIT/Apache-2.0 | https://github.com/Nullus157/bs58-rs |
| bumpalo | 3.20.3 | MIT OR Apache-2.0 | https://github.com/fitzgen/bumpalo |
| bytemuck | 1.25.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/Lokathor/bytemuck |
| bytemuck_derive | 1.12.1 | Zlib OR Apache-2.0 OR MIT | https://github.com/Lokathor/bytemuck |
| byteorder | 1.5.0 | Unlicense OR MIT | https://github.com/BurntSushi/byteorder |
| byteorder-lite | 0.1.0 | Unlicense OR MIT | https://github.com/image-rs/byteorder-lite |
| bytes | 1.12.1 | MIT | https://github.com/tokio-rs/bytes |
| cairo-rs | 0.18.5 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| cairo-sys-rs | 0.18.2 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| camino | 1.2.6 | MIT OR Apache-2.0 | https://github.com/camino-rs/camino |
| cargo-platform | 0.1.9 | MIT OR Apache-2.0 | https://github.com/rust-lang/cargo |
| cargo_metadata | 0.19.2 | MIT | https://github.com/oli-obk/cargo_metadata |
| cargo_toml | 1.0.1 | Apache-2.0 OR MIT | https://gitlab.com/lib.rs/cargo_toml |
| cbc | 0.1.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-modes |
| cbc | 0.2.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-modes |
| cc | 1.8.0 | MIT OR Apache-2.0 | https://github.com/rust-lang/cc-rs |
| cesu8 | 1.1.0 | Apache-2.0/MIT | https://github.com/emk/cesu8-rs |
| cfb | 0.14.0 | MIT | https://github.com/mdsteele/rust-cfb |
| cfg-expr | 0.15.8 | MIT OR Apache-2.0 | https://github.com/EmbarkStudios/cfg-expr |
| cfg-if | 1.0.5 | MIT OR Apache-2.0 | https://github.com/rust-lang/cfg-if |
| cfg_aliases | 0.2.2 | MIT | https://github.com/katharostech/cfg_aliases |
| chacha20 | 0.10.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/stream-ciphers |
| chrono | 0.4.45 | MIT OR Apache-2.0 | https://github.com/chronotope/chrono |
| chunked_transfer | 1.5.0 | MIT OR Apache-2.0 | https://github.com/frewsxcv/rust-chunked-transfer |
| cipher | 0.4.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| cipher | 0.5.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| cms | 0.2.3 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/cms |
| color | 0.3.3 | Apache-2.0 OR MIT | https://github.com/linebender/color |
| color_quant | 1.1.0 | MIT | https://github.com/image-rs/color_quant.git |
| combine | 4.6.8 | MIT | https://github.com/Marwes/combine |
| concurrent-queue | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/concurrent-queue |
| const-oid | 0.9.6 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/const-oid |
| const-oid | 0.10.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats |
| cookie | 0.18.2 | MIT OR Apache-2.0 | https://github.com/SergioBenitez/cookie-rs |
| core-foundation | 0.9.4 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-foundation | 0.10.1 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-foundation-sys | 0.8.7 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-graphics | 0.25.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core-graphics-types | 0.2.0 | MIT OR Apache-2.0 | https://github.com/servo/core-foundation-rs |
| core_detect | 1.0.0 | MIT/Apache-2.0 | https://github.com/thomcc/core_detect |
| cpubits | 0.1.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| cpufeatures | 0.2.17 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| cpufeatures | 0.3.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| crc32fast | 1.5.2 | MIT OR Apache-2.0 | https://github.com/srijs/rust-crc32fast |
| crossbeam-channel | 0.5.17 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-deque | 0.8.8 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-epoch | 0.9.21 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crossbeam-utils | 0.8.23 | MIT OR Apache-2.0 | https://github.com/crossbeam-rs/crossbeam |
| crunchy | 0.2.4 | MIT | https://github.com/eira-fransham/crunchy |
| crypto-bigint | 0.5.5 | Apache-2.0 OR MIT | https://github.com/RustCrypto/crypto-bigint |
| crypto-common | 0.1.6 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| crypto-common | 0.1.7 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| crypto-common | 0.2.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| cryptoki | 0.12.1 | Apache-2.0 | https://github.com/parallaxsecond/rust-cryptoki |
| cryptoki-sys | 0.5.0 | Apache-2.0 | https://github.com/parallaxsecond/rust-cryptoki |
| cssparser | 0.37.0 | MPL-2.0 | https://github.com/servo/rust-cssparser |
| cssparser-macros | 0.7.1 | MPL-2.0 | https://github.com/servo/rust-cssparser |
| ctor | 1.0.13 | Apache-2.0 OR MIT | https://github.com/mmastrac/linktime |
| darling | 0.24.1 | MIT | https://github.com/TedDriggs/darling |
| darling_core | 0.24.1 | MIT | https://github.com/TedDriggs/darling |
| darling_macro | 0.24.1 | MIT | https://github.com/TedDriggs/darling |
| dbus | 0.9.12 | Apache-2.0/MIT | https://github.com/diwic/dbus-rs |
| defmt | 1.1.1 | MIT OR Apache-2.0 | https://github.com/knurling-rs/defmt |
| defmt-macros | 1.1.1 | MIT OR Apache-2.0 | https://github.com/knurling-rs/defmt |
| defmt-parser | 1.0.0 | MIT OR Apache-2.0 | https://github.com/knurling-rs/defmt |
| der | 0.7.10 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/der |
| der_derive | 0.7.3 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/der/derive |
| deranged | 0.5.8 | MIT OR Apache-2.0 | https://github.com/jhpratt/deranged |
| derive-new | 0.7.0 | MIT | https://github.com/nrc/derive-new |
| derive_more | 2.1.1 | MIT | https://github.com/JelteF/derive_more |
| derive_more-impl | 2.1.1 | MIT | https://github.com/JelteF/derive_more |
| des | 0.8.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| digest | 0.10.7 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| digest | 0.11.3 | MIT OR Apache-2.0 | https://github.com/RustCrypto/traits |
| dirs | 7.0.0 | MIT OR Apache-2.0 | https://codeberg.org/dirs/dirs-rs |
| dirs-sys | 0.5.0 | MIT OR Apache-2.0 | https://github.com/dirs-dev/dirs-sys-rs |
| dispatch2 | 0.3.1 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| displaydoc | 0.2.7 | MIT OR Apache-2.0 | https://github.com/yaahc/displaydoc |
| dlopen2 | 0.8.2 | MIT | https://github.com/OpenByteDev/dlopen2 |
| dlopen2_derive | 0.4.3 | MIT | https://github.com/OpenByteDev/dlopen2 |
| dom_query | 0.28.0 | MIT | https://github.com/niklak/dom_query |
| downcast-rs | 2.0.2 | MIT OR Apache-2.0 | https://github.com/marcianx/downcast-rs |
| dpi | 0.1.2 | Apache-2.0 AND MIT | https://github.com/rust-windowing/winit |
| dtoa | 1.0.11 | MIT OR Apache-2.0 | https://github.com/dtolnay/dtoa |
| dtoa-short | 0.3.5 | MPL-2.0 | https://github.com/upsuper/dtoa-short |
| dunce | 1.0.5 | CC0-1.0 OR MIT-0 OR Apache-2.0 | https://gitlab.com/kornelski/dunce |
| dyn-clone | 1.0.20 | MIT OR Apache-2.0 | https://github.com/dtolnay/dyn-clone |
| dyn-hash | 1.0.0 | MIT OR Apache-2.0 | https://github.com/dtolnay/dyn-hash |
| ecb | 0.2.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-modes |
| ecdsa | 0.16.9 | Apache-2.0 OR MIT | https://github.com/RustCrypto/signatures/tree/master/ecdsa |
| either | 1.19.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/either |
| elliptic-curve | 0.13.8 | Apache-2.0 OR MIT | https://github.com/RustCrypto/traits/tree/master/elliptic-curve |
| embed-resource | 3.0.12 | MIT | https://github.com/nabijaczleweli/rust-embed-resource |
| embed_plist | 1.2.2 | MIT OR Apache-2.0 | https://github.com/nvzqz/embed-plist-rs |
| encoding_rs | 0.8.42 | (Apache-2.0 OR MIT) AND BSD-3-Clause | https://github.com/hsivonen/encoding_rs |
| endi | 1.1.1 | MIT | https://github.com/zeenix/endi |
| enumflags2 | 0.7.12 | MIT OR Apache-2.0 | https://github.com/meithecatte/enumflags2 |
| enumflags2_derive | 0.7.12 | MIT OR Apache-2.0 | https://github.com/meithecatte/enumflags2 |
| equivalent | 1.0.2 | Apache-2.0 OR MIT | https://github.com/indexmap-rs/equivalent |
| erased-serde | 0.4.10 | MIT OR Apache-2.0 | https://github.com/dtolnay/erased-serde |
| errno | 0.3.14 | MIT OR Apache-2.0 | https://github.com/lambda-fairy/rust-errno |
| euclid | 0.22.14 | MIT OR Apache-2.0 | https://github.com/servo/euclid |
| event-listener | 5.4.2 | Apache-2.0 OR MIT | https://github.com/smol-rs/event-listener |
| event-listener-strategy | 0.5.4 | Apache-2.0 OR MIT | https://github.com/smol-rs/event-listener-strategy |
| fastrand | 2.5.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/fastrand |
| fdeflate | 0.3.7 | MIT OR Apache-2.0 | https://github.com/image-rs/fdeflate |
| fearless_simd | 0.7.0 | Apache-2.0 OR MIT | https://github.com/linebender/fearless_simd |
| fearless_simd | 1.1.0 | Apache-2.0 OR MIT | https://github.com/linebender/fearless_simd |
| ff | 0.13.1 | MIT/Apache-2.0 | https://github.com/zkcrypto/ff |
| field-offset | 0.3.6 | MIT OR Apache-2.0 | https://github.com/Diggsey/rust-field-offset |
| filetime | 0.2.30 | MIT/Apache-2.0 | https://github.com/alexcrichton/filetime |
| find-msvc-tools | 0.1.14 | MIT OR Apache-2.0 | https://github.com/rust-lang/cc-rs |
| flagset | 0.4.7 | Apache-2.0 | https://github.com/enarx/flagset |
| flate2 | 1.1.10 | MIT OR Apache-2.0 | https://github.com/rust-lang/flate2-rs |
| float-cmp | 0.9.0 | MIT | https://github.com/mikedilger/float-cmp |
| float-ord | 0.3.2 | MIT / Apache-2.0 | https://github.com/notriddle/rust-float-ord |
| fnv | 1.0.7 | Apache-2.0 / MIT | https://github.com/servo/rust-fnv |
| foldhash | 0.2.0 | Zlib | https://github.com/orlp/foldhash |
| font-types | 0.11.3 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| font-types | 0.12.6 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| foreign-types | 0.5.0 | MIT/Apache-2.0 | https://github.com/sfackler/foreign-types |
| foreign-types-macros | 0.2.4 | MIT/Apache-2.0 | https://github.com/sfackler/foreign-types |
| foreign-types-shared | 0.3.1 | MIT/Apache-2.0 | https://github.com/sfackler/foreign-types |
| form_urlencoded | 1.2.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-url |
| futures-channel | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-core | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-executor | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-io | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-lite | 2.6.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/futures-lite |
| futures-macro | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-sink | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-task | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| futures-util | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/futures-rs |
| gdk | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gdk-pixbuf | 0.18.5 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| gdk-pixbuf-sys | 0.18.0 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| gdk-sys | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gdkwayland-sys | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gdkx11 | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gdkx11-sys | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| generic-array | 0.14.7 | MIT | https://github.com/fizyk20/generic-array.git |
| generic-array | 0.14.9 | MIT | https://github.com/fizyk20/generic-array.git |
| getrandom | 0.2.17 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| getrandom | 0.3.4 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| getrandom | 0.4.3 | MIT OR Apache-2.0 | https://github.com/rust-random/getrandom |
| gif | 0.14.2 | MIT OR Apache-2.0 | https://github.com/image-rs/image-gif |
| gio | 0.18.4 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| gio-sys | 0.18.1 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| glib | 0.18.5 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| glib-macros | 0.18.5 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| glib-sys | 0.18.1 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| glifo | 0.4.0 | Apache-2.0 OR MIT | https://github.com/linebender/vello |
| glob | 0.3.4 | MIT OR Apache-2.0 | https://github.com/rust-lang/glob |
| gobject-sys | 0.18.0 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| group | 0.13.0 | MIT/Apache-2.0 | https://github.com/zkcrypto/group |
| gtk | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gtk-sys | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| gtk3-macros | 0.18.2 | MIT | https://github.com/gtk-rs/gtk3-rs |
| guillotiere | 0.7.0 | MIT/Apache-2.0 | https://github.com/nical/guillotiere |
| half | 2.7.1 | MIT OR Apache-2.0 | https://github.com/VoidStarKat/half-rs |
| harfrust | 0.14.0 | MIT | https://github.com/harfbuzz/harfrust |
| hashbrown | 0.12.3 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hashbrown | 0.16.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hashbrown | 0.17.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/hashbrown |
| hayro | 0.8.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-ccitt | 0.4.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-cmap | 0.1.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-interpret | 0.8.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-jbig2 | 0.3.1 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-jpeg2000 | 0.4.1 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-postscript | 0.1.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| hayro-syntax | 0.8.0 | Apache-2.0 OR MIT | https://github.com/LaurenzV/hayro |
| heck | 0.4.1 | MIT OR Apache-2.0 | https://github.com/withoutboats/heck |
| heck | 0.5.0 | MIT OR Apache-2.0 | https://github.com/withoutboats/heck |
| hermit-abi | 0.5.3 | MIT OR Apache-2.0 | https://github.com/hermit-os/hermit-rs |
| hex | 0.4.3 | MIT OR Apache-2.0 | https://github.com/KokaKiwi/rust-hex |
| hkdf | 0.12.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/KDFs/ |
| hmac | 0.12.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/MACs |
| html5ever | 0.39.0 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| http | 1.5.0 | MIT OR Apache-2.0 | https://github.com/hyperium/http |
| http-body | 1.1.0 | MIT | https://github.com/hyperium/http-body |
| http-body-util | 0.1.5 | MIT | https://github.com/hyperium/http-body |
| httparse | 1.10.1 | MIT OR Apache-2.0 | https://github.com/seanmonstar/httparse |
| httpdate | 1.0.3 | MIT OR Apache-2.0 | https://github.com/pyfisch/httpdate |
| hybrid-array | 0.4.15 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hybrid-array |
| hyper | 1.12.0 | MIT | https://github.com/hyperium/hyper |
| hyper-rustls | 0.27.10 | Apache-2.0 OR ISC OR MIT | https://github.com/rustls/hyper-rustls |
| hyper-util | 0.1.21 | MIT | https://github.com/hyperium/hyper-util |
| hypher | 0.1.8 | MIT OR Apache-2.0 | https://github.com/typst/hypher |
| i_float | 1.16.0 | MIT | https://github.com/iShape-Rust/iFloat |
| i_key_sort | 0.10.3 | MIT | https://github.com/iShape-Rust/iKeySort |
| i_overlay | 4.5.2 | MIT OR Apache-2.0 | https://github.com/iShape-Rust/iOverlay |
| i_shape | 1.18.0 | MIT | https://github.com/iShape-Rust/iShape |
| i_tree | 0.18.0 | MIT | https://github.com/iShape-Rust/iTree |
| iana-time-zone | 0.1.65 | MIT OR Apache-2.0 | https://github.com/strawlab/iana-time-zone |
| iana-time-zone-haiku | 0.1.2 | MIT OR Apache-2.0 | https://github.com/strawlab/iana-time-zone |
| ico | 0.5.0 | MIT | https://github.com/mdsteele/rust-ico |
| icu_collections | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_locale_core | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_normalizer | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_normalizer_data | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_properties | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_properties_data | 2.3.0 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| icu_provider | 2.3.1 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| ident_case | 1.0.1 | MIT/Apache-2.0 | https://github.com/TedDriggs/ident_case |
| idna | 1.1.0 | MIT OR Apache-2.0 | https://github.com/servo/rust-url/ |
| idna_adapter | 1.2.2 | Apache-2.0 OR MIT | https://github.com/hsivonen/idna_adapter |
| image | 0.25.10 | MIT OR Apache-2.0 | https://github.com/image-rs/image |
| image-webp | 0.2.4 | MIT OR Apache-2.0 | https://github.com/image-rs/image-webp |
| imagesize | 0.14.0 | MIT | https://github.com/Roughsketch/imagesize |
| indexmap | 1.9.3 | Apache-2.0 OR MIT | https://github.com/bluss/indexmap |
| indexmap | 2.14.2 | Apache-2.0 OR MIT | https://github.com/indexmap-rs/indexmap |
| infer | 0.22.0 | MIT | https://github.com/bojand/infer |
| inout | 0.1.4 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| inout | 0.2.2 | MIT OR Apache-2.0 | https://github.com/RustCrypto/utils |
| inventory | 0.3.25 | MIT OR Apache-2.0 | https://github.com/dtolnay/inventory |
| ipnet | 2.12.2 | MIT OR Apache-2.0 | https://github.com/krisprice/ipnet |
| itertools | 0.15.0 | MIT OR Apache-2.0 | https://github.com/rust-itertools/itertools |
| itoa | 1.0.18 | MIT OR Apache-2.0 | https://github.com/dtolnay/itoa |
| javascriptcore-rs | 1.1.2 | MIT | https://github.com/tauri-apps/javascriptcore-rs |
| javascriptcore-rs-sys | 1.1.1 | MIT | https://github.com/tauri-apps/javascriptcore-rs |
| jiff | 0.2.38 | Unlicense OR MIT | https://github.com/BurntSushi/jiff |
| jiff-core | 0.1.1 | Unlicense OR MIT | https://github.com/BurntSushi/jiff |
| jiff-static | 0.2.38 | Unlicense OR MIT | https://github.com/BurntSushi/jiff |
| jiff-tzdb | 0.1.9 | Unlicense OR MIT | https://github.com/BurntSushi/jiff |
| jiff-tzdb-platform | 0.1.3 | Unlicense OR MIT | https://github.com/BurntSushi/jiff |
| jni | 0.21.1 | MIT/Apache-2.0 | https://github.com/jni-rs/jni-rs |
| jni | 0.22.4 | MIT OR Apache-2.0 | https://github.com/jni-rs/jni-rs |
| jni-macros | 0.22.4 | MIT OR Apache-2.0 | https://github.com/jni-rs/jni-rs |
| jni-sys | 0.3.1 | MIT OR Apache-2.0 | https://github.com/jni-rs/jni-sys |
| jni-sys | 0.4.1 | MIT OR Apache-2.0 | https://github.com/jni-rs/jni-sys |
| jni-sys-macros | 0.4.1 | MIT OR Apache-2.0 | https://github.com/jni-rs/jni-sys |
| jpeg-encoder | 0.7.1 | (MIT OR Apache-2.0) AND IJG | https://github.com/vstroebel/jpeg-encoder |
| js-sys | 0.3.106 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/js-sys |
| json-patch | 4.2.0 | MIT/Apache-2.0 | https://github.com/idubrov/json-patch |
| jsonptr | 0.7.1 | MIT OR Apache-2.0 | https://github.com/chanced/jsonptr |
| keccak | 0.1.6 | Apache-2.0 OR MIT | https://github.com/RustCrypto/sponges/tree/master/keccak |
| keyboard-types | 0.8.3 | MIT OR Apache-2.0 | https://github.com/rust-windowing/keyboard-types |
| krilla | 0.8.2 | MIT OR Apache-2.0 | https://github.com/LaurenzV/krilla |
| kurbo | 0.13.1 | Apache-2.0 OR MIT | https://github.com/linebender/kurbo |
| lazy_static | 1.5.1 | MIT OR Apache-2.0 | https://github.com/rust-lang-nursery/lazy-static.rs |
| libappindicator | 0.9.0 | Apache-2.0 OR MIT |  |
| libappindicator-sys | 0.9.0 | Apache-2.0 OR MIT |  |
| libc | 0.2.190 | MIT OR Apache-2.0 | https://github.com/rust-lang/libc |
| libdbus-sys | 0.2.7 | Apache-2.0/MIT | https://github.com/diwic/dbus-rs |
| libloading | 0.7.4 | ISC | https://github.com/nagisa/rust_libloading/ |
| libloading | 0.8.9 | ISC | https://github.com/nagisa/rust_libloading/ |
| libm | 0.2.16 | MIT | https://github.com/rust-lang/compiler-builtins |
| libredox | 0.1.25 | MIT | https://gitlab.redox-os.org/redox-os/libredox.git |
| linebender_resource_handle | 0.1.1 | Apache-2.0 OR MIT | https://github.com/linebender/raw_resource_handle |
| linux-raw-sys | 0.12.1 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/sunfishcode/linux-raw-sys |
| litemap | 0.8.3 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| lock_api | 0.4.14 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| log | 0.4.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/log |
| lopdf | 0.45.0 | MIT | https://github.com/J-F-Liu/lopdf.git |
| maplit | 1.0.2 | MIT/Apache-2.0 | https://github.com/bluss/maplit |
| markup5ever | 0.39.0 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| matrixmultiply | 0.3.11 | MIT/Apache-2.0 | https://github.com/bluss/matrixmultiply/ |
| md-5 | 0.11.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| memchr | 2.8.3 | Unlicense OR MIT | https://github.com/BurntSushi/memchr |
| memmap2 | 0.9.12 | MIT OR Apache-2.0 | https://github.com/RazrFalcon/memmap2-rs |
| memoffset | 0.9.1 | MIT | https://github.com/Gilnaa/memoffset |
| metrics | 0.24.6 | MIT | https://github.com/metrics-rs/metrics |
| mime | 0.3.17 | MIT OR Apache-2.0 | https://github.com/hyperium/mime |
| minijinja | 3.1.0 | Apache-2.0 | https://github.com/mitsuhiko/minijinja |
| minisign-verify | 0.3.0 | MIT | https://github.com/jedisct1/rust-minisign-verify |
| miniz_oxide | 0.8.9 | MIT OR Zlib OR Apache-2.0 | https://github.com/Frommi/miniz_oxide/tree/master/miniz_oxide |
| miniz_oxide | 0.9.1 | MIT OR Zlib OR Apache-2.0 | https://github.com/Frommi/miniz_oxide/tree/master/miniz_oxide |
| mio | 1.2.4 | MIT | https://github.com/tokio-rs/mio |
| moxcms | 0.8.1 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/moxcms.git |
| muda | 0.20.0 | Apache-2.0 OR MIT | https://github.com/tauri-apps/muda |
| multiversion_no_op | 1.0.0 | Apache-2.0 OR MIT | https://github.com/hsivonen/multiversion_no_op |
| ndarray | 0.17.2 | MIT OR Apache-2.0 | https://github.com/rust-ndarray/ndarray |
| ndk | 0.9.0 | MIT OR Apache-2.0 | https://github.com/rust-mobile/ndk |
| ndk-context | 0.1.1 | MIT OR Apache-2.0 | https://github.com/rust-windowing/android-ndk-rs |
| ndk-sys | 0.6.0+11769913 | MIT OR Apache-2.0 | https://github.com/rust-mobile/ndk |
| new_debug_unreachable | 1.0.6 | MIT | https://github.com/mbrubeck/rust-debug-unreachable |
| nix | 0.31.3 | MIT | https://github.com/nix-rust/nix |
| nom | 8.0.0 | MIT | https://github.com/rust-bakery/nom |
| nom-language | 0.1.0 | MIT | https://github.com/rust-bakery/nom |
| num-bigint | 0.4.8 | MIT OR Apache-2.0 | https://github.com/rust-num/num-bigint |
| num-bigint-dig | 0.8.6 | MIT/Apache-2.0 | https://github.com/dignifiedquire/num-bigint |
| num-complex | 0.4.6 | MIT OR Apache-2.0 | https://github.com/rust-num/num-complex |
| num-conv | 0.2.2 | MIT OR Apache-2.0 | https://github.com/jhpratt/num-conv |
| num-integer | 0.1.47 | MIT OR Apache-2.0 | https://github.com/rust-num/num-integer |
| num-iter | 0.1.46 | MIT OR Apache-2.0 | https://github.com/rust-num/num-iter |
| num-rational | 0.4.2 | MIT OR Apache-2.0 | https://github.com/rust-num/num-rational |
| num-traits | 0.2.19 | MIT OR Apache-2.0 | https://github.com/rust-num/num-traits |
| num_enum | 0.7.6 | BSD-3-Clause OR MIT OR Apache-2.0 | https://github.com/illicitonion/num_enum |
| num_enum_derive | 0.7.6 | BSD-3-Clause OR MIT OR Apache-2.0 | https://github.com/illicitonion/num_enum |
| objc2 | 0.6.5 | MIT | https://github.com/madsmtm/objc2 |
| objc2-app-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-cloud-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-data | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-foundation | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-graphics | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-image | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-location | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-core-text | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-encode | 4.1.0 | MIT | https://github.com/madsmtm/objc2 |
| objc2-exception-helper | 0.1.1 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-foundation | 0.3.2 | MIT | https://github.com/madsmtm/objc2 |
| objc2-io-surface | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-osa-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-quartz-core | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-ui-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-user-notifications | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| objc2-web-kit | 0.3.2 | Zlib OR Apache-2.0 OR MIT | https://github.com/madsmtm/objc2 |
| once_cell | 1.21.4 | MIT OR Apache-2.0 | https://github.com/matklad/once_cell |
| openssl-probe | 0.2.2 | MIT OR Apache-2.0 | https://github.com/rustls/openssl-probe |
| option-ext | 0.2.0 | MPL-2.0 | https://github.com/soc/option-ext.git |
| ordered-stream | 0.2.0 | MIT OR Apache-2.0 | https://github.com/danieldg/ordered-stream |
| osakit | 0.3.1 | MIT OR Apache-2.0 | https://github.com/mdevils/rust-osakit |
| p256 | 0.13.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/elliptic-curves/tree/master/p256 |
| pango | 0.18.3 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| pango-sys | 0.18.0 | MIT | https://github.com/gtk-rs/gtk-rs-core |
| parking | 2.2.1 | Apache-2.0 OR MIT | https://github.com/smol-rs/parking |
| parking_lot | 0.12.5 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| parking_lot_core | 0.9.12 | MIT OR Apache-2.0 | https://github.com/Amanieu/parking_lot |
| pastey | 0.2.3 | MIT OR Apache-2.0 | https://github.com/as1100k/pastey |
| pdf-writer | 0.15.0 | MIT OR Apache-2.0 | https://github.com/typst/pdf-writer |
| pem-rfc7468 | 0.7.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/pem-rfc7468 |
| peniko | 0.6.1 | Apache-2.0 OR MIT | https://github.com/linebender/peniko |
| percent-encoding | 2.3.2 | MIT OR Apache-2.0 | https://github.com/servo/rust-url/ |
| phf | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_codegen | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_generator | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_macros | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| phf_shared | 0.13.1 | MIT | https://github.com/rust-phf/rust-phf |
| pic-scale | 0.7.12 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/pic-scale |
| pin-project-lite | 0.2.17 | Apache-2.0 OR MIT | https://github.com/taiki-e/pin-project-lite |
| piper | 0.2.5 | MIT OR Apache-2.0 | https://github.com/smol-rs/piper |
| pkcs1 | 0.7.5 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/pkcs1 |
| pkcs8 | 0.10.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/pkcs8 |
| pkg-config | 0.3.34 | MIT OR Apache-2.0 | https://github.com/rust-lang/pkg-config-rs |
| plist | 1.10.1 | MIT | https://github.com/ebarnard/rust-plist/ |
| png | 0.17.16 | MIT OR Apache-2.0 | https://github.com/image-rs/image-png |
| png | 0.18.1 | MIT OR Apache-2.0 | https://github.com/image-rs/image-png |
| polling | 3.11.0 | Apache-2.0 OR MIT | https://github.com/smol-rs/polling |
| polycool | 0.4.0 | MIT OR Apache-2.0 | https://github.com/linebender/kurbo |
| portable-atomic | 1.15.0 | Apache-2.0 OR MIT | https://github.com/taiki-e/portable-atomic |
| portable-atomic-util | 0.2.8 | Apache-2.0 OR MIT | https://github.com/taiki-e/portable-atomic-util |
| potential_utf | 0.1.6 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| powerfmt | 0.2.1 | MIT OR Apache-2.0 | https://github.com/jhpratt/powerfmt |
| ppv-lite86 | 0.2.21 | MIT OR Apache-2.0 | https://github.com/cryptocorrosion/cryptocorrosion |
| precomputed-hash | 0.1.1 | MIT | https://github.com/emilio/precomputed-hash |
| primal-check | 0.3.4 | MIT OR Apache-2.0 | https://github.com/huonw/primal |
| primeorder | 0.13.6 | Apache-2.0 OR MIT | https://github.com/RustCrypto/elliptic-curves/tree/master/primeorder |
| proc-macro-crate | 1.3.1 | MIT OR Apache-2.0 | https://github.com/bkchr/proc-macro-crate |
| proc-macro-crate | 2.0.2 | MIT OR Apache-2.0 | https://github.com/bkchr/proc-macro-crate |
| proc-macro-crate | 3.5.0 | MIT OR Apache-2.0 | https://github.com/bkchr/proc-macro-crate |
| proc-macro-error | 1.0.4 | MIT OR Apache-2.0 | https://gitlab.com/CreepySkeleton/proc-macro-error |
| proc-macro-error-attr | 1.0.4 | MIT OR Apache-2.0 | https://gitlab.com/CreepySkeleton/proc-macro-error |
| proc-macro2 | 1.0.107 | MIT OR Apache-2.0 | https://github.com/dtolnay/proc-macro2 |
| prost | 0.14.6 | Apache-2.0 | https://github.com/tokio-rs/prost |
| prost-derive | 0.14.6 | Apache-2.0 | https://github.com/tokio-rs/prost |
| pxfm | 0.1.30 | BSD-3-Clause OR Apache-2.0 | https://github.com/awxkee/pxfm |
| quick-error | 2.0.1 | MIT/Apache-2.0 | http://github.com/tailhook/quick-error |
| quick-xml | 0.42.0 | MIT | https://github.com/tafia/quick-xml |
| quote | 1.0.47 | MIT OR Apache-2.0 | https://github.com/dtolnay/quote |
| r-efi | 5.3.0 | MIT OR Apache-2.0 OR LGPL-2.1-or-later | https://github.com/r-efi/r-efi |
| r-efi | 6.0.0 | MIT OR Apache-2.0 OR LGPL-2.1-or-later | https://github.com/r-efi/r-efi |
| rand | 0.8.8 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand | 0.10.3 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand_chacha | 0.3.1 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand_core | 0.6.4 | MIT OR Apache-2.0 | https://github.com/rust-random/rand |
| rand_core | 0.10.1 | MIT OR Apache-2.0 | https://github.com/rust-random/rand_core |
| rand_distr | 0.6.0 | MIT OR Apache-2.0 | https://github.com/rust-random/rand_distr |
| rangemap | 1.8.0 | MIT/Apache-2.0 | https://github.com/jeffparsons/rangemap |
| rapidhash | 4.5.1 | MIT OR Apache-2.0 | https://github.com/hoxxep/rapidhash |
| raw-window-handle | 0.6.2 | MIT OR Apache-2.0 OR Zlib | https://github.com/rust-windowing/raw-window-handle |
| rawpointer | 0.2.1 | MIT/Apache-2.0 | https://github.com/bluss/rawpointer/ |
| rayon | 1.12.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/rayon |
| rayon-core | 1.13.0 | MIT OR Apache-2.0 | https://github.com/rayon-rs/rayon |
| rc2 | 0.8.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/block-ciphers |
| read-fonts | 0.39.2 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| read-fonts | 0.41.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| read-fonts | 0.43.3 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| read-fonts | 0.45.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| redox_syscall | 0.5.18 | MIT | https://gitlab.redox-os.org/redox-os/syscall |
| redox_users | 0.5.3 | MIT | https://gitlab.redox-os.org/redox-os/users |
| ref-cast | 1.0.27 | MIT OR Apache-2.0 | https://github.com/dtolnay/ref-cast |
| ref-cast-impl | 1.0.27 | MIT OR Apache-2.0 | https://github.com/dtolnay/ref-cast |
| regex | 1.13.1 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| regex-automata | 0.4.18 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| regex-syntax | 0.8.11 | MIT OR Apache-2.0 | https://github.com/rust-lang/regex |
| reqwest | 0.13.5 | MIT OR Apache-2.0 | https://github.com/seanmonstar/reqwest |
| rfc6979 | 0.4.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/signatures/tree/master/rfc6979 |
| rfd | 0.17.2 | MIT | https://github.com/PolyMeilex/rfd |
| ring | 0.17.14 | Apache-2.0 AND ISC | https://github.com/briansmith/ring |
| rsa | 0.9.10 | MIT OR Apache-2.0 | https://github.com/RustCrypto/RSA |
| rustc-hash | 2.1.3 | Apache-2.0 OR MIT | https://github.com/rust-lang/rustc-hash |
| rustc_version | 0.4.1 | MIT OR Apache-2.0 | https://github.com/djc/rustc-version-rs |
| rustfft | 6.4.1 | MIT OR Apache-2.0 | https://github.com/ejmahler/RustFFT |
| rustix | 1.1.6 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/bytecodealliance/rustix |
| rustls | 0.23.46 | Apache-2.0 OR ISC OR MIT | https://github.com/rustls/rustls |
| rustls-native-certs | 0.8.5 | Apache-2.0 OR ISC OR MIT | https://github.com/rustls/rustls-native-certs |
| rustls-pki-types | 1.16.0 | MIT OR Apache-2.0 | https://github.com/rustls/pki-types |
| rustls-platform-verifier | 0.7.1 | MIT OR Apache-2.0 | https://github.com/rustls/rustls-platform-verifier |
| rustls-platform-verifier-android | 0.2.0 | MIT OR Apache-2.0 | https://github.com/rustls/rustls-platform-verifier |
| rustls-webpki | 0.103.17 | ISC | https://github.com/rustls/webpki |
| rustversion | 1.0.23 | MIT OR Apache-2.0 | https://github.com/dtolnay/rustversion |
| ryu | 1.0.23 | Apache-2.0 OR BSL-1.0 | https://github.com/dtolnay/ryu |
| same-file | 1.0.6 | Unlicense/MIT | https://github.com/BurntSushi/same-file |
| schannel | 0.1.30 | MIT | https://github.com/steffengy/schannel-rs |
| schemars | 0.8.22 | MIT | https://github.com/GREsau/schemars |
| schemars | 0.9.0 | MIT | https://github.com/GREsau/schemars |
| schemars | 1.2.3 | MIT | https://github.com/GREsau/schemars |
| schemars_derive | 0.8.22 | MIT | https://github.com/GREsau/schemars |
| scopeguard | 1.2.0 | MIT OR Apache-2.0 | https://github.com/bluss/scopeguard |
| sec1 | 0.7.3 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/sec1 |
| secrecy | 0.10.3 | Apache-2.0 OR MIT | https://github.com/iqlusioninc/crates/tree/main/secrecy |
| security-framework | 3.7.0 | MIT OR Apache-2.0 | https://github.com/kornelski/rust-security-framework |
| security-framework-sys | 2.17.0 | MIT OR Apache-2.0 | https://github.com/kornelski/rust-security-framework |
| selectors | 0.38.0 | MPL-2.0 | https://github.com/servo/stylo |
| self_cell | 1.3.0 | Apache-2.0 OR GPL-2.0-only | https://github.com/Voultapher/self_cell |
| semver | 1.0.28 | MIT OR Apache-2.0 | https://github.com/dtolnay/semver |
| serde | 1.0.229 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde-untagged | 0.1.9 | MIT OR Apache-2.0 | https://github.com/dtolnay/serde-untagged |
| serde_core | 1.0.229 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde_derive | 1.0.229 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde_derive_internals | 0.29.1 | MIT OR Apache-2.0 | https://github.com/serde-rs/serde |
| serde_json | 1.0.154 | MIT OR Apache-2.0 | https://github.com/serde-rs/json |
| serde_repr | 0.1.21 | MIT OR Apache-2.0 | https://github.com/dtolnay/serde-repr |
| serde_spanned | 0.6.9 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| serde_spanned | 1.1.2 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| serde_with | 3.24.0 | MIT OR Apache-2.0 | https://github.com/jonasbb/serde_with/ |
| serde_with_macros | 3.24.0 | MIT OR Apache-2.0 | https://github.com/jonasbb/serde_with/ |
| serialize-to-javascript | 0.1.2 | MIT OR Apache-2.0 | https://github.com/chippers/serialize-to-javascript |
| serialize-to-javascript-impl | 0.1.2 | MIT OR Apache-2.0 | https://github.com/chippers/serialize-to-javascript |
| servo_arc | 0.4.3 | MIT OR Apache-2.0 | https://github.com/servo/stylo |
| sha1 | 0.10.7 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha2 | 0.10.9 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha2 | 0.11.0 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha2 | 0.11.1 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| sha3 | 0.10.9 | MIT OR Apache-2.0 | https://github.com/RustCrypto/hashes |
| shlex | 2.0.1 | MIT OR Apache-2.0 | https://github.com/comex/rust-shlex |
| signal-hook-registry | 1.4.8 | MIT OR Apache-2.0 | https://github.com/vorner/signal-hook |
| signature | 2.2.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/traits/tree/master/signature |
| simd-adler32 | 0.3.10 | MIT | https://github.com/mcountryman/simd-adler32 |
| simd_cesu8 | 1.2.0 | Apache-2.0 OR MIT | https://github.com/seancroach/simd_cesu8 |
| simdutf8 | 0.1.5 | MIT OR Apache-2.0 | https://github.com/rusticstuff/simdutf8 |
| siphasher | 1.0.4 | MIT OR Apache-2.0 | https://github.com/jedisct1/rust-siphash |
| skrifa | 0.42.1 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| skrifa | 0.44.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| skrifa | 0.46.2 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| skrifa | 0.48.0 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| slab | 0.4.12 | MIT | https://github.com/tokio-rs/slab |
| smallvec | 1.16.3 | MIT OR Apache-2.0 | https://github.com/servo/rust-smallvec |
| snap | 1.1.2 | BSD-3-Clause | https://github.com/BurntSushi/rust-snappy |
| socket2 | 0.6.5 | MIT OR Apache-2.0 | https://github.com/rust-lang/socket2 |
| softbuffer | 0.4.8 | MIT OR Apache-2.0 | https://github.com/rust-windowing/softbuffer |
| soup3 | 0.5.0 | MIT | https://gitlab.gnome.org/World/Rust/soup3-rs |
| soup3-sys | 0.5.0 | MIT | https://gitlab.gnome.org/World/Rust/soup3-rs |
| spin | 0.9.9 | MIT | https://github.com/mvdnes/spin-rs.git |
| spki | 0.7.3 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/spki |
| stable_deref_trait | 1.2.1 | MIT OR Apache-2.0 | https://github.com/storyyeller/stable_deref_trait |
| strength_reduce | 0.2.4 | MIT OR Apache-2.0 | http://github.com/ejmahler/strength_reduce |
| strict-num | 0.1.1 | MIT | https://github.com/RazrFalcon/strict-num |
| string-interner | 0.20.0 | MIT/Apache-2.0 | https://github.com/robbepop/string-interner |
| string_cache | 0.9.0 | MIT OR Apache-2.0 | https://github.com/servo/string-cache |
| string_cache_codegen | 0.6.1 | MIT OR Apache-2.0 | https://github.com/servo/string-cache |
| stringprep | 0.1.5 | MIT/Apache-2.0 | https://github.com/sfackler/rust-stringprep |
| strsim | 0.11.1 | MIT | https://github.com/rapidfuzz/strsim-rs |
| subsetter | 0.2.6 | MIT OR Apache-2.0 | https://github.com/typst/subsetter |
| subtle | 2.6.1 | BSD-3-Clause | https://github.com/dalek-cryptography/subtle |
| swift-rs | 1.0.9 | MIT OR Apache-2.0 | https://github.com/Brendonovich/swift-rs |
| syn | 1.0.109 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| syn | 2.0.119 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| syn | 3.0.8 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| syn | 3.0.9 | MIT OR Apache-2.0 | https://github.com/dtolnay/syn |
| sync_wrapper | 1.0.2 | Apache-2.0 | https://github.com/Actyx/sync_wrapper |
| synstructure | 0.14.0 | MIT | https://github.com/mystor/synstructure |
| system-configuration | 0.7.0 | MIT OR Apache-2.0 | https://github.com/mullvad/system-configuration-rs |
| system-configuration-sys | 0.6.0 | MIT OR Apache-2.0 | https://github.com/mullvad/system-configuration-rs |
| system-deps | 6.2.2 | MIT OR Apache-2.0 | https://github.com/gdesmott/system-deps |
| tao | 0.37.1 | Apache-2.0 | https://github.com/tauri-apps/tao |
| tao-macros | 0.1.4 | MIT OR Apache-2.0 | https://github.com/tauri-apps/tao |
| tar | 0.4.46 | MIT OR Apache-2.0 | https://github.com/composefs/tar-rs |
| target-lexicon | 0.12.16 | Apache-2.0 WITH LLVM-exception | https://github.com/bytecodealliance/target-lexicon |
| tauri | 2.12.3 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-build | 2.7.2 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-codegen | 2.7.2 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-macros | 2.7.2 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-plugin | 2.7.2 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-plugin-dialog | 2.8.4 | Apache-2.0 OR MIT | https://github.com/tauri-apps/plugins-workspace |
| tauri-plugin-fs | 2.7.1 | Apache-2.0 OR MIT | https://github.com/tauri-apps/plugins-workspace |
| tauri-plugin-single-instance | 2.5.5 | Apache-2.0 OR MIT | https://github.com/tauri-apps/plugins-workspace |
| tauri-plugin-updater | 2.14.1 | Apache-2.0 OR MIT | https://github.com/tauri-apps/plugins-workspace |
| tauri-runtime | 2.12.1 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-runtime-wry | 2.12.1 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-utils | 2.10.2 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri |
| tauri-winres | 0.3.6 | MIT | https://github.com/tauri-apps/winres |
| tempfile | 3.27.0 | MIT OR Apache-2.0 | https://github.com/Stebalien/tempfile |
| tendril | 0.5.1 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| thiserror | 1.0.69 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| thiserror | 2.0.21 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| thiserror-impl | 1.0.69 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| thiserror-impl | 2.0.21 | MIT OR Apache-2.0 | https://github.com/dtolnay/thiserror |
| time | 0.3.55 | MIT OR Apache-2.0 | https://github.com/time-rs/time |
| time-core | 0.1.9 | MIT OR Apache-2.0 | https://github.com/time-rs/time |
| time-macros | 0.2.32 | MIT OR Apache-2.0 | https://github.com/time-rs/time |
| tiny-skia-path | 0.12.0 | BSD-3-Clause | https://github.com/linebender/tiny-skia/tree/master/path |
| tiny_http | 0.12.0 | MIT OR Apache-2.0 | https://github.com/tiny-http/tiny-http |
| tinystr | 0.8.4 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| tinyvec | 1.13.3 | Zlib OR Apache-2.0 OR MIT | https://github.com/Lokathor/tinyvec |
| tls_codec | 0.4.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats |
| tls_codec_derive | 0.4.2 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats |
| tokio | 1.53.2 | MIT | https://github.com/tokio-rs/tokio |
| tokio-rustls | 0.26.6 | MIT OR Apache-2.0 | https://github.com/rustls/tokio-rustls |
| tokio-util | 0.7.20 | MIT | https://github.com/tokio-rs/tokio |
| toml | 0.8.2 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml | 1.1.8+spec-1.1.0 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_datetime | 0.6.3 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_datetime | 1.1.2+spec-1.1.0 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_edit | 0.19.15 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_edit | 0.20.2 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_edit | 0.25.17+spec-1.1.0 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_parser | 1.1.5+spec-1.1.0 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| toml_writer | 1.1.3+spec-1.1.0 | MIT OR Apache-2.0 | https://github.com/toml-rs/toml |
| tower | 0.5.3 | MIT | https://github.com/tower-rs/tower |
| tower-http | 0.6.11 | MIT | https://github.com/tower-rs/tower-http |
| tower-layer | 0.3.3 | MIT | https://github.com/tower-rs/tower |
| tower-service | 0.3.3 | MIT | https://github.com/tower-rs/tower |
| tracing | 0.1.44 | MIT | https://github.com/tokio-rs/tracing |
| tracing-attributes | 0.1.31 | MIT | https://github.com/tokio-rs/tracing |
| tracing-core | 0.1.36 | MIT | https://github.com/tokio-rs/tracing |
| tract-core | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-data | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-extra | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-hir | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-linalg | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-nnef | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-onnx | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-onnx-opl | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| tract-transformers | 0.23.10 | MIT OR Apache-2.0 | https://github.com/sonos/tract |
| transpose | 0.2.3 | MIT OR Apache-2.0 | https://github.com/ejmahler/transpose |
| tray-icon | 0.25.1 | MIT OR Apache-2.0 | https://github.com/tauri-apps/tray-icon |
| try-lock | 0.2.5 | MIT | https://github.com/seanmonstar/try-lock |
| ttf-parser | 0.25.1 | MIT OR Apache-2.0 | https://github.com/harfbuzz/ttf-parser |
| typed-path | 0.12.3 | MIT OR Apache-2.0 | https://github.com/chipsenkbeil/typed-path |
| typeid | 1.0.3 | MIT OR Apache-2.0 | https://github.com/dtolnay/typeid |
| typenum | 1.20.1 | MIT OR Apache-2.0 | https://github.com/paholg/typenum |
| uds_windows | 1.2.1 | MIT | https://github.com/haraldh/rust_uds_windows |
| unicode-bidi | 0.3.18 | MIT OR Apache-2.0 | https://github.com/servo/unicode-bidi |
| unicode-ident | 1.0.27 | (MIT OR Apache-2.0) AND Unicode-3.0 | https://github.com/dtolnay/unicode-ident |
| unicode-normalization | 0.1.25 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-normalization |
| unicode-properties | 0.1.4 | MIT/Apache-2.0 | https://github.com/unicode-rs/unicode-properties |
| unicode-segmentation | 1.13.3 | MIT OR Apache-2.0 | https://github.com/unicode-rs/unicode-segmentation |
| untrusted | 0.9.0 | ISC | https://github.com/briansmith/untrusted |
| url | 2.5.8 | MIT OR Apache-2.0 | https://github.com/servo/rust-url |
| urlpattern | 0.6.0 | MIT | https://github.com/denoland/rust-urlpattern |
| utf8_iter | 1.0.4 | Apache-2.0 OR MIT | https://github.com/hsivonen/utf8_iter |
| uuid | 1.28.0 | Apache-2.0 OR MIT | https://github.com/uuid-rs/uuid |
| vello_common | 0.3.0 | Apache-2.0 OR MIT | https://github.com/linebender/vello |
| vello_cpu | 0.3.0 | Apache-2.0 OR MIT | https://github.com/linebender/vello |
| version-compare | 0.2.1 | MIT | https://gitlab.com/timvisee/version-compare |
| version_check | 0.9.5 | MIT/Apache-2.0 | https://github.com/SergioBenitez/version_check |
| vswhom | 0.1.0 | MIT | https://github.com/nabijaczleweli/vswhom.rs |
| vswhom-sys | 0.1.3 | MIT | https://github.com/nabijaczleweli/vswhom-sys.rs |
| walkdir | 2.5.0 | Unlicense/MIT | https://github.com/BurntSushi/walkdir |
| want | 0.3.2 | MIT | https://github.com/seanmonstar/want |
| wasi | 0.11.1+wasi-snapshot-preview1 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/bytecodealliance/wasi |
| wasip2 | 1.0.4+wasi-0.2.12 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/bytecodealliance/wasi-rs |
| wasm-bindgen | 0.2.129 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen |
| wasm-bindgen | 0.2.130 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen |
| wasm-bindgen-futures | 0.4.79 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/futures |
| wasm-bindgen-macro | 0.2.129 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/macro |
| wasm-bindgen-macro | 0.2.130 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/macro |
| wasm-bindgen-macro-support | 0.2.129 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/main/crates/macro-support |
| wasm-bindgen-macro-support | 0.2.130 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/main/crates/macro-support |
| wasm-bindgen-shared | 0.2.129 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/shared |
| wasm-bindgen-shared | 0.2.130 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/shared |
| wasm-streams | 0.5.0 | MIT OR Apache-2.0 | https://github.com/MattiasBuelens/wasm-streams/ |
| web-sys | 0.3.106 | MIT OR Apache-2.0 | https://github.com/wasm-bindgen/wasm-bindgen/tree/master/crates/web-sys |
| web-time | 1.1.0 | MIT OR Apache-2.0 | https://github.com/daxpedda/web-time |
| web_atoms | 0.2.6 | MIT OR Apache-2.0 | https://github.com/servo/html5ever |
| webkit2gtk | 2.0.2 | MIT | https://github.com/tauri-apps/webkit2gtk-rs |
| webkit2gtk-sys | 2.0.2 | MIT | https://github.com/tauri-apps/webkit2gtk-rs |
| webpki-root-certs | 1.0.12 | CDLA-Permissive-2.0 | https://github.com/rustls/webpki-roots |
| webview2-com | 0.39.1 | MIT | https://github.com/wravery/webview2-rs |
| webview2-com-macros | 0.8.1 | MIT | https://github.com/wravery/webview2-rs |
| webview2-com-sys | 0.39.1 | MIT | https://github.com/wravery/webview2-rs |
| weezl | 0.1.12 | MIT OR Apache-2.0 | https://github.com/image-rs/weezl |
| weezl | 0.2.1 | MIT OR Apache-2.0 | https://github.com/image-rs/weezl |
| winapi | 0.3.9 | MIT/Apache-2.0 | https://github.com/retep998/winapi-rs |
| winapi-i686-pc-windows-gnu | 0.4.0 | MIT/Apache-2.0 | https://github.com/retep998/winapi-rs |
| winapi-util | 0.1.11 | Unlicense OR MIT | https://github.com/BurntSushi/winapi-util |
| winapi-x86_64-pc-windows-gnu | 0.4.0 | MIT/Apache-2.0 | https://github.com/retep998/winapi-rs |
| window-vibrancy | 0.8.1 | Apache-2.0 OR MIT | https://github.com/tauri-apps/tauri-plugin-vibrancy |
| windows | 0.62.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-collections | 0.3.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-core | 0.62.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-future | 0.3.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-implement | 0.60.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-interface | 0.59.3 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-link | 0.2.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-numerics | 0.3.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-registry | 0.6.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-result | 0.4.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-strings | 0.5.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-sys | 0.45.0 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-sys | 0.52.0 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-sys | 0.61.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-targets | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-targets | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-threading | 0.2.1 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows-version | 0.1.7 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_aarch64_gnullvm | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_aarch64_gnullvm | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_aarch64_msvc | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_aarch64_msvc | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_i686_gnu | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_i686_gnu | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_i686_gnullvm | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_i686_msvc | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_i686_msvc | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_gnu | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_gnu | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_gnullvm | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_gnullvm | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_msvc | 0.42.2 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| windows_x86_64_msvc | 0.52.6 | MIT OR Apache-2.0 | https://github.com/microsoft/windows-rs |
| winnow | 0.5.40 | MIT | https://github.com/winnow-rs/winnow |
| winnow | 1.0.4 | MIT | https://github.com/winnow-rs/winnow |
| winreg | 0.56.0 | MIT | https://github.com/gentoo90/winreg-rs |
| wit-bindgen | 0.57.1 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | https://github.com/bytecodealliance/wit-bindgen |
| write-fonts | 0.48.1 | MIT OR Apache-2.0 | https://github.com/googlefonts/fontations |
| writeable | 0.6.4 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| wry | 0.57.0 | Apache-2.0 OR MIT | https://github.com/tauri-apps/wry |
| x11 | 2.21.0 | MIT | https://github.com/AltF02/x11-rs.git |
| x11-dl | 2.21.0 | MIT | https://github.com/AltF02/x11-rs.git |
| x509-cert | 0.2.5 | Apache-2.0 OR MIT | https://github.com/RustCrypto/formats/tree/master/x509-cert |
| xattr | 1.7.0 | MIT OR Apache-2.0 | https://github.com/Stebalien/xattr |
| xmp-writer | 0.3.3 | MIT OR Apache-2.0 | https://github.com/typst/xmp-writer |
| yoke | 0.8.3 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| yoke-derive | 0.8.4 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zbus | 5.19.0 | MIT | https://github.com/z-galaxy/zbus/ |
| zbus_macros | 5.19.0 | MIT | https://github.com/z-galaxy/zbus/ |
| zbus_names | 4.3.5 | MIT | https://github.com/z-galaxy/zbus/ |
| zcheapstr | 1.2.0 | MIT | https://github.com/z-galaxy/zcheapstr/ |
| zerocopy | 0.8.62 | BSD-2-Clause OR Apache-2.0 OR MIT | https://github.com/google/zerocopy |
| zerocopy | 0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT | https://github.com/google/zerocopy |
| zerocopy-derive | 0.8.62 | BSD-2-Clause OR Apache-2.0 OR MIT | https://github.com/google/zerocopy |
| zerocopy-derive | 0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT | https://github.com/google/zerocopy |
| zerofrom | 0.1.8 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zerofrom-derive | 0.1.8 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zeroize | 1.9.1 | Apache-2.0 OR MIT | https://github.com/RustCrypto/utils |
| zeroize_derive | 1.5.0 | Apache-2.0 OR MIT | https://github.com/RustCrypto/utils |
| zerotrie | 0.2.5 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zerovec | 0.11.8 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zerovec-derive | 0.11.6 | Unicode-3.0 | https://github.com/unicode-org/icu4x |
| zip | 9.0.2 | MIT | https://github.com/zip-rs/zip2 |
| zlib-rs | 0.6.8 | Zlib | https://github.com/trifectatechfoundation/zlib-rs |
| zmij | 1.0.23 | MIT | https://github.com/dtolnay/zmij |
| zopfli | 0.8.4 | Apache-2.0 | https://github.com/zopfli-rs/zopfli |
| zune-core | 0.5.3 | MIT OR Apache-2.0 OR Zlib | https://github.com/etemesi254/zune-image |
| zune-jpeg | 0.5.15 | MIT OR Apache-2.0 OR Zlib | https://github.com/etemesi254/zune-image/tree/dev/crates/zune-jpeg |
| zvariant | 5.15.1 | MIT | https://github.com/z-galaxy/zbus/ |
| zvariant_derive | 5.15.1 | MIT | https://github.com/z-galaxy/zbus/ |
| zvariant_utils | 4.2.0 | MIT | https://github.com/z-galaxy/zbus/ |

## NOTICE of hypher (verbatim)

~~~~text
This NOTICE file compiles licenses and notices for code, data, and other
contents of this software that originate from third parties. In a source
repository, it covers contents not tracked by the dependency tree or other
machine-readable manifests; accompanying a distribution, it can also cover the
dependencies included in it. It is machine-readable and follows the format set
out in https://github.com/typst/notice (version 1). Tools that can parse this
file can use it to incorporate it into license notices, Software Bills of
Materials (SBOMs), etc of their distributions of this software, provided the
contents within are represented faithfully. Other distributions must reproduce
this file verbatim.

================================================================================
MIT --- This license applies to:

* Albanian hyphenation patterns

  Paths: `patterns/hyph-sq.tex`, `tries/sq.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sq.tex
  Notice: Copyright (C) 2020 Claudio Beccari, Sabina Koliqi; (C) 2025 Arthur
          Rosendahl

* Assamese hyphenation patterns

  Paths: `patterns/hyph-as.tex`, `tries/as.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-as.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Belarusian hyphenation patterns

  Paths: `patterns/hyph-be.tex`, `tries/be.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-be.tex
  Notice: Copyright (C) 2016 Maksim Salau

* Bengali hyphenation patterns

  Paths: `patterns/hyph-bn.tex`, `tries/bn.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-bn.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Czech hyphenation patterns

  Paths: `patterns/hyph-cs-sojka.tex`, `tries/cs.bin`
  Source: https://github.com/tensojka/cshyphen
  Notice: Copyright (c) 2019 Sojka

* Danish hyphenation patterns

  Paths: `patterns/hyph-da.tex`, `tries/da.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-da.tex
  Notice: Copyright (C) 1994 Frank Jensen

* Estonian hyphenation patterns

  Paths: `patterns/hyph-et.tex`, `tries/et.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-et.tex
  Notice: Copyright (C) 2004-2015 Enn Saar

* Finnish hyphenation patterns

  Paths: `patterns/hyph-fi-x-school.tex`, `tries/fi.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-fi-x-school.tex
  Notice: Copyright (C) 2020 Teemu Likonen, Arthur Rosendahl

* French hyphenation patterns

  Paths: `patterns/hyph-fr.tex`, `tries/fr.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-fr.tex
  Notice: Copyright (C) 1994-2002 Daniel Flipo, Bernard Gaulle, 2016 Arthur
          Reutenauer

* German hyphenation patterns

  Paths: `patterns/hyph-de-1996.tex`, `tries/de.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-de-1996.tex
  Notice: Copyright (c) 2013-2024 Stephan Hennig, Werner Lemberg, Günter Milde,
          Sander van Geloven, Georg Pfeiffer, Gisbert W. Selke, Tobias Wendorf,
          Keno Wehr

* Gujarati hyphenation patterns

  Paths: `patterns/hyph-gu.tex`, `tries/gu.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-gu.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Hindi hyphenation patterns

  Paths: `patterns/hyph-hi.tex`, `tries/hi.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-hi.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Italian hyphenation patterns

  Paths: `patterns/hyph-it.tex`, `tries/it.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-it.tex
  Notice: Copyright (C) 2008-2011 Claudio Beccari

* Kannada hyphenation patterns

  Paths: `patterns/hyph-kn.tex`, `tries/kn.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-kn.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Latin hyphenation patterns

  Paths: `patterns/hyph-la.tex`, `tries/la.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-la.tex
  Notice: Copyright (C) 1999-2016 Claudio Beccari

* Lithuanian hyphenation patterns

  Paths: `patterns/hyph-lt.tex`, `tries/lt.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-lt.tex
  Notice: Copyright (C) 1992 Sigitas Tolušis, Yannis Haralambous

* Malayalam hyphenation patterns

  Paths: `patterns/hyph-ml.tex`, `tries/ml.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-ml.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Marathi hyphenation patterns

  Paths: `patterns/hyph-mr.tex`, `tries/mr.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-mr.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Mongolian hyphenation patterns

  Paths: `patterns/hyph-mn.tex`, `tries/mn.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-mn.tex
  Notice: Copyright (C) 2007-2015 by Dorjgotov Batmunkh

* Oriya hyphenation patterns

  Paths: `patterns/hyph-or.tex`, `tries/or.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-or.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Panjabi hyphenation patterns

  Paths: `patterns/hyph-pa.tex`, `tries/pa.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-pa.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Polish hyphenation patterns

  Paths: `patterns/hyph-pl.tex`, `tries/pl.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-pl.tex
  Notice: Copyright (C) 1987-1995 Hanna Kołodziejska, Bogusław Jackowski, Marek
          Ryćko

* Slovak hyphenation patterns

  Paths: `patterns/hyph-sk.tex`, `tries/sk.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/645e87e9d5/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sk.tex
  Notice: Copyright (C) 1992 Jana Chlebíková

* Slovenian hyphenation patterns

  Paths: `patterns/hyph-sl.tex`, `tries/sl.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sl.tex
  Notice: Copyright (C) 1990 Matjaž Vrečko

* Spanish hyphenation patterns

  Paths: `patterns/hyph-es.tex`, `tries/es.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-es.tex
  Notice: Copyright (C) 1993, 1997 Javier Bezos, 2001-2019 Javier Bezos,
          CervanTeX

* Tamil hyphenation patterns

  Paths: `patterns/hyph-ta.tex`, `tries/ta.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-ta.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Telugu hyphenation patterns

  Paths: `patterns/hyph-te.tex`, `tries/te.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-te.tex
  Notice: Copyright (C) 2016 Santhosh Thottingal

* Turkmen hyphenation patterns

  Paths: `patterns/hyph-tk.tex`, `tries/tk.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-tk.tex
  Notice: Copyright (C) 2010-2015 Nazar Annagurban

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
================================================================================


================================================================================
BSD-3-Clause --- This license applies to:

* Portuguese hyphenation patterns

  Paths: `patterns/hyph-pt.tex`, `tries/pt.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-pt.tex
  Notice: Copyright (C) 1987, 1994, 1996, 2015 Pedro J. de Rezende, 1996, 2015
          J. Joao Dias Almeida, 2024 Leonardo Araujo and Aline Benevides

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.
* Neither the name of the University of Campinas, of the University of Minho
  nor the names of its contributors may be used to endorse or promote products
  derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL PEDRO J. DE REZENDE OR J.JOAO DIAS ALMEIDA BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF
THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
================================================================================


================================================================================
LPPL-1.3c --- This license applies to:

* Afrikaans hyphenation patterns

  Paths: `patterns/hyph-af.tex`, `tries/af.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-af.tex
  Notice: Copyright (C) 2013 Tilla Fick and Chris Swanepoel

* Catalan hyphenation patterns

  Paths: `patterns/hyph-ca.tex`, `tries/ca.bin`
  Source: https://ftp.uni-bayreuth.de/packages/TeX/languages/hyphenation/cahyph.tex
  Notice: Copyright (C) 1991-2003 Gonçal Badenes

* Croatian hyphenation patterns

  Paths: `patterns/hyph-hr.tex`, `tries/hr.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-hr.tex
  Notice: Copyright (C) 1994, 1996, 2011, 2015 Igor Marinović

* Dutch hyphenation patterns

  Paths: `patterns/hyph-nl.tex`, `tries/nl.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-nl.tex
  Notice: Copyright (C) 1996 Piet Tutelaers

* Georgian hyphenation patterns

  Paths: `patterns/hyph-ka.tex`, `tries/ka.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-ka.tex
  Notice: Copyright (C) 2013 Levan Shoshiashvili

* Greek hyphenation patterns

  Paths: `patterns/hyph-el-monoton.tex`, `tries/el.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-el-monoton.tex
  Notice: Copyright (C) 2008-2011 Dimitrios Filippou

* Icelandic hyphenation patterns

  Paths: `patterns/hyph-is.tex`, `tries/is.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-is.tex
  Notice: Copyright (C) 1988, 2004 Jörgen Pind

* Russian hyphenation patterns

  Paths: `patterns/hyph-ru.tex`, `tries/ru.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-ru.tex
  Notice: Copyright (C) 1999-2003 Alexander I. Lebedev

* Serbian hyphenation patterns

  Paths: `patterns/hyph-sh-cyrl.tex`, `tries/sr.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sh-cyrl.tex
  Notice: Copyright (C) 1990, 2008 Dejan Muhamedagić

* Swedish hyphenation patterns

  Paths: `patterns/hyph-sv.tex`, `tries/sv.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sv.tex
  Notice: Copyright (C) 1994 Jan Michael Rynning

* Turkish hyphenation patterns

  Paths: `patterns/hyph-tr.tex`, `tries/tr.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-tr.tex
  Notice: Copyright (C) 1987 Pierre A. MacKay, 2008, 2011 TUG

* Ukrainian hyphenation patterns

  Paths: `patterns/hyph-uk.tex`, `tries/uk.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-uk.tex
  Notice: Copyright (C) 1998-2001 Maksym Polyakov

The LaTeX Project Public License
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

LPPL Version 1.3c  2006-05-20

Copyright 1999 2002-2006 LaTeX3 Project
    Everyone is allowed to distribute verbatim copies of this
    license document, but modification of it is not allowed.


PREAMBLE
========

The LaTeX Project Public License (LPPL) is the primary license under
which the the LaTeX kernel and the base LaTeX packages are distributed.

You may use this license for any work of which you hold the copyright
and which you wish to distribute.  This license may be particularly
suitable if your work is TeX-related (such as a LaTeX package), but 
it is written in such a way that you can use it even if your work is 
unrelated to TeX.

The section `WHETHER AND HOW TO DISTRIBUTE WORKS UNDER THIS LICENSE',
below, gives instructions, examples, and recommendations for authors
who are considering distributing their works under this license.

This license gives conditions under which a work may be distributed
and modified, as well as conditions under which modified versions of
that work may be distributed.

We, the LaTeX3 Project, believe that the conditions below give you
the freedom to make and distribute modified versions of your work
that conform with whatever technical specifications you wish while
maintaining the availability, integrity, and reliability of
that work.  If you do not see how to achieve your goal while
meeting these conditions, then read the document `cfgguide.tex'
and `modguide.tex' in the base LaTeX distribution for suggestions.


DEFINITIONS
===========

In this license document the following terms are used:

   `Work'
    Any work being distributed under this License.
    
   `Derived Work'
    Any work that under any applicable law is derived from the Work.

   `Modification' 
    Any procedure that produces a Derived Work under any applicable
    law -- for example, the production of a file containing an
    original file associated with the Work or a significant portion of
    such a file, either verbatim or with modifications and/or
    translated into another language.

   `Modify'
    To apply any procedure that produces a Derived Work under any
    applicable law.
    
   `Distribution'
    Making copies of the Work available from one person to another, in
    whole or in part.  Distribution includes (but is not limited to)
    making any electronic components of the Work accessible by
    file transfer protocols such as FTP or HTTP or by shared file
    systems such as Sun's Network File System (NFS).

   `Compiled Work'
    A version of the Work that has been processed into a form where it
    is directly usable on a computer system.  This processing may
    include using installation facilities provided by the Work,
    transformations of the Work, copying of components of the Work, or
    other activities.  Note that modification of any installation
    facilities provided by the Work constitutes modification of the Work.

   `Current Maintainer'
    A person or persons nominated as such within the Work.  If there is
    no such explicit nomination then it is the `Copyright Holder' under
    any applicable law.

   `Base Interpreter' 
    A program or process that is normally needed for running or
    interpreting a part or the whole of the Work.    

    A Base Interpreter may depend on external components but these
    are not considered part of the Base Interpreter provided that each
    external component clearly identifies itself whenever it is used
    interactively.  Unless explicitly specified when applying the
    license to the Work, the only applicable Base Interpreter is a
    `LaTeX-Format' or in the case of files belonging to the 
    `LaTeX-format' a program implementing the `TeX language'.



CONDITIONS ON DISTRIBUTION AND MODIFICATION
===========================================

1.  Activities other than distribution and/or modification of the Work
are not covered by this license; they are outside its scope.  In
particular, the act of running the Work is not restricted and no
requirements are made concerning any offers of support for the Work.

2.  You may distribute a complete, unmodified copy of the Work as you
received it.  Distribution of only part of the Work is considered
modification of the Work, and no right to distribute such a Derived
Work may be assumed under the terms of this clause.

3.  You may distribute a Compiled Work that has been generated from a
complete, unmodified copy of the Work as distributed under Clause 2
above, as long as that Compiled Work is distributed in such a way that
the recipients may install the Compiled Work on their system exactly
as it would have been installed if they generated a Compiled Work
directly from the Work.

4.  If you are the Current Maintainer of the Work, you may, without
restriction, modify the Work, thus creating a Derived Work.  You may
also distribute the Derived Work without restriction, including
Compiled Works generated from the Derived Work.  Derived Works
distributed in this manner by the Current Maintainer are considered to
be updated versions of the Work.

5.  If you are not the Current Maintainer of the Work, you may modify
your copy of the Work, thus creating a Derived Work based on the Work,
and compile this Derived Work, thus creating a Compiled Work based on
the Derived Work.

6.  If you are not the Current Maintainer of the Work, you may
distribute a Derived Work provided the following conditions are met
for every component of the Work unless that component clearly states
in the copyright notice that it is exempt from that condition.  Only
the Current Maintainer is allowed to add such statements of exemption 
to a component of the Work. 

  a. If a component of this Derived Work can be a direct replacement
     for a component of the Work when that component is used with the
     Base Interpreter, then, wherever this component of the Work
     identifies itself to the user when used interactively with that
     Base Interpreter, the replacement component of this Derived Work
     clearly and unambiguously identifies itself as a modified version
     of this component to the user when used interactively with that
     Base Interpreter.
     
  b. Every component of the Derived Work contains prominent notices
     detailing the nature of the changes to that component, or a
     prominent reference to another file that is distributed as part
     of the Derived Work and that contains a complete and accurate log
     of the changes.
  
  c. No information in the Derived Work implies that any persons,
     including (but not limited to) the authors of the original version
     of the Work, provide any support, including (but not limited to)
     the reporting and handling of errors, to recipients of the
     Derived Work unless those persons have stated explicitly that
     they do provide such support for the Derived Work.

  d. You distribute at least one of the following with the Derived Work:

       1. A complete, unmodified copy of the Work; 
          if your distribution of a modified component is made by
          offering access to copy the modified component from a
          designated place, then offering equivalent access to copy
          the Work from the same or some similar place meets this
          condition, even though third parties are not compelled to
          copy the Work along with the modified component;

       2. Information that is sufficient to obtain a complete,
          unmodified copy of the Work.

7.  If you are not the Current Maintainer of the Work, you may
distribute a Compiled Work generated from a Derived Work, as long as
the Derived Work is distributed to all recipients of the Compiled
Work, and as long as the conditions of Clause 6, above, are met with
regard to the Derived Work.

8.  The conditions above are not intended to prohibit, and hence do not
apply to, the modification, by any method, of any component so that it
becomes identical to an updated version of that component of the Work as
it is distributed by the Current Maintainer under Clause 4, above.

9.  Distribution of the Work or any Derived Work in an alternative
format, where the Work or that Derived Work (in whole or in part) is
then produced by applying some process to that format, does not relax or
nullify any sections of this license as they pertain to the results of
applying that process.
     
10. a. A Derived Work may be distributed under a different license
       provided that license itself honors the conditions listed in
       Clause 6 above, in regard to the Work, though it does not have
       to honor the rest of the conditions in this license.
      
    b. If a Derived Work is distributed under a different license, that
       Derived Work must provide sufficient documentation as part of
       itself to allow each recipient of that Derived Work to honor the 
       restrictions in Clause 6 above, concerning changes from the Work.

11. This license places no restrictions on works that are unrelated to
the Work, nor does this license place any restrictions on aggregating
such works with the Work by any means.

12.  Nothing in this license is intended to, or may be used to, prevent
complete compliance by all parties with all applicable laws.


NO WARRANTY
===========

There is no warranty for the Work.  Except when otherwise stated in
writing, the Copyright Holder provides the Work `as is', without
warranty of any kind, either expressed or implied, including, but not
limited to, the implied warranties of merchantability and fitness for a
particular purpose.  The entire risk as to the quality and performance
of the Work is with you.  Should the Work prove defective, you assume
the cost of all necessary servicing, repair, or correction.

In no event unless required by applicable law or agreed to in writing
will The Copyright Holder, or any author named in the components of the
Work, or any other party who may distribute and/or modify the Work as
permitted above, be liable to you for damages, including any general,
special, incidental or consequential damages arising out of any use of
the Work or out of inability to use the Work (including, but not limited
to, loss of data, data being rendered inaccurate, or losses sustained by
anyone as a result of any failure of the Work to operate with any other
programs), even if the Copyright Holder or said author or said other
party has been advised of the possibility of such damages.


MAINTENANCE OF THE WORK
=======================

The Work has the status `author-maintained' if the Copyright Holder
explicitly and prominently states near the primary copyright notice in
the Work that the Work can only be maintained by the Copyright Holder
or simply that it is `author-maintained'.

The Work has the status `maintained' if there is a Current Maintainer
who has indicated in the Work that they are willing to receive error
reports for the Work (for example, by supplying a valid e-mail
address). It is not required for the Current Maintainer to acknowledge
or act upon these error reports.

The Work changes from status `maintained' to `unmaintained' if there
is no Current Maintainer, or the person stated to be Current
Maintainer of the work cannot be reached through the indicated means
of communication for a period of six months, and there are no other
significant signs of active maintenance.

You can become the Current Maintainer of the Work by agreement with
any existing Current Maintainer to take over this role.

If the Work is unmaintained, you can become the Current Maintainer of
the Work through the following steps:

 1.  Make a reasonable attempt to trace the Current Maintainer (and
     the Copyright Holder, if the two differ) through the means of
     an Internet or similar search.

 2.  If this search is successful, then enquire whether the Work
     is still maintained.

  a. If it is being maintained, then ask the Current Maintainer
     to update their communication data within one month.
     
  b. If the search is unsuccessful or no action to resume active
     maintenance is taken by the Current Maintainer, then announce
     within the pertinent community your intention to take over
     maintenance.  (If the Work is a LaTeX work, this could be
     done, for example, by posting to comp.text.tex.)

 3a. If the Current Maintainer is reachable and agrees to pass
     maintenance of the Work to you, then this takes effect
     immediately upon announcement.
     
  b. If the Current Maintainer is not reachable and the Copyright
     Holder agrees that maintenance of the Work be passed to you,
     then this takes effect immediately upon announcement.  
    
 4.  If you make an `intention announcement' as described in 2b. above
     and after three months your intention is challenged neither by
     the Current Maintainer nor by the Copyright Holder nor by other
     people, then you may arrange for the Work to be changed so as
     to name you as the (new) Current Maintainer.
     
 5.  If the previously unreachable Current Maintainer becomes
     reachable once more within three months of a change completed
     under the terms of 3b) or 4), then that Current Maintainer must
     become or remain the Current Maintainer upon request provided
     they then update their communication data within one month.

A change in the Current Maintainer does not, of itself, alter the fact
that the Work is distributed under the LPPL license.

If you become the Current Maintainer of the Work, you should
immediately provide, within the Work, a prominent and unambiguous
statement of your status as Current Maintainer.  You should also
announce your new status to the same pertinent community as
in 2b) above.


WHETHER AND HOW TO DISTRIBUTE WORKS UNDER THIS LICENSE
======================================================

This section contains important instructions, examples, and
recommendations for authors who are considering distributing their
works under this license.  These authors are addressed as `you' in
this section.

Choosing This License or Another License
----------------------------------------

If for any part of your work you want or need to use *distribution*
conditions that differ significantly from those in this license, then
do not refer to this license anywhere in your work but, instead,
distribute your work under a different license.  You may use the text
of this license as a model for your own license, but your license
should not refer to the LPPL or otherwise give the impression that
your work is distributed under the LPPL.

The document `modguide.tex' in the base LaTeX distribution explains
the motivation behind the conditions of this license.  It explains,
for example, why distributing LaTeX under the GNU General Public
License (GPL) was considered inappropriate.  Even if your work is
unrelated to LaTeX, the discussion in `modguide.tex' may still be
relevant, and authors intending to distribute their works under any
license are encouraged to read it.

A Recommendation on Modification Without Distribution
-----------------------------------------------------

It is wise never to modify a component of the Work, even for your own
personal use, without also meeting the above conditions for
distributing the modified component.  While you might intend that such
modifications will never be distributed, often this will happen by
accident -- you may forget that you have modified that component; or
it may not occur to you when allowing others to access the modified
version that you are thus distributing it and violating the conditions
of this license in ways that could have legal implications and, worse,
cause problems for the community.  It is therefore usually in your
best interest to keep your copy of the Work identical with the public
one.  Many works provide ways to control the behavior of that work
without altering any of its licensed components.

How to Use This License
-----------------------

To use this license, place in each of the components of your work both
an explicit copyright notice including your name and the year the work
was authored and/or last substantially modified.  Include also a
statement that the distribution and/or modification of that
component is constrained by the conditions in this license.

Here is an example of such a notice and statement:

  %% pig.dtx
  %% Copyright 2005 M. Y. Name
  %
  % This work may be distributed and/or modified under the
  % conditions of the LaTeX Project Public License, either version 1.3
  % of this license or (at your option) any later version.
  % The latest version of this license is in
  %   http://www.latex-project.org/lppl.txt
  % and version 1.3 or later is part of all distributions of LaTeX
  % version 2005/12/01 or later.
  %
  % This work has the LPPL maintenance status `maintained'.
  % 
  % The Current Maintainer of this work is M. Y. Name.
  %
  % This work consists of the files pig.dtx and pig.ins
  % and the derived file pig.sty.

Given such a notice and statement in a file, the conditions
given in this license document would apply, with the `Work' referring
to the three files `pig.dtx', `pig.ins', and `pig.sty' (the last being
generated from `pig.dtx' using `pig.ins'), the `Base Interpreter'
referring to any `LaTeX-Format', and both `Copyright Holder' and
`Current Maintainer' referring to the person `M. Y. Name'.

If you do not want the Maintenance section of LPPL to apply to your
Work, change `maintained' above into `author-maintained'.  
However, we recommend that you use `maintained', as the Maintenance
section was added in order to ensure that your Work remains useful to
the community even when you can no longer maintain and support it
yourself.

Derived Works That Are Not Replacements
---------------------------------------

Several clauses of the LPPL specify means to provide reliability and
stability for the user community. They therefore concern themselves
with the case that a Derived Work is intended to be used as a
(compatible or incompatible) replacement of the original Work. If
this is not the case (e.g., if a few lines of code are reused for a
completely different task), then clauses 6b and 6d shall not apply.


Important Recommendations
-------------------------

 Defining What Constitutes the Work

   The LPPL requires that distributions of the Work contain all the
   files of the Work.  It is therefore important that you provide a
   way for the licensee to determine which files constitute the Work.
   This could, for example, be achieved by explicitly listing all the
   files of the Work near the copyright notice of each file or by
   using a line such as:

    % This work consists of all files listed in manifest.txt.
   
   in that place.  In the absence of an unequivocal list it might be
   impossible for the licensee to determine what is considered by you
   to comprise the Work and, in such a case, the licensee would be
   entitled to make reasonable conjectures as to which files comprise
   the Work.
================================================================================


================================================================================
LicenseRef-LPPL-1.3 (LaTeX Project Public License 1.3) --- This license applies
to:

* Kurmanji hyphenation patterns

  Paths: `patterns/hyph-kmr.tex`, `tries/ku.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-kmr.tex
  Notice: Copyright (C) 2009 Jörg Knappen, Medeni Shemdê

The LaTeX Project Public License
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

LPPL Version 1.3  2003-12-01

Copyright 1999 2002-03 LaTeX3 Project
    Everyone is allowed to distribute verbatim copies of this
    license document, but modification of it is not allowed.


PREAMBLE
========

The LaTeX Project Public License (LPPL) is the primary license under which the
LaTeX kernel and the base LaTeX packages are distributed.

You may use this license for any work of which you hold the copyright and which
you wish to distribute.  This license may be particularly suitable if your work
is TeX-related (such as a LaTeX package), but you may use it with small
modifications even if your work is unrelated to TeX.

The section `WHETHER AND HOW TO DISTRIBUTE WORKS UNDER THIS LICENSE', below,
gives instructions, examples, and recommendations for authors who are
considering distributing their works under this license.

This license gives conditions under which a work may be distributed and
modified, as well as conditions under which modified versions of that work may
be distributed.

We, the LaTeX3 Project, believe that the conditions below give you the freedom
to make and distribute modified versions of your work that conform with whatever
technical specifications you wish while maintaining the availability, integrity,
and reliability of that work.  If you do not see how to achieve your goal while
meeting these conditions, then read the document `cfgguide.tex' and
`modguide.tex' in the base LaTeX distribution for suggestions.


DEFINITIONS
===========

In this license document the following terms are used:

   `Work' Any work being distributed under this License.

   `Derived Work' Any work that under any applicable law is derived from the
    Work.

   `Modification' Any procedure that produces a Derived Work under any
    applicable law -- for example, the production of a file containing an
    original file associated with the Work or a significant portion of such a
    file, either verbatim or with modifications and/or translated into another
    language.

   `Modify' To apply any procedure that produces a Derived Work under any
    applicable law.

   `Distribution' Making copies of the Work available from one person to
    another, in whole or in part.  Distribution includes (but is not limited to)
    making any electronic components of the Work accessible by file transfer
    protocols such as FTP or HTTP or by shared file systems such as Sun's
    Network Path System (NFS).

   `Compiled Work' A version of the Work that has been processed into a form
    where it is directly usable on a computer system.  This processing may
    include using installation facilities provided by the Work, transformations
    of the Work, copying of components of the Work, or other activities.  Note
    that modification of any installation facilities provided by the Work
    constitutes modification of the Work.

   `Current Maintainer' A person or persons nominated as such within the Work.
    If there is no such explicit nomination then it is the `Copyright Holder'
    under any applicable law.

   `Base Interpreter' A program or process that is normally needed for running
    or interpreting a part or the whole of the Work. A Base Interpreter may
    depend on external components but these are not considered part of the Base
    Interpreter provided that each external component clearly identifies itself
    whenever it is used interactively.  Unless explicitly specified when
    applying the license to the Work, the only applicable Base Interpreter is a
    "LaTeX-Format".



CONDITIONS ON DISTRIBUTION AND MODIFICATION
===========================================

1.  Activities other than distribution and/or modification of the Work are not
covered by this license; they are outside its scope.  In particular, the act of
running the Work is not restricted and no requirements are made concerning any
offers of support for the Work.

2.  You may distribute a complete, unmodified copy of the Work as you received
it.  Distribution of only part of the Work is considered modification of the
Work, and no right to distribute such a Derived Work may be assumed under the
terms of this clause.

3.  You may distribute a Compiled Work that has been generated from a complete,
unmodified copy of the Work as distributed under Clause 2 above, as long as that
Compiled Work is distributed in such a way that the recipients may install the
Compiled Work on their system exactly as it would have been installed if they
generated a Compiled Work directly from the Work.

4.  If you are the Current Maintainer of the Work, you may, without restriction,
modify the Work, thus creating a Derived Work.  You may also distribute the
Derived Work without restriction, including Compiled Works generated from the
Derived Work.  Derived Works distributed in this manner by the Current
Maintainer are considered to be updated versions of the Work.

5.  If you are not the Current Maintainer of the Work, you may modify your copy
of the Work, thus creating a Derived Work based on the Work, and compile this
Derived Work, thus creating a Compiled Work based on the Derived Work.

6.  If you are not the Current Maintainer of the Work, you may distribute a
Derived Work provided the following conditions are met for every component of
the Work unless that component clearly states in the copyright notice that it is
exempt from that condition.  Only the Current Maintainer is allowed to add such
statements of exemption to a component of the Work.

  a. If a component of this Derived Work can be a direct replacement for a
     component of the Work when that component is used with the Base
     Interpreter, then, wherever this component of the Work identifies itself to
     the user when used interactively with that Base Interpreter, the
     replacement component of this Derived Work clearly and unambiguously
     identifies itself as a modified version of this component to the user when
     used interactively with that Base Interpreter.

  b. Every component of the Derived Work contains prominent notices detailing
     the nature of the changes to that component, or a prominent reference to
     another file that is distributed as part of the Derived Work and that
     contains a complete and accurate log of the changes.

  c. No information in the Derived Work implies that any persons, including (but
     not limited to) the authors of the original version of the Work, provide
     any support, including (but not limited to) the reporting and handling of
     errors, to recipients of the Derived Work unless those persons have stated
     explicitly that they do provide such support for the Derived Work.

  d. You distribute at least one of the following with the Derived Work:

       1. A complete, unmodified copy of the Work;
          if your distribution of a modified component is made by
          offering access to copy the modified component from a
          designated place, then offering equivalent access to copy
          the Work from the same or some similar place meets this
          condition, even though third parties are not compelled to
          copy the Work along with the modified component;

       2. Information that is sufficient to obtain a complete, unmodified
          copy of the Work.

7.  If you are not the Current Maintainer of the Work, you may distribute a
Compiled Work generated from a Derived Work, as long as the Derived Work is
distributed to all recipients of the Compiled Work, and as long as the
conditions of Clause 6, above, are met with regard to the Derived Work.

8.  The conditions above are not intended to prohibit, and hence do not apply
to, the modification, by any method, of any component so that it becomes
identical to an  updated version of that component of the Work as it is
distributed by the Current Maintainer under Clause 4, above.

9.  Distribution of the Work or any Derived Work in an alternative format, where
the Work or that Derived Work (in whole or in part) is then produced by applying
some process to that format, does not relax or nullify any sections of this
license as they pertain to the results of applying that process.

10. a. A Derived Work may be distributed under a different license provided that
       license itself honors the conditions listed in Clause 6 above, in regard
       to the Work, though it does not have to honor the rest of the conditions
       in this license.

    b. If a Derived Work is distributed under this license, that Derived Work
       must provide sufficient documentation as part of itself to allow each
       recipient of that Derived Work to honor the restrictions in Clause 6
       above, concerning changes from the Work.

11. This license places no restrictions on works that are unrelated to the Work,
nor does this license place any restrictions on aggregating such works with the
Work by any means.

12.  Nothing in this license is intended to, or may be used to, prevent complete
compliance by all parties with all applicable laws.


NO WARRANTY
===========

There is no warranty for the Work.  Except when otherwise stated in writing, the
Copyright Holder provides the Work `as is', without warranty of any kind, either
expressed or implied, including, but not limited to, the implied warranties of
merchantability and fitness for a particular purpose.  The entire risk as to the
quality and performance of the Work is with you.  Should the Work prove
defective, you assume the cost of all necessary servicing, repair, or
correction.

In no event unless agreed to in writing will the Copyright Holder, or any author
named in the components of the Work, or any other party who may distribute
and/or modify the Work as permitted above, be liable to you for damages,
including any general, special, incidental or consequential damages arising out
of any use of the Work or out of inability to use the Work (including, but not
limited to, loss of data, data being rendered inaccurate, or losses sustained by
anyone as a result of any failure of the Work to operate with any other
programs), even if the Copyright Holder or said author or said other party has
been advised of the possibility of such damages.


MAINTENANCE OF THE WORK
=======================

The Work has the status `author-maintained' if the Copyright Holder explicitly
and prominently states near the primary copyright notice in the Work that the
Work can only be maintained by the Copyright Holder or simply that is
`author-maintained'.

The Work has the status `maintained' if there is a Current Maintainer who has
indicated in the Work that they are willing to receive error reports for the
Work (for example, by supplying a valid e-mail address). It is not required for
the Current Maintainer to acknowledge or act upon these error reports.

The Work changes from status `maintained' to `unmaintained' if there is no
Current Maintainer, or the person stated to be Current Maintainer of the work
cannot be reached through the indicated means of communication for a period of
six months, and there are no other significant signs of active maintenance.

You can become the Current Maintainer of the Work by agreement with any existing
Current Maintainer to take over this role.

If the Work is unmaintained, you can become the Current Maintainer of the Work
through the following steps:

 1.  Make a reasonable attempt to trace the Current Maintainer (and the
     Copyright Holder, if the two differ) through the means of an Internet or
     similar search.

 2.  If this search is successful, then enquire whether the Work is still
     maintained.

  a. If it is being maintained, then ask the Current Maintainer to update their
     communication data within one month.

  b. If the search is unsuccessful or no action to resume active maintenance is
     taken by the Current Maintainer, then announce within the pertinent
     community your intention to take over maintenance.  (If the Work is a LaTeX
     work, this could be done, for example, by posting to comp.text.tex.)

 3a. If the Current Maintainer is reachable and agrees to pass maintenance of
     the Work to you, then this takes effect immediately upon announcement.

  b. If the Current Maintainer is not reachable and the Copyright Holder agrees
     that maintenance of the Work be passed to you, then this takes effect
     immediately upon announcement.

 4.  If you make an `intention announcement' as described in 2b. above and after
     three months your intention is challenged neither by the Current Maintainer
     nor by the Copyright Holder nor by other people, then you may arrange for
     the Work to be changed so as to name you as the (new) Current Maintainer.

 5.  If the previously unreachable Current Maintainer becomes reachable once
     more within three months of a change completed under the terms of 3b) or
     4), then that Current Maintainer must become or remain the Current
     Maintainer upon request provided they then update their communication data
     within one month.

A change in the Current Maintainer does not, of itself, alter the fact that the
Work is distributed under the LPPL license.

If you become the Current Maintainer of the Work, you should immediately
provide, within the Work, a prominent and unambiguous statement of your status
as Current Maintainer.  You should also announce your new status to the same
pertinent community as in 2b) above.


WHETHER AND HOW TO DISTRIBUTE WORKS UNDER THIS LICENSE
======================================================

This section contains important instructions, examples, and recommendations for
authors who are considering distributing their works under this license.  These
authors are addressed as `you' in this section.

Choosing This License or Another License
----------------------------------------

If for any part of your work you want or need to use *distribution* conditions
that differ significantly from those in this license, then do not refer to this
license anywhere in your work but, instead, distribute your work under a
different license.  You may use the text of this license as a model for your own
license, but your license should not refer to the LPPL or otherwise give the
impression that your work is distributed under the LPPL.

The document `modguide.tex' in the base LaTeX distribution explains the
motivation behind the conditions of this license.  It explains, for example, why
distributing LaTeX under the GNU General Public License (GPL) was considered
inappropriate.  Even if your work is unrelated to LaTeX, the discussion in
`modguide.tex' may still be relevant, and authors intending to distribute their
works under any license are encouraged to read it.

A Recommendation on Modification Without Distribution
-----------------------------------------------------

It is wise never to modify a component of the Work, even for your own personal
use, without also meeting the above conditions for distributing the modified
component.  While you might intend that such modifications will never be
distributed, often this will happen by accident -- you may forget that you have
modified that component; or it may not occur to you when allowing others to
access the modified version that you are thus distributing it and violating the
conditions of this license in ways that could have legal implications and,
worse, cause problems for the community.  It is therefore usually in your best
interest to keep your copy of the Work identical with the public one.  Many
works provide ways to control the behavior of that work without altering any of
its licensed components.

How to Use This License
-----------------------

To use this license, place in each of the components of your work both an
explicit copyright notice including your name and the year the work was authored
and/or last substantially modified.  Include also a statement that the
distribution and/or modification of that component is constrained by the
conditions in this license.

Here is an example of such a notice and statement:

  %% pig.dtx
  %% Copyright 2003 M. Y. Name
  %
  % This work may be distributed and/or modified under the
  % conditions of the LaTeX Project Public License, either version 1.3
  % of this license or (at your option) any later version.
  % The latest version of this license is in
  %   http://www.latex-project.org/lppl.txt
  % and version 1.3 or later is part of all distributions of LaTeX
  % version 2003/12/01 or later.
  %
  % This work has the LPPL maintenance status "maintained".
  %
  % This Current Maintainer of this work is M. Y. Name.
  %
  % This work consists of the files pig.dtx and pig.ins
  % and the derived file pig.sty.

Given such a notice and statement in a file, the conditions given in this
license document would apply, with the `Work' referring to the three files
`pig.dtx', `pig.ins', and `pig.sty' (the last being generated from `pig.dtx'
using `pig.ins'), the `Base Interpreter' referring to any "LaTeX-Format", and
both `Copyright Holder' and `Current Maintainer' referring to the person `M. Y.
Name'.

To prevent the Maintenance section of LPPL from allowing someone else to become
the Current Maintainer without your agreement, you could change "maintained"
above into "author-maintained".


Important Recommendations
-------------------------

 Defining What Constitutes the Work

   The LPPL requires that distributions of the Work contain all the files of the
   Work.  It is therefore important that you provide a way for the licensee to
   determine which files constitute the Work. This could, for example, be
   achieved by explicitly listing all the files of the Work near the copyright
   notice of each file or by using a line such as:

    % This work consists of all files listed in manifest.txt.

   in that place.  In the absence of an unequivocal list it might be impossible
   for the licensee to determine what is considered by you to comprise the Work
   and, in such a case, the licensee would be entitled to make reasonable
   conjectures as to which files comprise the Work.
================================================================================


================================================================================
MPL-1.1 --- This license applies to:

* Hungarian hyphenation patterns

  Paths: `patterns/hyph-hu.tex`, `tries/hu.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-hu.tex
  Notice: Copyright (C) 2003 Bence Nagy

                          MOZILLA PUBLIC LICENSE
                                Version 1.1

                              ---------------

1. Definitions.

     1.0.1. "Commercial Use" means distribution or otherwise making the
     Covered Code available to a third party.

     1.1. "Contributor" means each entity that creates or contributes to
     the creation of Modifications.

     1.2. "Contributor Version" means the combination of the Original
     Code, prior Modifications used by a Contributor, and the Modifications
     made by that particular Contributor.

     1.3. "Covered Code" means the Original Code or Modifications or the
     combination of the Original Code and Modifications, in each case
     including portions thereof.

     1.4. "Electronic Distribution Mechanism" means a mechanism generally
     accepted in the software development community for the electronic
     transfer of data.

     1.5. "Executable" means Covered Code in any form other than Source
     Code.

     1.6. "Initial Developer" means the individual or entity identified
     as the Initial Developer in the Source Code notice required by Exhibit
     A.

     1.7. "Larger Work" means a work which combines Covered Code or
     portions thereof with code not governed by the terms of this License.

     1.8. "License" means this document.

     1.8.1. "Licensable" means having the right to grant, to the maximum
     extent possible, whether at the time of the initial grant or
     subsequently acquired, any and all of the rights conveyed herein.

     1.9. "Modifications" means any addition to or deletion from the
     substance or structure of either the Original Code or any previous
     Modifications. When Covered Code is released as a series of files, a
     Modification is:
          A. Any addition to or deletion from the contents of a file
          containing Original Code or previous Modifications.

          B. Any new file that contains any part of the Original Code or
          previous Modifications.

     1.10. "Original Code" means Source Code of computer software code
     which is described in the Source Code notice required by Exhibit A as
     Original Code, and which, at the time of its release under this
     License is not already Covered Code governed by this License.

     1.10.1. "Patent Claims" means any patent claim(s), now owned or
     hereafter acquired, including without limitation,  method, process,
     and apparatus claims, in any patent Licensable by grantor.

     1.11. "Source Code" means the preferred form of the Covered Code for
     making modifications to it, including all modules it contains, plus
     any associated interface definition files, scripts used to control
     compilation and installation of an Executable, or source code
     differential comparisons against either the Original Code or another
     well known, available Covered Code of the Contributor's choice. The
     Source Code can be in a compressed or archival form, provided the
     appropriate decompression or de-archiving software is widely available
     for no charge.

     1.12. "You" (or "Your")  means an individual or a legal entity
     exercising rights under, and complying with all of the terms of, this
     License or a future version of this License issued under Section 6.1.
     For legal entities, "You" includes any entity which controls, is
     controlled by, or is under common control with You. For purposes of
     this definition, "control" means (a) the power, direct or indirect,
     to cause the direction or management of such entity, whether by
     contract or otherwise, or (b) ownership of more than fifty percent
     (50%) of the outstanding shares or beneficial ownership of such
     entity.

2. Source Code License.

     2.1. The Initial Developer Grant.
     The Initial Developer hereby grants You a world-wide, royalty-free,
     non-exclusive license, subject to third party intellectual property
     claims:
          (a)  under intellectual property rights (other than patent or
          trademark) Licensable by Initial Developer to use, reproduce,
          modify, display, perform, sublicense and distribute the Original
          Code (or portions thereof) with or without Modifications, and/or
          as part of a Larger Work; and

          (b) under Patents Claims infringed by the making, using or
          selling of Original Code, to make, have made, use, practice,
          sell, and offer for sale, and/or otherwise dispose of the
          Original Code (or portions thereof).

          (c) the licenses granted in this Section 2.1(a) and (b) are
          effective on the date Initial Developer first distributes
          Original Code under the terms of this License.

          (d) Notwithstanding Section 2.1(b) above, no patent license is
          granted: 1) for code that You delete from the Original Code; 2)
          separate from the Original Code;  or 3) for infringements caused
          by: i) the modification of the Original Code or ii) the
          combination of the Original Code with other software or devices.

     2.2. Contributor Grant.
     Subject to third party intellectual property claims, each Contributor
     hereby grants You a world-wide, royalty-free, non-exclusive license

          (a)  under intellectual property rights (other than patent or
          trademark) Licensable by Contributor, to use, reproduce, modify,
          display, perform, sublicense and distribute the Modifications
          created by such Contributor (or portions thereof) either on an
          unmodified basis, with other Modifications, as Covered Code
          and/or as part of a Larger Work; and

          (b) under Patent Claims infringed by the making, using, or
          selling of  Modifications made by that Contributor either alone
          and/or in combination with its Contributor Version (or portions
          of such combination), to make, use, sell, offer for sale, have
          made, and/or otherwise dispose of: 1) Modifications made by that
          Contributor (or portions thereof); and 2) the combination of
          Modifications made by that Contributor with its Contributor
          Version (or portions of such combination).

          (c) the licenses granted in Sections 2.2(a) and 2.2(b) are
          effective on the date Contributor first makes Commercial Use of
          the Covered Code.

          (d)    Notwithstanding Section 2.2(b) above, no patent license is
          granted: 1) for any code that Contributor has deleted from the
          Contributor Version; 2)  separate from the Contributor Version;
          3)  for infringements caused by: i) third party modifications of
          Contributor Version or ii)  the combination of Modifications made
          by that Contributor with other software  (except as part of the
          Contributor Version) or other devices; or 4) under Patent Claims
          infringed by Covered Code in the absence of Modifications made by
          that Contributor.

3. Distribution Obligations.

     3.1. Application of License.
     The Modifications which You create or to which You contribute are
     governed by the terms of this License, including without limitation
     Section 2.2. The Source Code version of Covered Code may be
     distributed only under the terms of this License or a future version
     of this License released under Section 6.1, and You must include a
     copy of this License with every copy of the Source Code You
     distribute. You may not offer or impose any terms on any Source Code
     version that alters or restricts the applicable version of this
     License or the recipients' rights hereunder. However, You may include
     an additional document offering the additional rights described in
     Section 3.5.

     3.2. Availability of Source Code.
     Any Modification which You create or to which You contribute must be
     made available in Source Code form under the terms of this License
     either on the same media as an Executable version or via an accepted
     Electronic Distribution Mechanism to anyone to whom you made an
     Executable version available; and if made available via Electronic
     Distribution Mechanism, must remain available for at least twelve (12)
     months after the date it initially became available, or at least six
     (6) months after a subsequent version of that particular Modification
     has been made available to such recipients. You are responsible for
     ensuring that the Source Code version remains available even if the
     Electronic Distribution Mechanism is maintained by a third party.

     3.3. Description of Modifications.
     You must cause all Covered Code to which You contribute to contain a
     file documenting the changes You made to create that Covered Code and
     the date of any change. You must include a prominent statement that
     the Modification is derived, directly or indirectly, from Original
     Code provided by the Initial Developer and including the name of the
     Initial Developer in (a) the Source Code, and (b) in any notice in an
     Executable version or related documentation in which You describe the
     origin or ownership of the Covered Code.

     3.4. Intellectual Property Matters
          (a) Third Party Claims.
          If Contributor has knowledge that a license under a third party's
          intellectual property rights is required to exercise the rights
          granted by such Contributor under Sections 2.1 or 2.2,
          Contributor must include a text file with the Source Code
          distribution titled "LEGAL" which describes the claim and the
          party making the claim in sufficient detail that a recipient will
          know whom to contact. If Contributor obtains such knowledge after
          the Modification is made available as described in Section 3.2,
          Contributor shall promptly modify the LEGAL file in all copies
          Contributor makes available thereafter and shall take other steps
          (such as notifying appropriate mailing lists or newsgroups)
          reasonably calculated to inform those who received the Covered
          Code that new knowledge has been obtained.

          (b) Contributor APIs.
          If Contributor's Modifications include an application programming
          interface and Contributor has knowledge of patent licenses which
          are reasonably necessary to implement that API, Contributor must
          also include this information in the LEGAL file.

               (c)    Representations.
          Contributor represents that, except as disclosed pursuant to
          Section 3.4(a) above, Contributor believes that Contributor's
          Modifications are Contributor's original creation(s) and/or
          Contributor has sufficient rights to grant the rights conveyed by
          this License.

     3.5. Required Notices.
     You must duplicate the notice in Exhibit A in each file of the Source
     Code.  If it is not possible to put such notice in a particular Source
     Code file due to its structure, then You must include such notice in a
     location (such as a relevant directory) where a user would be likely
     to look for such a notice.  If You created one or more Modification(s)
     You may add your name as a Contributor to the notice described in
     Exhibit A.  You must also duplicate this License in any documentation
     for the Source Code where You describe recipients' rights or ownership
     rights relating to Covered Code.  You may choose to offer, and to
     charge a fee for, warranty, support, indemnity or liability
     obligations to one or more recipients of Covered Code. However, You
     may do so only on Your own behalf, and not on behalf of the Initial
     Developer or any Contributor. You must make it absolutely clear than
     any such warranty, support, indemnity or liability obligation is
     offered by You alone, and You hereby agree to indemnify the Initial
     Developer and every Contributor for any liability incurred by the
     Initial Developer or such Contributor as a result of warranty,
     support, indemnity or liability terms You offer.

     3.6. Distribution of Executable Versions.
     You may distribute Covered Code in Executable form only if the
     requirements of Section 3.1-3.5 have been met for that Covered Code,
     and if You include a notice stating that the Source Code version of
     the Covered Code is available under the terms of this License,
     including a description of how and where You have fulfilled the
     obligations of Section 3.2. The notice must be conspicuously included
     in any notice in an Executable version, related documentation or
     collateral in which You describe recipients' rights relating to the
     Covered Code. You may distribute the Executable version of Covered
     Code or ownership rights under a license of Your choice, which may
     contain terms different from this License, provided that You are in
     compliance with the terms of this License and that the license for the
     Executable version does not attempt to limit or alter the recipient's
     rights in the Source Code version from the rights set forth in this
     License. If You distribute the Executable version under a different
     license You must make it absolutely clear that any terms which differ
     from this License are offered by You alone, not by the Initial
     Developer or any Contributor. You hereby agree to indemnify the
     Initial Developer and every Contributor for any liability incurred by
     the Initial Developer or such Contributor as a result of any such
     terms You offer.

     3.7. Larger Works.
     You may create a Larger Work by combining Covered Code with other code
     not governed by the terms of this License and distribute the Larger
     Work as a single product. In such a case, You must make sure the
     requirements of this License are fulfilled for the Covered Code.

4. Inability to Comply Due to Statute or Regulation.

     If it is impossible for You to comply with any of the terms of this
     License with respect to some or all of the Covered Code due to
     statute, judicial order, or regulation then You must: (a) comply with
     the terms of this License to the maximum extent possible; and (b)
     describe the limitations and the code they affect. Such description
     must be included in the LEGAL file described in Section 3.4 and must
     be included with all distributions of the Source Code. Except to the
     extent prohibited by statute or regulation, such description must be
     sufficiently detailed for a recipient of ordinary skill to be able to
     understand it.

5. Application of this License.

     This License applies to code to which the Initial Developer has
     attached the notice in Exhibit A and to related Covered Code.

6. Versions of the License.

     6.1. New Versions.
     Netscape Communications Corporation ("Netscape") may publish revised
     and/or new versions of the License from time to time. Each version
     will be given a distinguishing version number.

     6.2. Effect of New Versions.
     Once Covered Code has been published under a particular version of the
     License, You may always continue to use it under the terms of that
     version. You may also choose to use such Covered Code under the terms
     of any subsequent version of the License published by Netscape. No one
     other than Netscape has the right to modify the terms applicable to
     Covered Code created under this License.

     6.3. Derivative Works.
     If You create or use a modified version of this License (which you may
     only do in order to apply it to code which is not already Covered Code
     governed by this License), You must (a) rename Your license so that
     the phrases "Mozilla", "MOZILLAPL", "MOZPL", "Netscape",
     "MPL", "NPL" or any confusingly similar phrase do not appear in your
     license (except to note that your license differs from this License)
     and (b) otherwise make it clear that Your version of the license
     contains terms which differ from the Mozilla Public License and
     Netscape Public License. (Filling in the name of the Initial
     Developer, Original Code or Contributor in the notice described in
     Exhibit A shall not of themselves be deemed to be modifications of
     this License.)

7. DISCLAIMER OF WARRANTY.

     COVERED CODE IS PROVIDED UNDER THIS LICENSE ON AN "AS IS" BASIS,
     WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING,
     WITHOUT LIMITATION, WARRANTIES THAT THE COVERED CODE IS FREE OF
     DEFECTS, MERCHANTABLE, FIT FOR A PARTICULAR PURPOSE OR NON-INFRINGING.
     THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE COVERED CODE
     IS WITH YOU. SHOULD ANY COVERED CODE PROVE DEFECTIVE IN ANY RESPECT,
     YOU (NOT THE INITIAL DEVELOPER OR ANY OTHER CONTRIBUTOR) ASSUME THE
     COST OF ANY NECESSARY SERVICING, REPAIR OR CORRECTION. THIS DISCLAIMER
     OF WARRANTY CONSTITUTES AN ESSENTIAL PART OF THIS LICENSE. NO USE OF
     ANY COVERED CODE IS AUTHORIZED HEREUNDER EXCEPT UNDER THIS DISCLAIMER.

8. TERMINATION.

     8.1.  This License and the rights granted hereunder will terminate
     automatically if You fail to comply with terms herein and fail to cure
     such breach within 30 days of becoming aware of the breach. All
     sublicenses to the Covered Code which are properly granted shall
     survive any termination of this License. Provisions which, by their
     nature, must remain in effect beyond the termination of this License
     shall survive.

     8.2.  If You initiate litigation by asserting a patent infringement
     claim (excluding declatory judgment actions) against Initial Developer
     or a Contributor (the Initial Developer or Contributor against whom
     You file such action is referred to as "Participant")  alleging that:

     (a)  such Participant's Contributor Version directly or indirectly
     infringes any patent, then any and all rights granted by such
     Participant to You under Sections 2.1 and/or 2.2 of this License
     shall, upon 60 days notice from Participant terminate prospectively,
     unless if within 60 days after receipt of notice You either: (i)
     agree in writing to pay Participant a mutually agreeable reasonable
     royalty for Your past and future use of Modifications made by such
     Participant, or (ii) withdraw Your litigation claim with respect to
     the Contributor Version against such Participant.  If within 60 days
     of notice, a reasonable royalty and payment arrangement are not
     mutually agreed upon in writing by the parties or the litigation claim
     is not withdrawn, the rights granted by Participant to You under
     Sections 2.1 and/or 2.2 automatically terminate at the expiration of
     the 60 day notice period specified above.

     (b)  any software, hardware, or device, other than such Participant's
     Contributor Version, directly or indirectly infringes any patent, then
     any rights granted to You by such Participant under Sections 2.1(b)
     and 2.2(b) are revoked effective as of the date You first made, used,
     sold, distributed, or had made, Modifications made by that
     Participant.

     8.3.  If You assert a patent infringement claim against Participant
     alleging that such Participant's Contributor Version directly or
     indirectly infringes any patent where such claim is resolved (such as
     by license or settlement) prior to the initiation of patent
     infringement litigation, then the reasonable value of the licenses
     granted by such Participant under Sections 2.1 or 2.2 shall be taken
     into account in determining the amount or value of any payment or
     license.

     8.4.  In the event of termination under Sections 8.1 or 8.2 above,
     all end user license agreements (excluding distributors and resellers)
     which have been validly granted by You or any distributor hereunder
     prior to termination shall survive termination.

9. LIMITATION OF LIABILITY.

     UNDER NO CIRCUMSTANCES AND UNDER NO LEGAL THEORY, WHETHER TORT
     (INCLUDING NEGLIGENCE), CONTRACT, OR OTHERWISE, SHALL YOU, THE INITIAL
     DEVELOPER, ANY OTHER CONTRIBUTOR, OR ANY DISTRIBUTOR OF COVERED CODE,
     OR ANY SUPPLIER OF ANY OF SUCH PARTIES, BE LIABLE TO ANY PERSON FOR
     ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY
     CHARACTER INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF GOODWILL,
     WORK STOPPAGE, COMPUTER FAILURE OR MALFUNCTION, OR ANY AND ALL OTHER
     COMMERCIAL DAMAGES OR LOSSES, EVEN IF SUCH PARTY SHALL HAVE BEEN
     INFORMED OF THE POSSIBILITY OF SUCH DAMAGES. THIS LIMITATION OF
     LIABILITY SHALL NOT APPLY TO LIABILITY FOR DEATH OR PERSONAL INJURY
     RESULTING FROM SUCH PARTY'S NEGLIGENCE TO THE EXTENT APPLICABLE LAW
     PROHIBITS SUCH LIMITATION. SOME JURISDICTIONS DO NOT ALLOW THE
     EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO
     THIS EXCLUSION AND LIMITATION MAY NOT APPLY TO YOU.

10. U.S. GOVERNMENT END USERS.

     The Covered Code is a "commercial item," as that term is defined in
     48 C.F.R. 2.101 (Oct. 1995), consisting of "commercial computer
     software" and "commercial computer software documentation," as such
     terms are used in 48 C.F.R. 12.212 (Sept. 1995). Consistent with 48
     C.F.R. 12.212 and 48 C.F.R. 227.7202-1 through 227.7202-4 (June 1995),
     all U.S. Government End Users acquire Covered Code with only those
     rights set forth herein.

11. MISCELLANEOUS.

     This License represents the complete agreement concerning subject
     matter hereof. If any provision of this License is held to be
     unenforceable, such provision shall be reformed only to the extent
     necessary to make it enforceable. This License shall be governed by
     California law provisions (except to the extent applicable law, if
     any, provides otherwise), excluding its conflict-of-law provisions.
     With respect to disputes in which at least one party is a citizen of,
     or an entity chartered or registered to do business in the United
     States of America, any litigation relating to this License shall be
     subject to the jurisdiction of the Federal Courts of the Northern
     District of California, with venue lying in Santa Clara County,
     California, with the losing party responsible for costs, including
     without limitation, court costs and reasonable attorneys' fees and
     expenses. The application of the United Nations Convention on
     Contracts for the International Sale of Goods is expressly excluded.
     Any law or regulation which provides that the language of a contract
     shall be construed against the drafter shall not apply to this
     License.

12. RESPONSIBILITY FOR CLAIMS.

     As between Initial Developer and the Contributors, each party is
     responsible for claims and damages arising, directly or indirectly,
     out of its utilization of rights under this License and You agree to
     work with Initial Developer and Contributors to distribute such
     responsibility on an equitable basis. Nothing herein is intended or
     shall be deemed to constitute any admission of liability.

13. MULTIPLE-LICENSED CODE.

     Initial Developer may designate portions of the Covered Code as
     "Multiple-Licensed".  "Multiple-Licensed" means that the Initial
     Developer permits you to utilize portions of the Covered Code under
     Your choice of the NPL or the alternative licenses, if any, specified
     by the Initial Developer in the file described in Exhibit A.

EXHIBIT A -Mozilla Public License.

     ``The contents of this file are subject to the Mozilla Public License
     Version 1.1 (the "License"); you may not use this file except in
     compliance with the License. You may obtain a copy of the License at
     http://www.mozilla.org/MPL/

     Software distributed under the License is distributed on an "AS IS"
     basis, WITHOUT WARRANTY OF ANY KIND, either express or implied. See the
     License for the specific language governing rights and limitations
     under the License.

     The Original Code is ______________________________________.

     The Initial Developer of the Original Code is ________________________.
     Portions created by ______________________ are Copyright (C) ______
     _______________________. All Rights Reserved.

     Contributor(s): ______________________________________.

     Alternatively, the contents of this file may be used under the terms
     of the _____ license (the  "[___] License"), in which case the
     provisions of [______] License are applicable instead of those
     above.  If you wish to allow use of your version of this file only
     under the terms of the [____] License and not to allow others to use
     your version of this file under the MPL, indicate your decision by
     deleting  the provisions above and replace  them with the notice and
     other provisions required by the [___] License.  If you do not delete
     the provisions above, a recipient may use your version of this file
     under either the MPL or the [___] License."

     [NOTE: The text of this Exhibit A may differ slightly from the text of
     the notices in the Source Code files of the Original Code. You should
     use the text of this Exhibit A rather than the text found in the
     Original Code Source Code for Your Modifications.]
================================================================================


================================================================================
Unlicense --- This license applies to:

* Galician hyphenation patterns

  Paths: `patterns/hyph-gl.tex`, `tries/gl.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-gl.tex
  Notice: Copyright (C) 2006, 2007, 2008, 2010 Javier A. Múgica

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>
================================================================================


================================================================================
FSFAP-no-warranty-disclaimer --- This license applies to:

* English hyphenation patterns

  Paths: `patterns/hyph-en-us.tex`, `tries/en.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-en-us.tex
  Notice: Copyright (C) 1990, 2004, 2005 Gerard D.C. Kuiken

Copying and distribution of this file, with or without modification, are
permitted in any medium without royalty provided the copyright notice and this
notice are preserved.
================================================================================


================================================================================
FSFAP-no-warranty-disclaimer --- This license applies to:

* Norwegian hyphenation patterns

  Paths: `patterns/hyph-no.tex`, `tries/no.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-no.tex
  Notice: Copyright (C) 2004, 2005 Rune Kleveland, Ole Michael Selberg

Copying and distribution of this file, with or without modification, is
permitted in any medium without royalty provided the copyright notice and this
notice are preserved.
================================================================================


================================================================================
LicenseRef-hyph-bg (Bulgarian Hyphenation Patterns License) --- This license
applies to:

* Bulgarian hyphenation patterns

  Paths: `patterns/hyph-bg.tex`, `tries/bg.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-bg.tex
  Notice: Copyright (C) 2000, 2004, 2017 Anton Zinoviev

This software may be used, modified, copied, distributed, and sold, both in
source and binary form provided that the above copyright notice and these terms
are retained. The name of the author may not be used to endorse or promote
products derived from this software without prior permission. THIS SOFTWARE IS
PROVIDES "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES ARE DISCLAIMED. IN NO
EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DAMAGES ARISING IN ANY WAY OUT OF THE
USE OF THIS SOFTWARE.
================================================================================


================================================================================
LicenseRef-hyph-sa (Sanskrit Hyphenation Patterns License) --- This license
applies to:

* Sanskrit hyphenation patterns

  Paths: `patterns/hyph-sa.tex`, `tries/sa.bin`
  Source: https://github.com/hyphenation/tex-hyphen/blob/master/hyph-utf8/tex/generic/hyph-utf8/patterns/tex/hyph-sa.tex
  Notice: Copyright (C) 2006-2011 Yves Codet

You may freely use, copy, modify and/or distribute this file.
================================================================================
~~~~
