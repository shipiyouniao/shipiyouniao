# 石皮幼鸟 · shipiyouniao

I'm a full-stack engineer at Sangfor in Shenzhen and one of the maintainers of [KVCached](https://github.com/ovg-project/kvcached). I work on how inference servers share GPU memory, especially when several models run on the same card. I also contribute to vLLM and SGLang.

[Personal website](https://shipiyouniao.github.io/) · [PR notes](https://shipiyouniao.github.io/#/notes) · [Bilibili](https://space.bilibili.com/30915729) · [Email](mailto:2960474346@qq.com)

## Notes from inference work

- A multimodal model went from about 2.9 GiB to 14 GiB during startup with the same image. I traced the extra memory to a missing PyTorch decorator. [KVCached #461](https://github.com/ovg-project/kvcached/pull/461)
- Freeing one cache block used to sort candidates across the whole pool. Tracking which pages changed cut a single trim from about 260 to 20 microseconds on a T4 with 1,000 cached blocks. [KVCached #538](https://github.com/ovg-project/kvcached/pull/538)
- A Python worker held on to the previous request while unpacking the next one. Moving each call into its own function let the old arguments go first. [vLLM #51979](https://github.com/vllm-project/vllm/pull/51979)

## Games and other projects

I like writing C# and making games in Unity and for the browser.

- **Minefarer** is a Minesweeper adventure with a map, puzzles, and a story. [Play in your browser](https://shipiyouniao.github.io/minefarer/) · [Source](https://github.com/shipiyouniao/minefarer)
- **UnityEasyInject** is a small dependency-injection library for Unity. [Source](https://github.com/shipiyouniao/UnityEasyInject)
- **NNRP** is a runtime protocol I work on at NagareWorks. [Rust](https://github.com/NagareWorks/nnrp-rs) · [Python](https://github.com/NagareWorks/nnrp-py) · [C#](https://github.com/NagareWorks/nnrp-cs)
