# reproduce_tinyStories

Colab 很强大。

Ref: https://zhuanlan.zhihu.com/p/695130168

## 代码说明

- tokenizer: 使用的是Llama-2-7b-hf
- model: 
    - model_type: llama
    - 可以自定义模型大小
    - hidden_size = 256
    - intermediate_size = 768
    - num_attention_heads=16,
    - num_hidden_layers=4,
    - num_key_value_heads=8
    - 最后模型参数数量：19.5 M