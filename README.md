# Awesome Forensic Fingerprint Matching

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome tools and literature for forensic fingerprint matching.

## Open source software

### Fingerprint quality evaluation

- **[NIST's fingerprint image quality algorithm (NFIQ).](https://www.nist.gov/publications/fingerprint-image-qualitiy)** Part of the NIST open source Biometric Image Software (see below).

### Minutiae-based matching algorithms

- :star: **[NIST's open source Biometric Image Software.](https://www.nist.gov/services-resources/software/nist-biometric-image-software-nbis)** Complete suite of tools for minutiae-based fingerprint matching developped for the FBI and DHS. Contains:
    - A "[fingerprint image quality algorithm](https://www.nist.gov/publications/fingerprint-image-qualitiy), NFIQ, which analyses a fingerprint image and assigns a quality value of 1 (highest quality) 5(lowest quality) to the image."
    - A fingerprint pattern classification system, PCASYS.
    - A minutiae detector called, MINDTCT.
    - A fingerprint matching algorithm, BOZORTH3.
    - More, such as fingerprint detection and segmentation algorithms, and image manipulation utilities.

- :star: **[LatentAFIS.](https://github.com/prip-lab/MSU-LatentAFIS)** Latent fingerprint identification and matching. Developped at MSU and supported by a series of paper. Provides a gui as well as command line tools.

- **[SourceAFIS.](https://sourceafis.machinezoo.com/)** Open source fingerprint software (Java and .NET) with an explanation of their algorithm [here](https://sourceafis.machinezoo.com/algorithm).

- **[OpenAFIS.](https://github.com/neilharan/openafis)** High performance C++ fingerprint matching library. Note: does not extract minutiae.

## Literature

