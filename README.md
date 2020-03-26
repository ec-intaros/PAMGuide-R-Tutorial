# PAMGuide-R-Tutorial
Tool for analysis of passive acoustic data.

## Introduction
This tool is a slightly modified version of PAMGuide for R, originally created by Nathan Merchant [1]. The primary modifications that have been made are 1) adding support for vector input, and 2) adding support for Jupyter notebook. The original version of PAMGuide only supports WAV-files (audio files) as input. However, passive acoustic data are often stored in NetCDF or other data files (e.g. MATLAB files). Converting this data into audio files increases processing time and can also lead to loss of data.

A Jupyter notebook is included here to illustrate how to use the tool. It also shows how to access data available on a Thredds server without downloading the data manually.

## Installation

The processing tool requires the following software to run:
- R (Available at: https://www.r-project.org )
- PAMGuide (Available at: https://sourceforge.net/projects/pamguide/)
- Jupyter notebook ( https://jupyter.org )
- Sample data (WIFAR data available here: https://archive.norstore.no/pages/public/datasetDetail.jsf?id=10.11582/2017.00012 )

Download the files in this repository and add them to the PAMGuide folder. The whole content of this repository can be downloaded using `git clone https://github.com/ec-intaros/PAMGuide-R-Tutorial`

The Jupyter notebook uses example data from the WIFAR project [2], which must be downloaded from the link above and placed in the main folder.


## Usage
Start the Jupyter notebook by typing `jupyter notebook` in a terminal, and open the notebook. The notebook contains a step by step walkthrough, illustrating how the tool is used, and also how to read in data from a Thredds server.

A detailed instruction in the use of PAMGuide, as well as an overview of the capabilities of the software, is given in the instruction manual, which is available [here](
https://besjournals.onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1111%2F2041-210X.12330&file=mee312330-sup-0001-AppendixS1.pdf)

## References
[1] Merchant, N.D., Fristrup, K.M., Johnson, M.P., Tyack, P.L., Witt, M.J., Blondel, P. and Parks, S.E. (2015), *Measuring acoustic habitats*. Methods Ecol Evol, **6**: 257-265. doi:[10.1111/2041-210X.12330](https://doi.org/10.1111/2041-210X.12330)

[2] Waves-in-Ice Forecasting for Arctic Operators, https://www.nersc.no/project/wifar

## Authors
Espen Storheim (NERSC)

## Licenses

## Acknowledgements
This work has been funded by the H2020 project *Integrated Arctic Observation System* (INTAROS). www.intaros.eu


