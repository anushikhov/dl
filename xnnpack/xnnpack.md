# XNNPACK  

XNNPACK is a highly optimized library for floating-point neural network inference operators for ARM, WebAssembly, and x86 platforms.  

It provides low-level performance primitives for accelerating high-level machine learning frameworks.  

github.com/google/XNNPACK  

All operators in XNNPACK support NHWC layout, but additionally allow custom stride along the Channel dimension.  

Operators can consume a subset of channels in the input tensor, and produce a subset of channels in the output tensor, providing a zero-cost Channel Split and Channel Concatenation operations.  

XNNPACK is based on QNNPACK library. Over time its codebase diverged a lot and XNNPACK API is no longer compatible with QNNPACK.
