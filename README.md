# LTX ComfyUI Workflow Index

> **Independent platform notice:** Maintained by
> [LTX.dev](https://ltx.dev), an independent multi-model AI video platform.
> Not affiliated with or endorsed by Lightricks.

A versioned, documented index for reproducible ComfyUI workflows using LTX video
models.

[Explore LTX.dev](https://ltx.dev) ·
[Official ComfyUI integration](https://github.com/Lightricks/ComfyUI-LTXVideo) ·
[Official LTX-2 source](https://github.com/Lightricks/LTX-2)

## Upstream-first policy

Canonical workflows belong in the official integration whenever possible. This
repository will contribute upstream first, then index and annotate canonical
workflows. It will not silently fork official workflow files.

## Planned workflow catalog

| Workflow | Purpose | Status |
|---|---|---|
| Text-to-video starter | First local generation | Awaiting validation |
| Image-to-video | Animate a reference image | Awaiting validation |
| Synchronized audio-video | Dialogue and ambience | Awaiting validation |
| Keyframe interpolation | Controlled transitions | Awaiting validation |
| Low-VRAM generation | Constrained hardware | Awaiting validation |

See [`workflows/README.md`](workflows/README.md) for the required directory and
manifest format.

## Safety and quality

Workflow files must not contain local absolute paths, secrets, personal data, or
unlicensed preview media. Compatibility and VRAM claims require a dated test
record.

## License

Original index content is available under the [MIT License](LICENSE). Each
workflow and preview must document its own provenance and applicable licenses.
Versioned and documented ComfyUI workflows for LTX video generation.
