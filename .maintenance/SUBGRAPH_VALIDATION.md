# Workflow Presentation Validation

This comparison checks JSON structure and unchanged saved data. It does not prove runtime functionality or visual quality.

Visual inspection is a separate user review. No workflow execution was performed by this validator.

## Frame Interpolation.json

Result: **PASS** — 10 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `722d571621f33bd7a614553a2cf4ca5b99d2c4117ea866fd8d12b8fddc69eb1f`

Modified SHA-256: `0d66332fd37a9a13917f750b29792a080f11ba9831fa644a5dddaed049b87c0a`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/3/bgcolor | Node 31 (PrimitiveInt) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/3/color | Node 31 (PrimitiveInt) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/3/title | Node 31 (PrimitiveInt) | "Int (Multiplier)" | "Frame Multiplier" | Allowed |
| /definitions/subgraphs/0/nodes/5/bgcolor | Node 33 (PrimitiveBoolean) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/5/color | Node 33 (PrimitiveBoolean) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/5/title | Node 33 (PrimitiveBoolean) | "Boolean (Apply multiplier to FPS?)" | "Apply Multiplier to Frame Rate" | Allowed |
| /nodes/0/bgcolor | Node 36 (d1c9ad27-2f53-4822-bd6a-a999e024466a) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 36 (d1c9ad27-2f53-4822-bd6a-a999e024466a) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/8 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 38, "type": "MarkdownNote", "pos": [-3360, -3080], "size": [480, 360], "flags": {}, "order": 8, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nAdd frames between the existing frames of a video and return both the rebuilt video and the frame sequence.\n\n### How to Use\n\n1. Connect a video to **video** and select a model in **model_name**.\n2. Set **multiplier**. Turn on **enable_fps_multiplier** to increase the playback frame rate. Leave it off to keep the source frame rate and slow down playback.\n3. Use **VIDEO** for the assembled clip or **IMAGE** for the frames."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 37 | 38 | Allowed |

## Image to Ideogram Prompt.json

Result: **PASS** — 8 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `8d5e4b79a89f6cf6a8483be8a09881ee0fdecf732ffeeea02d2d47045fa9e4e7`

Modified SHA-256: `752c051f8985bd7fb4507ca5ae65b36a361b528b01022f50fb48b222c745e743`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/1/bgcolor | Node 190 (OllamaChat) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/1/color | Node 190 (OllamaChat) | (absent; ComfyUI default) | "#35414A" | Allowed |
| /definitions/subgraphs/0/nodes/1/title | Node 190 (OllamaChat) | (absent; ComfyUI default) | "Expand Ideogram Prompt" | Allowed |
| /nodes/0/bgcolor | Node 191 (52d489ca-ffb3-4e04-8508-5d3db8beae91) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 191 (52d489ca-ffb3-4e04-8508-5d3db8beae91) | (absent; ComfyUI default) | "#235B74" | Allowed |
| /nodes/0/title | Node 191 (52d489ca-ffb3-4e04-8508-5d3db8beae91) | "Image to Ideogram Prompt" | "Expand Prompt for Ideogram" | Allowed |
| /definitions/subgraphs/0/nodes/2 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 192, "type": "MarkdownNote", "pos": [5480, 1500], "size": [480, 360], "flags": {}, "order": 2, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nTurn a text idea into a structured Ideogram caption using Ollama.\n\n### How to Use\n\n1. Connect a text description to **prompt** and make sure Ollama has the model selected inside the node.\n2. The saved node is bypassed. Enable it when you want to generate a caption.\n3. Connect **result** to an Ideogram prompt builder that accepts structured captions or to a text preview."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 191 | 192 | Allowed |

## Image to Ideogram Realistic Prompt.json

Result: **PASS** — 8 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `a257530f117f711eaed73f44eb2291d8814c8fa873199ae36b3c192980b497da`

Modified SHA-256: `c56ed7cd57eccd737e8427ad30f0ef6610419566c54363ea6fc9e5e800ef6eda`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/0/bgcolor | Node 210 (OllamaChat) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/0/color | Node 210 (OllamaChat) | (absent; ComfyUI default) | "#35414A" | Allowed |
| /definitions/subgraphs/0/nodes/0/title | Node 210 (OllamaChat) | (absent; ComfyUI default) | "Expand Realistic Ideogram Prompt" | Allowed |
| /nodes/0/bgcolor | Node 211 (a64aa18c-8922-4f43-8971-7380f5d50f25) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 211 (a64aa18c-8922-4f43-8971-7380f5d50f25) | (absent; ComfyUI default) | "#235B74" | Allowed |
| /nodes/0/title | Node 211 (a64aa18c-8922-4f43-8971-7380f5d50f25) | "Image to Ideogram Realistic Prompt" | "Expand Realistic Prompt for Ideogram" | Allowed |
| /definitions/subgraphs/0/nodes/2 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 212, "type": "MarkdownNote", "pos": [5480, 1500], "size": [480, 360], "flags": {}, "order": 2, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nTurn a text idea into a structured caption for realistic Ideogram images using Ollama.\n\n### How to Use\n\n1. Connect a scene description to **prompt** and make sure Ollama has the model selected inside the node.\n2. Connect **result** to an Ideogram prompt builder that accepts structured captions or to a text preview."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 211 | 212 | Allowed |

