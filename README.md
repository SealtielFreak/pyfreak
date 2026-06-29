# pyfreak

[![License: LGPL v3](https://img.shields.io/badge/License-LGPL_v3-blue.svg?style=flat-square)](https://www.gnu.org/licenses/lgpl-3.0)

![PyPI - Version](https://img.shields.io/pypi/v/pyfreak?style=flat-square)
![PyPI - Implementation](https://img.shields.io/pypi/implementation/pyfreak?style=flat-square)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pyfreak?style=flat-square)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/pyfreak?style=flat-square)
![GitHub Release Date](https://img.shields.io/github/release-date/sealtielfreak/pyfreak.svg?style=flat-square)
![PyPI - Downloads](https://img.shields.io/pypi/dm/pyfreak?style=flat-square)

*Parallel Yielding Functional Regularized Element-wise Array Kernels* (or *pyfreak*) is a high-performance, low-level compilation toolkit designed to inject algebraic abstractions—such as Monads, Functors, and Applicatives—directly into vectorized pipelines. 

Rather than replacing general-purpose functional libraries like [toolz](https://github.com/pytoolz/toolz), acts as a specialized complement. It bridges the gap between pure declarative programming and bare-metal performance, enabling the seamless composition of lazy, immutable functional workflows inside highly-parallel computational kernels compiled via [numba](https://github.com/numba/numba) and [numpy](https://github.com/numpy/numpy).