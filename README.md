# forge.dotnet.toolchain

A Rust crate that drives Microsoft’s dotnetup to install, update and remove .NET SDKs in a user-owned folder, reading its JSON state and mapping failures to typed errors. Built for IDE integration: no admin rights, no shell profile edits, per-process DOTNET_ROOT and PATH.
