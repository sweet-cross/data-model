---
title: Upload
layout: default
has_toc: false
nav_order: 7
---


# Upload result files to CROSSHub

## Prepare the data

The first step in submitting data is preparing your data. The platform has to ways of uploading data: using a file or directly using the python client. The data should include all the compulsory [fields](/instructions-data/docs/fields)  and the standard naming convention for [variable names](/instructions-data/docs/variables).


## Upload the data using a CSV or Excel file

Once you have prepared the data, follow these steps:

1. Go to the [upload page](https://app.sweetcross.link/dashboard) 
2. Sign in with your model credentials
3. Upload **one single** Excel or CSV file following the [template](/instructions-data/docs/upload/files)

{: .warning }
The platform validates the file. It checks column names, variable names, units, etc. If any specifications are not met, the submission will fail and an error will be returned

## Automatic submission with the CROSS Client

{: .warning } This is in experimental stage and subject to changes

[`crossclient`](https://sweet-cross.github.io/crossclient) is Python package developed to directly interact with the CROSS platform. 
It allows for the automatic submission of result files using python and without any manual upload. A more detailed 
description of the process and example code is proveded in the [documentation](https://sweet-cross.github.io/crossclient/api/#result-submission). The current version allows for automatic upload. In future releases we add the possibility to validate files locally, i.e., before the upload of the results.