## Klein Inpaint.json

Result: **PASS** — 8 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `efba69c9e54a8e93d17e2b2024fb8c33eda59fca9a74a226ce5c8163086e48a8`

Modified SHA-256: `3c5d04006a840608b99a45959efb30806505fb72b29e2e59f8c32bbe078e5799`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/4/title | Node 10 (VAEEncode) | "Match VAE Geometry (encode)" | "Match VAE Geometry (Encode)" | Allowed |
| /definitions/subgraphs/0/nodes/6/title | Node 8 (CLIPTextEncode) | "Negative Prompt (optional, CFG 1)" | "Negative Prompt (Optional, CFG 1)" | Allowed |
| /definitions/subgraphs/0/nodes/8/title | Node 11 (VAEDecode) | "Match VAE Geometry (decode)" | "Match VAE Geometry (Decode)" | Allowed |
| /definitions/subgraphs/0/nodes/14/title | Node 13 (ImageScale) | "Aligned Source (original colors)" | "Aligned Source (Original Colors)" | Allowed |
| /definitions/subgraphs/0/nodes/23/title | Node 29 (Flux2Scheduler) | "Klein Scheduler (4 steps)" | "Klein Scheduler (4 Steps)" | Allowed |
| /nodes/0/title | Node 147 (38f1ecb7-317c-4f39-a118-8a1d0d947593) | "Klein Image" | "Inpaint Image (FLUX.2 Klein)" | Allowed |
| /definitions/subgraphs/0/nodes/30 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 151, "type": "MarkdownNote", "pos": [-1520, -540], "size": [480, 360], "flags": {}, "order": 30, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nReplace or repair a masked region of an image with FLUX.2 Klein.\n\n### How to Use\n\n1. Connect your source to **image** and the area to replace to **mask**.\n2. Describe what should appear there in **Prompt**. Start with the saved **megapixels** and **noise_seed** settings.\n3. Connect **IMAGE** to Preview Image or Save Image in the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 150 | 151 | Allowed |

## Klein Outpaint.json

Result: **PASS** — 15 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `fb8d880883b636d03ac76da3dcde14883fc52d1185a6baca8fbf3a48146e0f6b`

Modified SHA-256: `3eee8f52b610663a120d506c2f76f2b645f6cc2203cdcdf91dc1fbfd3e2f2571`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/groups/0/color | Group 1 | "#3f789e" | "#35414A" | Allowed |
| /definitions/subgraphs/0/groups/1/color | Group 2 | "#3f789e" | "#235B74" | Allowed |
| /definitions/subgraphs/0/groups/2/color | Group 3 | "#3f789e" | "#35414A" | Allowed |
| /definitions/subgraphs/0/groups/2/title | Group 3 | "Sampler" | "Sampling" | Allowed |
| /definitions/subgraphs/0/nodes/12/bgcolor | Node 139 (ImagePadForOutpaintTargetSize) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/12/color | Node 139 (ImagePadForOutpaintTargetSize) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/12/title | Node 139 (ImagePadForOutpaintTargetSize) | (absent; ComfyUI default) | "Outpaint Canvas Size" | Allowed |
| /definitions/subgraphs/0/nodes/13/bgcolor | Node 140 (CLIPTextEncode) | "#353" | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/13/color | Node 140 (CLIPTextEncode) | "#232" | "#235B74" | Allowed |
| /definitions/subgraphs/0/nodes/13/title | Node 140 (CLIPTextEncode) | "CLIP Text Encode (Positive Prompt)" | "Positive Prompt" | Allowed |
| /nodes/0/bgcolor | Node 225 (395926d4-2751-49c5-98ba-9d33596ce365) | "#593930" | "#30343B" | Allowed |
| /nodes/0/color | Node 225 (395926d4-2751-49c5-98ba-9d33596ce365) | "#332922" | "#715B2D" | Allowed |
| /nodes/0/title | Node 225 (395926d4-2751-49c5-98ba-9d33596ce365) | "Klein Outpaint" | "Extend Image (FLUX.2 Klein)" | Allowed |
| /definitions/subgraphs/0/nodes/15 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 232, "type": "MarkdownNote", "pos": [-1600, 1060], "size": [480, 360], "flags": {}, "order": 15, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nExtend an image beyond its original borders with FLUX.2 Klein.\n\n### How to Use\n\n1. Connect the original to **image**. The saved export is bypassed, including its internal nodes. Check those states before using it.\n2. Open the subgraph to set **Outpaint Canvas Size** and describe the extension in **Positive Prompt**.\n3. Connect **IMAGE** to a preview or save node in the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 231 | 232 | Allowed |

