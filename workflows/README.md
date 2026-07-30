# Workflow Submission Contract

Use one directory per workflow:

```text
workflows/<slug>/
├── workflow.json
├── README.md
├── manifest.yaml
├── preview.webp
└── LICENSE-ASSETS.md
```

`manifest.yaml` must record:

- LTX model and version;
- ComfyUI version;
- required custom nodes and exact revisions;
- required model files and expected locations;
- tested GPU/VRAM class;
- inputs, outputs, author, license, and last-tested date.

Before merge, confirm that JSON parses, dependencies resolve, paths are
portable, secrets are absent, and preview rights are documented.
