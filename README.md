# Awesome Forensic Fingerprint Matching

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome tools and literature for forensic fingerprint matching.

## Open source software

### Fingerprint quality evaluation


- **[NIST's fingerprint image quality algorithm (NFIQ).](https://www.nist.gov/publications/fingerprint-image-qualitiy)** Part of the NIST open source Biometric Image Software (see below).
    - See [NFIQ2](https://github.com/usnistgov/NFIQ2) in particular.

### Minutiae-based matching algorithms

- [**FingerJetFXOSE** minutiae extraction algorithm](https://github.com/FingerJetFXOSE/FingerJetFXOSE)

- :star: **[NIST's open source Biometric Image Software.](https://www.nist.gov/services-resources/software/nist-biometric-image-software-nbis)** Complete suite of tools for minutiae-based fingerprint matching developped for the FBI and DHS. Contains:
    - A "[fingerprint image quality algorithm](https://www.nist.gov/publications/fingerprint-image-qualitiy), NFIQ, which analyses a fingerprint image and assigns a quality value of 1 (highest quality) 5(lowest quality) to the image."
    - A fingerprint pattern classification system, PCASYS.
    - A minutiae detector called, MINDTCT.
    - A fingerprint matching algorithm, BOZORTH3.
    - More, such as fingerprint detection and segmentation algorithms, and image manipulation utilities.

- :star: **[LatentAFIS.](https://github.com/prip-lab/MSU-LatentAFIS)** Latent fingerprint identification and matching. Developped at MSU and supported by a series of paper. Provides a gui as well as command line tools.

- **[SourceAFIS.](https://sourceafis.machinezoo.com/)** Open source fingerprint software (Java and .NET) with an explanation of their algorithm [here](https://sourceafis.machinezoo.com/algorithm).

- **[OpenAFIS.](https://github.com/neilharan/openafis)** High performance C++ fingerprint matching library. Note: does not extract minutiae.

## Publicly available software (closed source)

- **[FRStat](http://www.forensicxpert.com/frstat/)** software to statistically assess "the significance of an association between two friction ridge skin impressions." Paper is available [here](https://www.sciencedirect.com/science/article/abs/pii/S0379073818301403).

## Literature

- **[Maltoni et al. (2003) Handbook of Fingerprint Recognition](https://books.google.com/books?hl=fr&lr=&id=1Wpx25D8qOwC&oi=fnd&pg=PR11&dq=Handbook+of+fingerprint+recognition&ots=9zM11Upr67&sig=UpwRZCM9EFWTBC_rfvkSIhJPGCA#v=onepage&q=Handbook%20of%20fingerprint%20recognition&f=false):** thorough treatment of minutiae-based methods with additional topics such as synthetic fingerprint generation.

- **[PhD thesis "Fingerprint Recognition for Forensic Applications".](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiu3JiAzLrwAhWLGFkFHXzTDyEQFjABegQIAxAD&url=https%3A%2F%2Frepositorio.uam.es%2Fbitstream%2Fhandle%2F10486%2F667596%2Fkrishnamoorthy_ram_prasad.pdf%3Fsequence%3D1&usg=AOvVaw2uTAW9HZQQLWMolvry98_t)** Develops an evidence evaluation framework based on probabilistic matching (i.e. using likelihood ratios).

- **[Wavelet transforms for fingerprint matching](https://aip.scitation.org/doi/pdf/10.1063/1.3526205):** Automatic fingerprint identification system based on Level 3 features.

