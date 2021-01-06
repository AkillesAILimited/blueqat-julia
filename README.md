# blueqat-julia

[![Build Status](https://travis-ci.com/ryuNagai/blueqat.jl.svg?branch=master)](https://travis-ci.com/ryuNagai/blueqat.jl)
[![Coverage](https://codecov.io/gh/ryuNagai/blueqat.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/ryuNagai/blueqat.jl)
[![Coverage](https://coveralls.io/repos/github/ryuNagai/blueqat.jl/badge.svg?branch=master)](https://coveralls.io/github/ryuNagai/blueqat.jl?branch=master)

Quantum computing simulator with Julia.

Codes written in Julia is intuitive, easily be fast than Python, and possibly as fast as C++.

It provides fast and user-friendly StateVectorBackend.

For simulation of intermediate-scale quantum computer,
- graph based method(UndirectedGraphBackend) 
and 
- tensor network based methods(on development)
are integrated and easily swithable.

For code example, please refer to
blueqat-julia/src/Example_for_use.ipynb