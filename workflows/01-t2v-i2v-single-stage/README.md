# LTX-2.3 Single-Stage Text/Image-to-Video Workflow

Status: official workflow indexed from reviewed commit `3b9c5cd`; not
independently executed by LTX.dev.

[Download the canonical workflow JSON](https://github.com/Lightricks/ComfyUI-LTXVideo/blob/3b9c5cde4700917074823d45e25401d81049f8fc/example_workflows/2.3/LTX-2.3_T2V_I2V_Single_Stage_Distilled_Full.json)

## Use this workflow when

- you want a current LTX-2.3 starter graph;
- you need text-to-video or first-frame image conditioning;
- you prefer a single-stage graph without the separate spatial upsampling pass.

The upstream file supports full and distilled model paths. Inspect all node
values after importing; a JSON workflow is not a substitute for the current
upstream README.

## Setup

1. Install current ComfyUI.
2. Install `Lightricks/ComfyUI-LTXVideo` through Comfy Manager or the documented
   custom-node method.
3. Download the checkpoint and Gemma text encoder listed in the current
   [official README](https://github.com/Lightricks/ComfyUI-LTXVideo).
4. Import the canonical JSON.
5. Confirm every model selector resolves to a local file.
6. For image-to-video, replace the example input with media you may use.

## Review notes

The official repository states that LTX-2 is built into ComfyUI core and that
this extension supplies additional nodes and workflows. Hardware and storage
requirements change with checkpoint, precision, and graph configuration; this
index makes no independent minimum claim.

## Provenance

Workflow copyright and license remain with the upstream project. This page is
an independent index and operational summary.
