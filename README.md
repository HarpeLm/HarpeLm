<div align="center">

# Hi, I'm HarpeLm 👋

**Medical student in Switzerland who loves to code.**
Jack of all trades: I learn by building things from scratch.

![Geneva](https://img.shields.io/badge/📍_Geneva-Switzerland-DC143C?style=flat-square)
![Med student](https://img.shields.io/badge/🩺_Medical-student-0A84FF?style=flat-square)
![Open source](https://img.shields.io/badge/🦀_Open_source-contributor-F74C00?style=flat-square)

</div>

---

## 🌱 About me

<table align="center">
<tr>
<td align="center" width="33%">
<h3>🩺</h3>
<b>Medicine</b><br>
<sub>Med student in Geneva,<br>coding in my spare time</sub>
</td>
<td align="center" width="33%">
<h3>🦀</h3>
<b>Rust first</b><br>
<sub>Browsers, engines, tools.<br>Swift for iOS</sub>
</td>
<td align="center" width="33%">
<h3>🔥</h3>
<b>Open source</b><br>
<sub>Contributing to Burn,<br>deep learning in Rust</sub>
</td>
</tr>
</table>

```rust
struct HarpeLm {
    location: &'static str,
    studies: &'static str,
    languages: [&'static str; 3],
    contributing_to: &'static str,
    currently_building: [&'static str; 3],
}

impl HarpeLm {
    fn new() -> Self {
        Self {
            location: "Geneva, Switzerland 🇨🇭",
            studies: "Medicine 🩺",
            languages: ["Rust", "Swift", "Python"],
            contributing_to: "tracel-ai/burn-onnx",
            currently_building: ["a browser engine", "a chess engine", "iOS apps"],
        }
    }

    fn motto(&self) -> &str {
        "Jack of all trades: learn by building things from scratch."
    }
}
```

## 🤝 Open source

<table>
<tr>
<td>

**[tracel-ai/burn-onnx#592](https://github.com/tracel-ai/burn-onnx/pull/592)** · ![merged](https://img.shields.io/badge/merged-8957e5?style=flat-square&logo=github&logoColor=white)

**Split: accept Shape as split sizes input**
Fixed `Split` rejecting `Shape` inputs and its codegen for runtime `Shape` split sizes, which unblocked 5 official ONNX `rotary_embedding` tests.

</td>
</tr>
</table>

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌐 [Lumen](https://github.com/HarpeLm/Lumen)
A web browser engine written from scratch, tested against the official suites (html5lib, WPT).

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

</td>
<td width="50%" valign="top">

### 🪐 [Aetheris](https://github.com/HarpeLm/Aetheris)
A from-scratch desktop web browser: no Chromium, WebKit or Gecko.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![WGSL](https://img.shields.io/badge/WGSL-005A9C?style=flat-square&logo=webgpu&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ♟️ [chessengine](https://github.com/HarpeLm/chessengine)
A chess engine that learns by playing itself, with a local web UI.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
<td width="50%" valign="top">

### 🤖 [EDITH](https://github.com/HarpeLm/EDITH)
A desktop AI assistant with tools and memory.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💧 [AquApp](https://github.com/HarpeLm/AquApp)
A hydration tracker for iPhone, built with friends for fun.

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0A84FF?style=flat-square&logo=swift&logoColor=white)

</td>
<td width="50%" valign="top">

### 🎬 [Framey](https://github.com/HarpeLm/Framey)
An iOS movie and TV diary: watchlist, lists, ratings.

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

</td>
</tr>
</table>

## 🛠️ Tech

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,swift,py,html,css,js,git,apple&theme=dark" alt="Rust, Swift, Python, HTML, CSS, JavaScript, Git, Apple" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Burn-deep_learning-F74C00?style=flat-square" alt="Burn" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" />
</p>
