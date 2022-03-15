# The XRFast Package for Dictionary learning of MA-XRF Images <br>

***

This repository is a companion to the following paper:

**XRFast a New Software Package for Processing of MA-XRF Datasets using Machine Leaning** 
> *Journal where the paper will be pubished*,  <br>

Marc Vermeulen (1), 
Alicia McGeachy (1), 
Bingjie Xu (1), 
Henry Chopp (2),
Aggelos Kataggelos (2), 
Rebecca Meyers (3), 
Matthias Alfeld (4), 
Marc Walton (5)<br>


> 1. Northwestern University / Art Institute of Chicago Center for Scientific Studies in the Arts (NU-ACCESS), 2145 Sheridan Road, Evanston, IL, United States
> 2. Department of ECE, Northwestern University, Evanston, IL, United States
> 3. National Museum of Mexican Art, 1852 W. 19th street, Chicago, IL, United States
> 4. Delft University of Technology, Department of Materials Science and Engineering (MSE), 2628 CN Delft, Netherlands.
> 5. M+ Museum, 38 Museum Drive, West Kowloon Cultural District, Hong Kong*

*corresponding author: marc.walton@mplus.org.hk

**Abstract:** *XRF is a common technique in the field of heritage science. However, data processing and data interpretation remains a challenge because often requires a-priori knowledge of the pigments present in the analyzed objects. For this reason, we developed an open-source unsupervised dictionary learning algorithm reducing the complexity of large datasets containing 10’s of thousands of spectra and identifying patterns. This approach reduces the number of variables and creates correlated elemental maps, characteristic for pigments containing various elements or for pigments mixtures. This alternative approach creates an overcomplete dictionary which is learned which is based on the input data itself, therefore reducing the a-priori user input. In this study, we apply this method to a MA-XRF data set obtained on an 18th century Mexican painting, and positively identified smalt (pigment characterized by the co-occurrence of cobalt, arsenic, bismuth, nickel, and potassium), mixtures of vermilion and lead white, identified two complex conservation materials/interventions, and identified correlated elements that were not identified using the traditional elemental maps approach without image processing. This approach proved very useful as it yields the same conclusions as the traditional elemental maps approach without requiring further image processing or user manipulation to understand elemental correlation. This is therefore a gain of time and a useful resource to understand better the pigments mixtures used in historical paintings.*

***

The aim of this repository is to give full access to a Julia package called XRFast designed for dictionary learning and sparse representation of XRF signals using KSVD. Also included is a Jupyter notebook showing how to use this package, a test dataset, and instructions allowing for the identification of spectral endmembers and their spatial distribution across a 2D work of art.

The intention is that the presented research can be fully replicated and implemented by other scientists in their host institutions. 

Efforts have been made to the best of the authors' abilities to make the data processing procedures accessible and reusable in support of the growing Open Science movement. 


[![Build Status](https://travis-ci.com/NU-ACCESS/XRFast2.jl.svg?branch=master)](https://travis-ci.com/NU-ACCESS/XRFast2.jl)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/NU-ACCESS/XRFast2.jl?svg=true)](https://ci.appveyor.com/project/NU-ACCESS/XRFast2-jl)
[![Codecov](https://codecov.io/gh/NU-ACCESS/XRFast2.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/NU-ACCESS/XRFast2.jl)
[![Coveralls](https://coveralls.io/repos/github/NU-ACCESS/XRFast2.jl/badge.svg?branch=master)](https://coveralls.io/github/NU-ACCESS/XRFast2.jl?branch=master)
