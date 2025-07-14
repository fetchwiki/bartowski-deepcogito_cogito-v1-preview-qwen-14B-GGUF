---
quantized_by: bartowski
pipeline_tag: text-generation
license: apache-2.0
base_model: deepcogito/cogito-v1-preview-qwen-14B
base_model_relation: quantized
---

## Llamacpp imatrix Quantizations of cogito-v1-preview-qwen-14B by deepcogito

Using <a href="https://github.com/ggerganov/llama.cpp/">llama.cpp</a> release <a href="https://github.com/ggerganov/llama.cpp/releases/tag/b5074">b5074</a> for quantization.

Original model: https://huggingface.co/deepcogito/cogito-v1-preview-qwen-14B

All quants made using imatrix option with dataset from [here](https://gist.github.com/bartowski1182/eb213dccb3571f863da82e99418f81e8)

Run them in [LM Studio](https://lmstudio.ai/)

Run them directly with [llama.cpp](https://github.com/ggerganov/llama.cpp), or any other llama.cpp based project

## Prompt format

```
<|im_start|>system
{system_prompt}<|im_end|>
<|im_start|>user
{prompt}<|im_end|>
<|im_start|>assistant
```

## Download a file (not the whole branch) from below:

| Filename | Quant type | File Size | Split | Description |
| -------- | ---------- | --------- | ----- | ----------- |
| [cogito-v1-preview-qwen-14B-bf16.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-bf16.gguf) | bf16 | 29.54GB | false | Full BF16 weights. |
| [cogito-v1-preview-qwen-14B-Q8_0.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q8_0.gguf) | Q8_0 | 15.70GB | false | Extremely high quality, generally unneeded but max available quant. |
| [cogito-v1-preview-qwen-14B-Q6_K_L.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q6_K_L.gguf) | Q6_K_L | 12.50GB | false | Uses Q8_0 for embed and output weights. Very high quality, near perfect, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q6_K.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q6_K.gguf) | Q6_K | 12.12GB | false | Very high quality, near perfect, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q5_K_L.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q5_K_L.gguf) | Q5_K_L | 10.99GB | false | Uses Q8_0 for embed and output weights. High quality, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q5_K_M.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q5_K_M.gguf) | Q5_K_M | 10.51GB | false | High quality, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q5_K_S.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q5_K_S.gguf) | Q5_K_S | 10.26GB | false | High quality, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q4_K_L.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q4_K_L.gguf) | Q4_K_L | 9.56GB | false | Uses Q8_0 for embed and output weights. Good quality, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q4_1.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q4_1.gguf) | Q4_1 | 9.39GB | false | Legacy format, similar performance to Q4_K_S but with improved tokens/watt on Apple silicon. |
| [cogito-v1-preview-qwen-14B-Q4_K_M.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q4_K_M.gguf) | Q4_K_M | 8.99GB | false | Good quality, default size for most use cases, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q3_K_XL.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q3_K_XL.gguf) | Q3_K_XL | 8.60GB | false | Uses Q8_0 for embed and output weights. Lower quality but usable, good for low RAM availability. |
| [cogito-v1-preview-qwen-14B-Q4_K_S.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q4_K_S.gguf) | Q4_K_S | 8.57GB | false | Slightly lower quality with more space savings, *recommended*. |
| [cogito-v1-preview-qwen-14B-IQ4_NL.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ4_NL.gguf) | IQ4_NL | 8.55GB | false | Similar to IQ4_XS, but slightly larger. Offers online repacking for ARM CPU inference. |
| [cogito-v1-preview-qwen-14B-Q4_0.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q4_0.gguf) | Q4_0 | 8.54GB | false | Legacy format, offers online repacking for ARM and AVX CPU inference. |
| [cogito-v1-preview-qwen-14B-IQ4_XS.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ4_XS.gguf) | IQ4_XS | 8.12GB | false | Decent quality, smaller than Q4_K_S with similar performance, *recommended*. |
| [cogito-v1-preview-qwen-14B-Q3_K_L.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q3_K_L.gguf) | Q3_K_L | 7.92GB | false | Lower quality but usable, good for low RAM availability. |
| [cogito-v1-preview-qwen-14B-Q3_K_M.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q3_K_M.gguf) | Q3_K_M | 7.34GB | false | Low quality. |
| [cogito-v1-preview-qwen-14B-IQ3_M.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ3_M.gguf) | IQ3_M | 6.91GB | false | Medium-low quality, new method with decent performance comparable to Q3_K_M. |
| [cogito-v1-preview-qwen-14B-Q3_K_S.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q3_K_S.gguf) | Q3_K_S | 6.66GB | false | Low quality, not recommended. |
| [cogito-v1-preview-qwen-14B-Q2_K_L.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q2_K_L.gguf) | Q2_K_L | 6.53GB | false | Uses Q8_0 for embed and output weights. Very low quality but surprisingly usable. |
| [cogito-v1-preview-qwen-14B-IQ3_XS.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ3_XS.gguf) | IQ3_XS | 6.38GB | false | Lower quality, new method with decent performance, slightly better than Q3_K_S. |
| [cogito-v1-preview-qwen-14B-IQ3_XXS.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ3_XXS.gguf) | IQ3_XXS | 5.94GB | false | Lower quality, new method with decent performance, comparable to Q3 quants. |
| [cogito-v1-preview-qwen-14B-Q2_K.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-Q2_K.gguf) | Q2_K | 5.77GB | false | Very low quality but surprisingly usable. |
| [cogito-v1-preview-qwen-14B-IQ2_M.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ2_M.gguf) | IQ2_M | 5.35GB | false | Relatively low quality, uses SOTA techniques to be surprisingly usable. |
| [cogito-v1-preview-qwen-14B-IQ2_S.gguf](https://huggingface.co/bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF/blob/main/deepcogito_cogito-v1-preview-qwen-14B-IQ2_S.gguf) | IQ2_S | 5.00GB | false | Low quality, uses SOTA techniques to be usable. |

## Embed/output weights

Some of these quants (Q3_K_XL, Q4_K_L etc) are the standard quantization method with the embeddings and output weights quantized to Q8_0 instead of what they would normally default to.

## Downloading using huggingface-cli

<details>
  <summary>Click to view download instructions</summary>

First, make sure you have hugginface-cli installed:

```
pip install -U "huggingface_hub[cli]"
```

Then, you can target the specific file you want:

```
huggingface-cli download bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF --include "deepcogito_cogito-v1-preview-qwen-14B-Q4_K_M.gguf" --local-dir ./
```

If the model is bigger than 50GB, it will have been split into multiple files. In order to download them all to a local folder, run:

```
huggingface-cli download bartowski/deepcogito_cogito-v1-preview-qwen-14B-GGUF --include "deepcogito_cogito-v1-preview-qwen-14B-Q8_0/*" --local-dir ./
```

You can either specify a new local-dir (deepcogito_cogito-v1-preview-qwen-14B-Q8_0) or download them all in place (./)

</details>

## ARM/AVX information

Previously, you would download Q4_0_4_4/4_8/8_8, and these would have their weights interleaved in memory in order to improve performance on ARM and AVX machines by loading up more data in one pass.

Now, however, there is something called "online repacking" for weights. details in [this PR](https://github.com/ggerganov/llama.cpp/pull/9921). If you use Q4_0 and your hardware would benefit from repacking weights, it will do it automatically on the fly.

As of llama.cpp build [b4282](https://github.com/ggerganov/llama.cpp/releases/tag/b4282) you will not be able to run the Q4_0_X_X files and will instead need to use Q4_0.

Additionally, if you want to get slightly better quality for , you can use IQ4_NL thanks to [this PR](https://github.com/ggerganov/llama.cpp/pull/10541) which will also repack the weights for ARM, though only the 4_4 for now. The loading time may be slower but it will result in an overall speed incrase.

<details>
  <summary>Click to view Q4_0_X_X information (deprecated</summary>

I'm keeping this section to show the potential theoretical uplift in performance from using the Q4_0 with online repacking.

<details>
  <summary>Click to view benchmarks on an AVX2 system (EPYC7702)</summary>

| model                          |       size |     params | backend    | threads |          test |                  t/s |  % (vs Q4_0)  |
| ------------------------------ | ---------: | ---------: | ---------- | ------: | ------------: | -------------------: |-------------: |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |         pp512 |        204.03 ± 1.03 |          100% |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |        pp1024 |        282.92 ± 0.19 |          100% |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |        pp2048 |        259.49 ± 0.44 |          100% |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |         tg128 |         39.12 ± 0.27 |          100% |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |         tg256 |         39.31 ± 0.69 |          100% |
| qwen2 3B Q4_0                  |   1.70 GiB |     3.09 B | CPU        |      64 |         tg512 |         40.52 ± 0.03 |          100% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |         pp512 |        301.02 ± 1.74 |          147% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |        pp1024 |        287.23 ± 0.20 |          101% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |        pp2048 |        262.77 ± 1.81 |          101% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |         tg128 |         18.80 ± 0.99 |           48% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |         tg256 |         24.46 ± 3.04 |           83% |
| qwen2 3B Q4_K_M                |   1.79 GiB |     3.09 B | CPU        |      64 |         tg512 |         36.32 ± 3.59 |           90% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |         pp512 |        271.71 ± 3.53 |          133% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |        pp1024 |       279.86 ± 45.63 |          100% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |        pp2048 |        320.77 ± 5.00 |          124% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |         tg128 |         43.51 ± 0.05 |          111% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |         tg256 |         43.35 ± 0.09 |          110% |
| qwen2 3B Q4_0_8_8              |   1.69 GiB |     3.09 B | CPU        |      64 |         tg512 |         42.60 ± 0.31 |          105% |

Q4_0_8_8 offers a nice bump to prompt processing and a small bump to text generation

</details>

</details>

## Which file should I choose?

<details>
  <summary>Click here for details</summary>

A great write up with charts showing various performances is provided by Artefact2 [here](https://gist.github.com/Artefact2/b5f810600771265fc1e39442288e8ec9)

The first thing to figure out is how big a model you can run. To do this, you'll need to figure out how much RAM and/or VRAM you have.

If you want your model running as FAST as possible, you'll want to fit the whole thing on your GPU's VRAM. Aim for a quant with a file size 1-2GB smaller than your GPU's total VRAM.

If you want the absolute maximum quality, add both your system RAM and your GPU's VRAM together, then similarly grab a quant with a file size 1-2GB Smaller than that total.

Next, you'll need to decide if you want to use an 'I-quant' or a 'K-quant'.

If you don't want to think too much, grab one of the K-quants. These are in format 'QX_K_X', like Q5_K_M.

If you want to get more into the weeds, you can check out this extremely useful feature chart:

[llama.cpp feature matrix](https://github.com/ggerganov/llama.cpp/wiki/Feature-matrix)

But basically, if you're aiming for below Q4, and you're running cuBLAS (Nvidia) or rocBLAS (AMD), you should look towards the I-quants. These are in format IQX_X, like IQ3_M. These are newer and offer better performance for their size.

These I-quants can also be used on CPU, but will be slower than their K-quant equivalent, so speed vs performance is a tradeoff you'll have to decide.

</details>

## Credits

Thank you kalomaze and Dampf for assistance in creating the imatrix calibration dataset.

Thank you ZeroWw for the inspiration to experiment with embed/output.

Thank you to LM Studio for sponsoring my work.

Want to support my work? Visit my ko-fi page here: https://ko-fi.com/bartowski
