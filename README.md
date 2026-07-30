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
| [Single-stage T2V/I2V](workflows/01-t2v-i2v-single-stage/README.md) | Text or image generation | Official workflow indexed |
| [Two-stage T2V/I2V](workflows/02-t2v-i2v-two-stage/README.md) | Generation with upsampling | Official workflow indexed |
| [Lipdub two-stage](workflows/03-lipdub-two-stage/README.md) | Rephrase or dub a source video | Official workflow indexed |
| Keyframe interpolation | Controlled transitions | Awaiting validation |
| Low-VRAM generation | Constrained hardware | Awaiting validation |

The entries link to immutable upstream workflow files at reviewed commit
`3b9c5cd`. LTX.dev does not redistribute or claim authorship of the official
JSON. See [`workflows/README.md`](workflows/README.md) for the submission format.

## Safety and quality

Workflow files must not contain local absolute paths, secrets, personal data, or
unlicensed preview media. Compatibility and VRAM claims require a dated test
record.

## License

Original index content is available under the [MIT License](LICENSE). Each
workflow and preview must document its own provenance and applicable licenses.
Versioned and documented ComfyUI workflows for LTX video generation.
