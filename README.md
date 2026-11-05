# Catalina Resampler

Standalone UTAU command-line resampler for the Kamafeu NSF HiFi-GAN engine. The binary is distributed separately from Kamafeu Studio and can be installed from its Additional Packages manager.

The ONNX model is not bundled. Select or install the compatible model through Kamafeu's engine setup. Releases include the platform ONNX Runtime dependencies when required.

## Build

```sh
cargo build --release --locked
```

## License

MIT. Kamafeu core is used as a Git dependency; retain the upstream notices.
