This repository contains an antenna performance dataset with 157 rows and 270 columns, where each column represents one antenna design sample.

For every antenna sample:

Rows 1–52: S11 (return loss) values in linear scale, corresponding to frequencies from 2 GHz to 7 GHz.

Rows 53–103: Gain values (in dB).

Rows 104–153: Radiation pattern data points (Provided only for E Plane wrt both the bands). The H Plane data will be provided on request. 

Rows 154–157: Antenna geometry variables used for the design.

In this dataset, the S11, gain, and radiation pattern data serve as the inputs to the proposed model, while the antenna geometry parameters form the output.

The dataset is intended for machine learning–based antenna analysis, performance prediction, and inverse design studies. The implementation details of the model, along with the dataset preparation steps, are described in the associated research paper.

At present, a sample dataset of size 110x157 is provided for public access, considering that generating such datasets requires significant computational resources and time. The complete dataset and code will be provided upon request.
