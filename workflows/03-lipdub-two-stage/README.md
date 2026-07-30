# LTX-2.3 Two-Stage Lipdub Workflow

Status: official workflow indexed from reviewed commit `3b9c5cd`; not
independently executed by LTX.dev.

[Download the canonical workflow JSON](https://github.com/Lightricks/ComfyUI-LTXVideo/blob/3b9c5cde4700917074823d45e25401d81049f8fc/example_workflows/2.3/LTX-2.3_ICLoRA_Lipdub_Two_Stage_Distilled.json)

## Use this workflow when

- you have a source video with a visible speaker;
- you want to rephrase or translate the spoken content;
- you need generated lip motion and audio conditioned by the source.

## Required care

Use only video, voice, and identity material you have permission to process.
Obtain consent for real people. Clearly disclose synthetic or altered speech
where required. Do not use the workflow for impersonation, fraud, or deceptive
media.

## Setup

1. Install the current official LTX custom nodes.
2. Download the current distilled checkpoint, spatial upscaler, Gemma encoder,
   distilled LoRA, and official LipDub IC-LoRA listed upstream.
3. Import the canonical JSON.
4. Replace the bundled/example source with authorized media.
5. Write the intended dialogue explicitly in the prompt.
6. Review identity preservation, mouth motion, audio clarity, and disclosure
   requirements before distributing the output.

## Upstream behavior

The official README describes a two-stage process: base audio-video generation
followed by spatial upsampling while audio is frozen. It also describes
reference-audio conditioning for speaker context. Those are upstream claims,
not independent LTX.dev benchmark results.

## Provenance

Workflow copyright and license remain with the upstream project. This page is
an independent index and safety-oriented operational summary.
