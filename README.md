# C++/CUDA Extensions in PyTorch with SIMD

This is my edit to add SIMD for cpu version for learning purpose.

Please check [here](https://pytorch.org/tutorials/advanced/cpp_custom_ops.html) for the original tutorial.

The examples in this repo work with PyTorch 2.4+.

To build:
```
pip install -e .
```

To test:
```
python test/test_extension.py
```

To benchmark Python vs. C++ vs. CUDA:
```
python test/benchmark.py
```

## Authors

[Peter Goldsborough](https://github.com/goldsborough), [Richard Zou](https://github.com/zou3519)
