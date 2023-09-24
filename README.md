# Blazor.WebAuthentication
A Blazor wrapper for the [Web Authentication](https://www.w3.org/TR/webauthn-3/) browser API.

The API specified ways to create and validate strong public-key-based credentials. It gets these credentials from the native authenticators of the devices. On Windows, that's Windows Hello; on iOS/macOS, that's Touch ID or Face ID; and on Android, that's face, fingerprint, or PIN authentication. This project implements a wrapper around the API for Blazor so that we can easily and safely work with native authentication methods from the browser.

# Related articles
This repository was built with inspiration and help from the following series of articles:

- [Typed exceptions for JSInterop in Blazor](https://kristoffer-strube.dk/post/typed-exceptions-for-jsinterop-in-blazor/)
- [Wrapping Compression Streams in Blazor](https://kristoffer-strube.dk/post/wrapping-compression-streams-in-blazor/)
- [Wrapping JavaScript libraries in Blazor WebAssembly/WASM](https://blog.elmah.io/wrapping-javascript-libraries-in-blazor-webassembly-wasm/)
- [Call anonymous C# functions from JS in Blazor WASM](https://blog.elmah.io/call-anonymous-c-functions-from-js-in-blazor-wasm/)
- [Using JS Object References in Blazor WASM to wrap JS libraries](https://blog.elmah.io/using-js-object-references-in-blazor-wasm-to-wrap-
