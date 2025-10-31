---
title: Upload
layout: default
has_toc: false
nav_order: 6
---


# Upload result files to CROSSHub

## Prepare the data

The first step in submitting data is preparing your data files. The platform accepts two types of [data files](/instructions-data/docs/upload/files): CSV and Excel (in a fixed format). We also require a standard naming convention for [variable names](/instructions-data/docs/variables).


## Upload the data

Once you have prepared the data, follow these steps:

1. Go to the [upload page](https://app.sweetcross.link/dashboard) 
2. Sign in with your model credentials
3. Upload **one single** Excel or CSV file

{: .warning }
The platform validates the file. It checks column names, variable names, units, etc. If any specifications are not met, the submission will fail and an error will be returned

## Problems uploading data

If you encounter issues when uploading data, please send an email to [sweet-cross](mailto:sweet.cross.ch[at]gmail.com?subject=technicalproblem) including:
- The file you tried to upload
- A description of the error

## Automatic submission with the CROSS Client
[`crossclient`](https://sweet-cross.github.io/crossclient) is Python package developed to directly interact with the CROSS platform. 
It allows for the automatic submission of result files using python and without any manual upload. A more detailed 
description of the process and example code is proveded in the [documentation](https://sweet-cross.github.io/crossclient/api/#result-submission).