## Realistic Post.json

Result: **PASS** — 11 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `927b9dfa4c2819b8f0fe375c6321441d606883999035e0bffc530478e7605288`

Modified SHA-256: `2848d2af92155de7b8d44da5d412c2dc872320908e0105979263731d584c5939`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/3/bgcolor | Node 208 (PrimitiveFloat) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/3/color | Node 208 (PrimitiveFloat) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/3/title | Node 208 (PrimitiveFloat) | (absent; ComfyUI default) | "Brightness" | Allowed |
| /definitions/subgraphs/0/nodes/4/bgcolor | Node 207 (PrimitiveFloat) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/4/color | Node 207 (PrimitiveFloat) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/4/title | Node 207 (PrimitiveFloat) | (absent; ComfyUI default) | "Contrast" | Allowed |
| /nodes/0/bgcolor | Node 154 (4bf6b209-672f-4c7d-86fd-3f415b8ef270) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 154 (4bf6b209-672f-4c7d-86fd-3f415b8ef270) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /nodes/0/title | Node 154 (4bf6b209-672f-4c7d-86fd-3f415b8ef270) | "Post" | "Realistic Image Finishing" | Allowed |
| /definitions/subgraphs/0/nodes/7 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 212, "type": "MarkdownNote", "pos": [2060, 1280], "size": [480, 360], "flags": {}, "order": 16, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nUpscale and finish an image with sharpening, noise, brightness, and contrast.\n\n### How to Use\n\n1. Connect the source to **image**.\n2. Start with the saved settings. Adjust **Noise**, **sharpen_radius**, **brightness**, or **contrast** and compare the results.\n3. Connect **IMAGE** to a preview or save node in the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 211 | 212 | Allowed |

## Seed2VR Image Upscale.json

Result: **PASS** — 11 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `abdb16d14fd70548e709abb8b73b1776a4395d5818692a5300fd1711b2e7809f`

Modified SHA-256: `268c438216741e7718edb1b1bcae322a0a8580ddc6589e4cdf638fbc3e206b19`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/0/bgcolor | Node 18 (Note) | "#653" | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/0/color | Node 18 (Note) | "#432" | "#35414A" | Allowed |
| /definitions/subgraphs/0/nodes/0/title | Node 18 (Note) | (absent; ComfyUI default) | "Alpha Channel Tip" | Allowed |
| /definitions/subgraphs/0/nodes/2/bgcolor | Node 10 (SeedVR2VideoUpscaler) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/2/color | Node 10 (SeedVR2VideoUpscaler) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /definitions/subgraphs/0/nodes/2/title | Node 10 (SeedVR2VideoUpscaler) | (absent; ComfyUI default) | "SeedVR2 Upscale Settings" | Allowed |
| /nodes/0/bgcolor | Node 21 (48dc50d5-1cc2-4c73-953d-effce9784a3d) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 21 (48dc50d5-1cc2-4c73-953d-effce9784a3d) | (absent; ComfyUI default) | "#715B2D" | Allowed |
| /nodes/0/title | Node 21 (48dc50d5-1cc2-4c73-953d-effce9784a3d) | "Seed2VR Image Upscale" | "Upscale Image (SeedVR2)" | Allowed |
| /definitions/subgraphs/0/nodes/5 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 32, "type": "MarkdownNote", "pos": [-300, 300], "size": [480, 360], "flags": {}, "order": 5, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nEnlarge an image with SeedVR2.\n\n### How to Use\n\n1. Connect the original to **image**.\n2. Start with the saved settings. Open **SeedVR2 Upscale Settings** for more controls. See **Alpha Channel Tip** if your source has transparency.\n3. Connect **IMAGE** to a preview or save node in the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 31 | 32 | Allowed |

## Video Metadata.json

Result: **PASS** — 7 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `d3c36eb686efec3f1ef60389404e86db0967baaf1fbcacb13e85c90c92350553`

