# US-Fascicle-Imaging
George Ivanov, KCL NMES Computer Science

The project provides a latency evaluation of the models and analysis proved by:
https://github.com/njcronin/DL_Track/blob/master/README.md
Source code and COLAB notebook are taken and accredited to the owner https://github.com/njcronin

Latency Evaluation of existing SOTA model for B-mode ultrasound analysis of muscle fascicles

Extract SOTA models from https://github.com/njcronin/DL_Track/tree/master/models ensuring that gitLFS is installed.
Convert SOTA models to ONNX models via https://github.com/george-sho-ivanov/US-Fascicle-Imaging/blob/main/tf_to_onnx_conversion.ipynb
Perform latency analysis via https://github.com/george-sho-ivanov/US-Fascicle-Imaging/blob/main/OnnxSingleInference.ipynb
Record latency results

Options to experiment with Optimized models, quantized models, and profiling are documented in the OnnxSingleInference source code.
