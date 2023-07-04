+++
title = "Bindings"
description = "Bindings to an existing, non-Rust GUI framework"
criteria = "TODO"

[extra]

# TODO: Unsure how this should be categorised?
[crates.gemgui]
name = "GemGui"
technology = "web"
os = ["desktop", "android"]

# TODO: Unsure how this should be categorised?
[crates.imgui]
technology = "custom"
os = ["desktop", "mobile"]

[crates.gtk]
name = "GTK 3"
docs = "https://gtk-rs.org/docs-src/"
technology = "gtk"
os = ["desktop"]

[crates.gtk4]
name = "GTK 4"
technology = "gtk"
os = ["desktop"]

[crates.flutter_rust_bridge]
technology = "custom"
os = ["desktop", "mobile", "web"]

[crates.winsafe]
name = "WinSafe"
technology = "native"
os = ["windows"]

[crates.iui]
technology = "native"
os = ["desktop"]

[crates.lvgl]
technology = "custom"
os = ["embedded"]

[crates.fltk]
technology = "custom"
os = ["desktop"]

[crates.qt_widgets]
description = "Ritual Qt bindings"
docs = "https://rust-qt.github.io/qt/"
technology = "qt"
os = ["desktop", "mobile", "embedded", "web"] # Unverified

[crates.rust-qt-binding-generator]
technology = "qt"
os = ["desktop", "mobile", "embedded", "web"] # Unverified

[crates.qmetaobject]
description = "A framework empowering everyone to create Qt/QML applications with Rust. It does so by building QMetaObjects at compile time, registering QML types (optionally via exposing QQmlExtensionPlugins) and providing idiomatic wrappers."
technology = "qt"
os = ["desktop", "mobile", "embedded", "web"] # Unverified

[crates.cxx-qt]
name = "CXX-Qt"
description = "CXX-Qt is a library that automatically generates code to transfer data between Rust and C++ through common interfaces such as QObjects that can be exposed directly into QML. It uses the cxx crate for safe interaction between Rust and C++."
docs = "https://kdab.github.io/cxx-qt/book/"
technology = "qt"
os = ["desktop", "mobile", "embedded", "web"] # Unverified

[crates.sciter-rs]
name = "Sciter"
technology = "web"
os = ["desktop", "mobile", "embedded"]

[crates.core-foundation]
technology = "native"
os = ["macos", "ios"]

[crates.cacao]
technology = "native"
os = ["macos", "ios"]

+++
