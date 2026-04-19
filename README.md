# Extended Save Image for ComfyUI

A community-maintained archive/fork of **Extended Save Image for ComfyUI**, originally created by **palant**.

I really like this node because it stays simple and focused: it does not add many complicated options, and only provides a straightforward way to choose the image format when saving. That simplicity is why I wanted to preserve a copy.

The original repository was previously available at:

```text
https://github.com/palant/extended-saveimage-comfyui
```

The original repository has been archived by its owner and is now read-only, so this fork is preserved here for continued use by the ComfyUI community.

## What this node does

This custom node is largely identical to ComfyUI's default Save Image node, but adds support for saving images as:

- PNG
- JPEG
- WEBP lossless
- WEBP lossy

Metadata is embedded in the images as usual, and the resulting images can be used to load a workflow.

## Changes in this fork

Compared with the original version, this fork includes:

- Support for replacing date placeholders in `filename_prefix`, including:
  - `%Y-%m-%d`
  - `%date%`
  - `%date:yyyy-MM-dd%`

## Installation

Clone this repository into your `ComfyUI/custom_nodes` folder:

```bash
git clone https://github.com/lilyao313/extended-saveimage-comfyui
```

Then restart ComfyUI.

## Attribution

Original project by **palant**.

This repository is a preserved and modified fork maintained by **lilyao313**.

## License

This project is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE).

This fork preserves the original GPLv3 license and marks modifications made after the original release.
