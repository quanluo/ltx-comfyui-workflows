# LTX-2.3 Two-Stage Text/Image-to-Video Workflow

Status: official workflow indexed from reviewed commit `3b9c5cd`; not
independently executed by LTX.dev.

[Download the canonical workflow JSON](https://github.com/Lightricks/ComfyUI-LTXVideo/blob/3b9c5cde4700917074823d45e25401d81049f8fc/example_workflows/2.3/LTX-2.3_T2V_I2V_Two_Stage_Distilled.json)

## Use this workflow when

- you want the upstream two-stage distilled graph;
- you want a base generation followed by spatial upsampling/refinement;
- you need text-to-video or image-to-video conditioning.

## Additional models

In addition to the distilled checkpoint and Gemma encoder, the official
repository lists a spatial upscaler and distilled LoRA for current two-stage
workflows. Use the filenames from the current upstream README rather than
guessing from older tutorials.

## Import checklist

- Install or update the official LTX custom nodes.
- Import the immutable canonical JSON linked above.
- Resolve every red or missing node before queueing.
- Select the matching LTX-2.3 checkpoint, spatial upscaler, Gemma directory,
  and LoRA.
- Replace example media and prompts.
- Inspect output dimensions and save paths.
- Save a local copy with your environment-specific choices.

## Why two stages

The official Python pipeline documentation describes two-stage pipelines as the
recommended production-quality path and includes an upsampling/refinement
stage. This workflow is the ComfyUI-side canonical example; results still depend
on the graph revision and local settings.

## Provenance

Workflow copyright and license remain with the upstream project. This page is
an independent index and operational summary.