Modified SHA-256: `a3b2be9cbd9abdf0d457a82f3df954e43cca0190801b05bdc2a2c3c9107dbd35`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/nodes/2/title | Node 4 (ComfyMathExpression) | "Duration (frames / fps)" | "Video Duration (Seconds)" | Allowed |
| /definitions/subgraphs/0/nodes/3/title | Node 5 (StringFormat) | "Video metadata summary" | "Video Details Summary" | Allowed |
| /nodes/0/bgcolor | Node 7 (53281abb-9f87-4d66-a6cc-9e979cf58034) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /nodes/0/color | Node 7 (53281abb-9f87-4d66-a6cc-9e979cf58034) | (absent; ComfyUI default) | "#35414A" | Allowed |
| /nodes/0/title | Node 7 (53281abb-9f87-4d66-a6cc-9e979cf58034) | "Video Metadata" | "Video Details" | Allowed |
| /definitions/subgraphs/0/nodes/4 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 8, "type": "MarkdownNote", "pos": [-240, -100], "size": [480, 360], "flags": {}, "order": 4, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nRead a video’s dimensions, frame rate, frame count, duration, bit depth, and color space.\n\n### How to Use\n\n1. Connect a video to **video**.\n2. Connect **metadata** to a text preview and run the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 7 | 8 | Allowed |

## Z-Image Pass with LoRa.json

Result: **PASS** — 14 changed fields; 0 unauthorized changes.

Original: `Pre-edit working copy at b86dc0a`

Layout allowance: none; all positions, sizes, and group bounds are protected.

Instructional note text allowance: disabled.

Instructional note allowance: one unconnected Quick Start in the primary embedded graph, with its graph-local node counter.

Original SHA-256: `670a2510de34c9ef30453c5c38e57e6a2dc141505236d2ecd7bd1dbc69432751`

Modified SHA-256: `727e12c517bbb090ae67038ea3f910b5010d5beff8ec7a8fe3677d49d6b53d00`

| JSON Pointer | Object | Before | After | Result |
| --- | --- | --- | --- | --- |
| /definitions/subgraphs/0/groups/0/color | Group 2 | "#3f789e" | "#D2B16F" | Allowed |
| /definitions/subgraphs/0/groups/0/title | Group 2 | "Step2 - Image size" | "Step 2 · Image Size" | Allowed |
| /definitions/subgraphs/0/groups/1/color | Group 3 | "#3f789e" | "#235B74" | Allowed |
| /definitions/subgraphs/0/groups/1/title | Group 3 | "Step3 - Prompt" | "Step 3 · Prompt" | Allowed |
| /definitions/subgraphs/0/groups/2/color | Group 4 | "#3f789e" | "#35414A" | Allowed |
| /definitions/subgraphs/0/groups/2/title | Group 4 | "Step1 - Load models" | "Step 1 · Load Models" | Allowed |
| /definitions/subgraphs/0/nodes/11/bgcolor | Node 48 (PreviewAny) | (absent; ComfyUI default) | "#30343B" | Allowed |
| /definitions/subgraphs/0/nodes/11/color | Node 48 (PreviewAny) | (absent; ComfyUI default) | "#594A72" | Allowed |
| /definitions/subgraphs/0/nodes/11/title | Node 48 (PreviewAny) | (absent; ComfyUI default) | "Prompt Preview" | Allowed |
| /nodes/0/bgcolor | Node 146 (06b328ac-34fc-4c9c-b41d-6c6bab4667b5) | "#355" | "#30343B" | Allowed |
| /nodes/0/color | Node 146 (06b328ac-34fc-4c9c-b41d-6c6bab4667b5) | "#233" | "#715B2D" | Allowed |
| /nodes/0/title | Node 146 (06b328ac-34fc-4c9c-b41d-6c6bab4667b5) | "Z-Image Pass with LoRa" | "Z-Image Pass with LoRA" | Allowed |
| /definitions/subgraphs/0/nodes/13 | Authorized instructional note addition | (absent; ComfyUI default) | {"id": 165, "type": "MarkdownNote", "pos": [-620, 420], "size": [480, 360], "flags": {}, "order": 13, "mode": 0, "inputs": [], "outputs": [], "title": "Quick Start", "properties": {}, "widgets_values": ["### What It Does\n\nRefine an input image with Z-Image and a LoRA. Ollama prepares the prompt from the input image.\n\n### How to Use\n\n1. Connect the original to **Image** and start the Ollama service configured inside the subgraph.\n2. Choose **lora_name**. Use **lora_strength** to control the LoRA effect and **denoise_strength** to control how much the image can change.\n3. Connect **IMAGE** to a preview or save node in the parent workflow."], "color": "#35414A", "bgcolor": "#30343B"} | Allowed |
| /definitions/subgraphs/0/state/lastNodeId | Authorized instructional note addition | 164 | 165 | Allowed |
