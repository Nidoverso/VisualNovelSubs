# VisualNovelSubs (VNS)

VisualNovelSubs (VNS) is a Python module designed to perform OCR using Tesseract on video gameplay from visual novels, with the goal of extracting text and generating frame-accurate subtitles. This module provides all the necessary functions to simplify and streamline this process.

## Key Features

- Text extraction from visual novel videos.
- Generation of subtitles synchronized with the video on a per-frame basis.
- Facilitates the development of applications for visual novel processing.

## Applications

VisualNovelSubs serves as a common component in two main applications:

1. **[VNS OCR](https://github.com/nidoverso/vns-ocr)**: This application focuses on performing OCR on visual novel videos. It utilizes the VNS module to extract text and generate subtitles.

2. **[VNS Editor](https://github.com/nidoverso/vns-editor)**: VNS Editor is responsible for editing and refining the results produced by VNS OCR to achieve greater accuracy in subtitles. It also relies on the VNS module.

## Usage and Customization

While two specific applications are provided, VisualNovelSubs is versatile enough for you to develop your own customized applications while maintaining the same structure and compatibility. This allows you to tailor VNS to your specific needs.

## License

VisualNovelSubs (VNS) and its associated applications are distributed under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html). This ensures that the source code is available, and you can modify it to suit your needs while adhering to the terms of the license.