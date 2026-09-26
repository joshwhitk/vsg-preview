# vsg preview

A friends-and-family web preview distribution for the recovered Surviving Independence/VSG game work.

## Scope and status

- index.html and Build/ contain the exported Unity WebGL player. The editable Unity source lives in surviving-independence; this repository is the distribution artifact.
- Use an HTTP server configured for the build's compressed files and WebAssembly MIME types. A basic file preview may fail even when all build files are present.
- Build artifacts are being updated independently; refer to the current commit/build stamp rather than assuming a particular numbered build from this README.

Documentation reviewed from source and available project history on 2026-09-27. The application was not started or acceptance-tested as part of this documentation update.
