---
title: "MSMC-TTS: Multi-Stage Multi-Codebook VQ-VAE Based Neural TTS"
authors:
- Haohan Guo
- Fenglong Xie
- Xixin Wu
- Frank K Soong
- Helen Meng

date: "2023-05-02T00:00:00Z"
doi: "10.1109/TASLP.2023.3272470"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE TASLP"
publication_short: ""

abstract: This article aims to improve neural TTS with vector-quantized, compact speech representations. We propose a Vector-Quantized Variational AutoEncoder (VQ-VAE) based feature analyzer to encode acoustic features into sequences with different time resolutions, and quantize them with multiple VQ codebooks to form the Multi-Stage Multi-Codebook Representation (MSMCR). The TTS system, MSMC-TTS, is proposed to predict better speech via this representation. In prediction, the multi-stage predictor is trained to map the input text sequence to MSMCRs in stages, by minimizing Euclidean distance and “triplet loss”. In synthesis, the neural vocoder converts ground-truth or predicted MSMCRs into speech waveforms. The proposed system is trained with single-speaker TTS datasets and tested in various scenarios for comprehensive evaluation. In TTS evaluation, MSMC-TTS obtains MOS of 4.34 and 4.10 on English and Chinese datasets, which significantly outperforms VITS with scores of 3.78 and 3.90. Meanwhile, compared with Mel-Spectrograms, the domain discrepancy between prediction and ground truth is lower in MSMCRs with the higher Domain-classification Error Rate (DER). Furthermore, this system shows lower modeling complexity and data size requirements, preserving excellent performance even with fewer model parameters or training data. The noticeable improvement in analysis-synthesis and TTS from multiple codebooks and stages also validate them as vital components in seeking a more profitable speech representation and building high-performance neural TTS.

# Summary. An optional shortened abstract.
summary: This article aims to improve neural TTS with vector-quantized, compact speech representations. We propose a Vector-Quantized Variational AutoEncoder (VQ-VAE) based feature analyzer to encode acoustic features into sequences with different time resolutions, and quantize them with multiple VQ codebooks to form the Multi-Stage Multi-Codebook Representation (MSMCR). The TTS system, MSMC-TTS, is proposed to predict better speech via this representation. In prediction, the multi-stage predictor is trained to map the input text sequence to MSMCRs in stages, by minimizing Euclidean distance and “triplet loss”. In synthesis, the neural vocoder converts ground-truth or predicted MSMCRs into speech waveforms. The proposed system is trained with single-speaker TTS datasets and tested in various scenarios for comprehensive evaluation. In TTS evaluation, MSMC-TTS obtains MOS of 4.34 and 4.10 on English and Chinese datasets, which significantly outperforms VITS with scores of 3.78 and 3.90. Meanwhile, compared with Mel-Spectrograms, the domain discrepancy between prediction and ground truth is lower in MSMCRs with the higher Domain-classification Error Rate (DER). Furthermore, this system shows lower modeling complexity and data size requirements, preserving excellent performance even with fewer model parameters or training data. The noticeable improvement in analysis-synthesis and TTS from multiple codebooks and stages also validate them as vital components in seeking a more profitable speech representation and building high-performance neural TTS.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10114504
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
