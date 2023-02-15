# TensorRTCMakeModule
A CMake module for TensorRT

This is a CMake Find module for TensorRT

## The following variables will be set:
* `TensorRT_FOUND`        - Set to true if TensorRT can be found
* `TensorRT_INCLUDE_DIRS` - The path to the TensorRT header files for all components
* `TensorRT_LIBRARIES`    - A list of TensorRT library targets for all components
* `TensorRT_EXECUTABLE`   - The full path of trtexec

## Available components:
* `nvinfer` (default)
* `nvinfer_plugin`
* `nvparsers`
* `nvonnxparsers`

