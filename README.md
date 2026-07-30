# LTX ComfyUI Workflow Index

> **Independent platform notice:** Maintained by
> [LTX.dev](https://ltx.dev), an independent multi-model AI video platform.
> Not affiliated with or endorsed by Lightricks.

A versioned index for ComfyUI workflows using LTX video models, connected to
hosted multi-model generation, documentation, examples, and prompt recipes.

[Use LTX.dev Studio](https://ltx.dev/studio/text-to-video) ·
[Workflow library guide](https://github.com/quanluo/ltx-video-docs/blob/main/docs/workflows/ltx-workflow-library.md) ·
[Local generation guide](https://github.com/quanluo/ltx-video-docs/blob/main/docs/guides/local-ai-video-generation.md) ·
[Developer guide](https://github.com/quanluo/ltx-video-docs/blob/main/docs/developers/ltx-developer-guide.md) ·
[Official ComfyUI integration](https://github.com/Lightricks/ComfyUI-LTXVideo) ·
[Examples](https://github.com/quanluo/ltx-video-examples) ·
[Prompts](https://github.com/quanluo/ltx-video-prompts)

## Choose a workflow path

| Goal | Local workflow | Hosted path |
|---|---|---|
| Generate from text | [Single-stage T2V/I2V](workflows/01-t2v-i2v-single-stage/README.md) | [Text to video](https://ltx.dev/studio/text-to-video) |
| Generate and upscale | [Two-stage T2V/I2V](workflows/02-t2v-i2v-two-stage/README.md) | [LTX 2.3](https://ltx.dev/studio/text-to-video/ltx) |
| Rephrase or dub video | [Lipdub two-stage](workflows/03-lipdub-two-stage/README.md) | [Audio to video](https://ltx.dev/studio/audio-to-video) |
| Compare model options | [Workflow guide](https://github.com/quanluo/ltx-video-docs/blob/main/docs/workflows/ltx-workflow-library.md) | [Model workspace](https://ltx.dev/studio/text-to-video) |

## Upstream-first policy

Canonical workflows belong in the official integration whenever possible. This
repository indexes and annotates upstream files; it does not claim authorship
of official workflow JSON.

The current entries link to immutable upstream files at reviewed commit
`3b9c5cd`.

## Submission format

See [`workflows/README.md`](workflows/README.md). Every entry identifies model
version, node dependencies, provenance, author, license, and source URL.

## Related ecosystem resources

- [AI video model benchmark](https://github.com/quanluo/ltx-video-docs/blob/main/docs/benchmarks/ai-video-model-benchmark.md)
- [Open-weight model comparison](https://github.com/quanluo/ltx-video-docs/blob/main/docs/comparisons/open-source-ai-video-models.md)
- [Prompt cookbook](https://github.com/quanluo/ltx-video-prompts)
- [Independent ecosystem hub](https://github.com/quanluo/ltx-dev-ecosystem)

## Safety and quality

Workflow files must not contain secrets, personal data, unsafe download steps,
or unlicensed preview media. Compatibility notes distinguish upstream claims
from community observations.

## License

Original index content is available under the [MIT License](LICENSE). Each
workflow and preview retains its documented provenance and license.
