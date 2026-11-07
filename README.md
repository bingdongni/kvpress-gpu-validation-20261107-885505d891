# ChunkPress singleton validation

The [successful GitHub Actions run](https://github.com/bingdongni/kvpress-gpu-validation-20261107-885505d891/actions/runs/42328973448) applied the included patch to NVIDIA/kvpress commit `94951a5b90a2594efbb674c69a9fb9cd28f300c0` and ran 24 tests: 12 CPU and 12 CUDA cases. The [redacted job log](gpu-validation.log) records the result.

The ephemeral self-hosted runner used Windows, an NVIDIA GeForce RTX 4060 Laptop GPU, PyTorch 2.6.0+cu124 and transformers 4.57.6. It is not evidence of other GPU architectures, multi-GPU behavior or performance. Earlier runs stopped during patch preparation and did not run the tests.
