### Oscar Lin

Undergraduate at Nanjing University of Posts and Telecommunications. I work on LLM serving, benchmarking and request scheduling.

**Upstream fixes in LLM serving stacks**

- Merged: [modelscope/evalscope#2088](https://github.com/modelscope/evalscope/pull/2088), enable `trust_env` only when a proxy or netrc entry applies
- Open: [vllm-project/vllm#67624](https://github.com/vllm-project/vllm/pull/67624) and the same benchmark fix for [sgl-project/sglang#50505](https://github.com/sgl-project/sglang/pull/50505), [NVIDIA/TensorRT-LLM#22283](https://github.com/NVIDIA/TensorRT-LLM/pull/22283), [SemiAnalysisAI/InferenceX#5088](https://github.com/SemiAnalysisAI/InferenceX/pull/5088), [aio-libs/aiohttp#14380](https://github.com/aio-libs/aiohttp/pull/14380)
- Open: vLLM tool-call and reasoning parser fixes, [#67491](https://github.com/vllm-project/vllm/pull/67491), [#67496](https://github.com/vllm-project/vllm/pull/67496), [#67509](https://github.com/vllm-project/vllm/pull/67509)

**Research**

- Y. Guo, Z. Lin, C. Huo, Y. Song. Prediction-Driven Non-Preemptive Scheduling with Bounded Overtaking: A Per-Job Wait Guarantee. Under revision at *Mathematics* (MDPI), 2026. Code, data and Lean 4 proofs: [spjf-guard](https://github.com/oscar030406/spjf-guard), [Zenodo](https://doi.org/10.5281/zenodo.23035899)

**My projects**

- [bench-truth](https://github.com/oscar030406/bench-truth): a streaming server with known timings, to measure how accurate LLM serving benchmarks are
- [parser-conformance](https://github.com/oscar030406/parser-conformance): conformance checks that find bugs in vLLM's tool-call and reasoning parsers, seeded from vLLM's own tests
- [museum-of-attention](https://github.com/oscar030406/museum-of-attention): a walk through the history of attention modules, 2014–2026
