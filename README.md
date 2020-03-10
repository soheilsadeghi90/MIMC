# MIMC: Modal Identification using Matrix Completion

This repo contains a brief tutorial of the MIMC algorithm for bridge system identification using mobile sensing network.

To run the notebook, make sure that the dependencies are installed. The most important ones:
  - Tensorflow
  - Scipy

## Organization

The first part of the notebook contains the algorithm used for matrix completion using sparse observations. 

The second part performs the structured optimization to extract modal properties. 

For more information, please refer to this published paper:

https://ascelibrary.org/doi/full/10.1061/%28ASCE%29EM.1943-7889.0001733

## Files

Notebook.ipynb: this is the notebook that you use for testing the algorithm. It's quite self-explanatory. 

Accel_42.txt: a sample input file containing a bridge respose at 5,000 DOFs in 5,000 time samples (5K x 5K matrix). Feel free to replace it with your files.

utilities: contains utility functions needed to run the notebook. Algorithms are implemented here. You may find the implementation details from the papers below. 

## References

[1] Sadeghi Eshkevari, S., Pakzad, S. N., Takáč, M., & Matarazzo, T. J. (2020). Modal identification of bridges using mobile sensors with sparse vibration data. Journal of Engineering Mechanics, 146(4), 04020011.

[2] Eshkevari, S. S., & Pakzad, S. N. (2020). Signal reconstruction from mobile sensors network using matrix completion approach. In Topics in Modal Analysis & Testing, Volume 8 (pp. 61-75). Springer, Cham.

[3] ESHKEVARI, S. S., TAKÁC, M., PAKZAD, S. N., & ESHKEVARI, S. S. (2019). High Resolution Bridge Mode Shape Identification via Matrix Completion Approach. Structural Health Monitoring 2019.
