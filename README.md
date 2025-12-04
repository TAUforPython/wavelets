# Wavelets for Python

This repo provides a pure Python implementation of Continuous and Discrete Wavelet Transforms. It is engineered for simplicity and seamless integration with the scientific Python ecosystem, including NumPy, SciPy, and Matplotlib. The library is intended for use in signal processing, time-frequency analysis, and data compression applications where wavelet transforms are a fundamental analytical tool.

## Features

*   **Continuous Wavelet Transform (CWT)**: Implementation of the CWT for multi-resolution signal analysis, providing a time-frequency representation of non-stationary signals.
*   **Inverse Continuous Wavelet Transform (ICWT)**: Methodology for signal reconstruction from CWT coefficients.
*   **Discrete Wavelet Transform (DWT)**: Efficient decomposition of signals into approximation and detail coefficients for multi-resolution analysis and data sub-band coding.
*   **Inverse Discrete Wavelet Transform (IDWT)**: Perfect reconstruction of signals from their DWT coefficients.
*   **Implemented Mother Wavelets**: Includes a selection of classical mother wavelets, such as Morlet, Ricker (Mexican Hat), Paul, and Gaussian derivatives.
*   **Scientific Computing Compatibility**: Designed to operate directly on NumPy arrays and integrate smoothly with other scientific libraries.



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
