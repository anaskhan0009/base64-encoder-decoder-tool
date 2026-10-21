# Free Online Base64 Encoder & Decoder — Text, URL-Safe & File to Base64 Converter

A free **Base64 encoder and decoder** that runs entirely in your browser. Convert text to Base64 and back (fully **UTF-8 safe** — emoji and every language work), switch to the **URL-safe Base64 variant**, and turn any file into a **Base64 data string** for embedding or API testing.

**Live Demo:** https://anaskhan0009.github.io/base64-encoder-decoder-tool/

## Features

- **Text ⇄ Base64** encoding and decoding with correct UTF-8 handling (no broken characters on non-English text)
- **URL-safe mode** — uses `-` and `_` instead of `+` and `/`, padding handled automatically
- **File to Base64** — any file becomes a `data:` URL or raw Base64 string, with an image preview
- **Smart decode errors** — tells you whether input is invalid Base64 or valid Base64 of binary (non-text) data
- **Size report** — characters, UTF-8 bytes and Base64 length for every conversion
- **Education section** — what Base64 is, where it's used (email MIME, data URLs, JWTs, APIs), and why it is *not* encryption

## How to Use

1. Type text in the top box and press **Encode**, or paste Base64 in the bottom box and press **Decode**.
2. Tick **URL-safe variant** when the result will go into a URL, filename or token.
3. For files: choose a file, then copy the data URL (or tick "Raw Base64 only" for the bare string).

## Why Developers and Security Learners Use Base64 Daily

Base64 rewrites binary data as safe text so it can travel through email, URLs, JSON and HTML. Defenders also decode Base64 constantly — attackers hide payloads and phishing links inside it. This converter makes both directions instant, private and correct, including the tricky UTF-8 cases many online tools get wrong.

## Privacy

Everything runs locally in your browser. No text or file is ever uploaded, stored or logged.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, TextEncoder/TextDecoder, FileReader API.

## Ethical Use

This tool is for **development, learning and defensive analysis** — for example decoding a suspicious string to inspect what it really contains. Base64 provides **zero secrecy**: never use it to "hide" passwords or secrets, and only decode content you have a legitimate reason to inspect.

## About

Built by **Dinal Studios** — digital agency for video editing, design, web & app development.
GitHub: https://github.com/anaskhan0009

*Keywords: base64 encoder online, base64 decoder online, base64 converter, file to base64, image to base64, url safe base64, base64 encode text, base64 decode tool, data url generator*
