---
layout: default
title: ADNI@CMIC
nav_order: 2
parent: Data
has_children: false
permalink: docs/data/adni@cmic
has_toc: false
---

# ADNI@CMIC

This page contains information on the curated version of the [ADNI](https://adni.loni.usc.edu) dataset stored at UCL [CMIC](https://www.ucl.ac.uk/cmic).

Please address all queries/requests/contributions to the current ADNI@CMIC Gatekeeper: [Neil Oxtoby](https://github.com/noxtoby)

See [below](#how-to-access-adnicmic) for how to access ADNI@CMIC.

<hr />

## Available data

The ADNI@CMIC repository currently includes CSV files of clinical data and the following imaging modalities:

| Modality    | Derivatives                      | Download date  | BIDS App used | Contact |
| ----------- | -------------------------------- | -------------- | ------------- | ------- |
| T1w MRI     | FreeSurfer 7.1.1 cross-sectional | September 2022 | [E-DADS FreeSurfer](https://e-dads.github.io/tools) | Neil Oxtoby |


<!-- | PiB PET     | AmyPET SUVr and CL            | October 2022  | |
| AV45 PET    | AmyPET SUVr and CL            | October 2022  | |
| AV1451 PET  | AmyPET SUVr and CL            | October 2022  | |
| FDG PET     | NiftyPET SUVr and CL          | October 2022  | | -->



Notes:
- T1w MRI: We downloaded `IMAGEUID` from ADNIMERGE.csv, which have already undergone QC by ADNI. (If you need/want the raw T1 MRI, discuss it with the ADNI@CMIC gatekeeper.)

<hr />

## How to access ADNI@CMIC

You must first have approval from ADNI to access the data.

1. Register and apply to ADNI: [https://adni.loni.usc.edu/data-samples/access-data/#access_data](https://adni.loni.usc.edu/data-samples/access-data/#access_data)
2. Send an email to the [ADNI@CMIC Gatekeeper](#adnicmic) (see above) including the following information:
  - evidence of your current permission to access ADNI data, e.g.:
    - your confirmation email from LONI/ADNI if recently approved;
    - a current screenshot of your "My Account" section of the LONI IDA website, showing that you are up to date and have access.
  - your CS cluster username

The [ADNI@CMIC Gatekeeper](#adnicmic) will then arrange for you to be added to the `adni` linux permissions group on the CS cluster.

## Background

In September 2022, Neil Oxtoby (of [UCL POND](http://pond.cs.ucl.ac.uk)) started curating a local ADNI repository, approximately following the Brain Imaging Data Structure ([BIDS](https://bids.neuroimaging.io)) specification.

The original goals were to reduce wasted/duplicated compute time and storage, and to improve efficiency and reproducibility of ADNI-based research at CMIC.



