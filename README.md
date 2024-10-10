# llm

1. [检查 Tokenizer 词表大小与 LLM 的 Embedding 和 LM_head 输入大小是否匹配](https://github.com/KnowAIHub/llm/blob/main/embedding/check_embedding.ipynb)
2. [对 SBert 进行训练、预测、评估使其进行相似度计算](https://github.com/KnowAIHub/llm/tree/main/huggingface/Sentence-BERT-Similarity)
3. [对 BERT 进行训练、预测、评估使其进行文本分类](https://github.com/KnowAIHub/llm/tree/main/huggingface/bert-text-classification)
4. [使用 CLIP 模型进行文本图像匹配](https://github.com/KnowAIHub/llm/tree/main/huggingface/clip-text-image-matching)
5. [对 JoinBERT 进行训练、预测使其进行对话意图和槽位联合识别](https://github.com/KnowAIHub/llm/tree/main/huggingface/intent-reg)
6. [对比LoRA微调、模型Last Layers微调以及模型全参数微调对比，并且使用网格搜索 LoRA 最佳参数设置](https://github.com/KnowAIHub/llm/tree/main/huggingface/lora-comparison)
7. [对 Qwen2-0.5B 模型进行 LoRA 微调](https://github.com/KnowAIHub/llm/tree/main/huggingface/peft-lora)
8. [对 RoBERTa 进行训练、预测使其进行中文/英文文本分类](https://github.com/KnowAIHub/llm/tree/main/huggingface/roberta-text-classification)
9. [利用 SBert 进行Embedding、文本相似度计算、语义检索、检索ReRank、图像检索等](https://github.com/KnowAIHub/llm/tree/main/huggingface/sbert)
10. [简单的文本分类实现](https://github.com/KnowAIHub/llm/tree/main/huggingface/text-classification)
11. [LLM 不同精度（FP16，FP32，BF16）下显存占用、精度转换](https://github.com/KnowAIHub/llm/tree/main/memory_precision)
12. [使用 Sentencepiece 进行LLM词表的扩展与中文化](https://github.com/KnowAIHub/llm/tree/main/sentencepiece)
13. [扩展LLM词表后对 Embedding 以及 LM_head 进行随机初始化](https://github.com/KnowAIHub/llm/blob/main/embedding/code.ipynb)
14. [Qwen2 的 LoRA、QLoRA、全参数微调以及 FastAPI 部署](https://github.com/KnowAIHub/llm/tree/main/sft)
15. [Proxy Tuning 微调](https://github.com/KnowAIHub/llm/blob/main/sft/proxy_tuning.ipynb)
16. [Gemma2、Jamba 的 LoRA 微调](https://github.com/KnowAIHub/llm/tree/main/sft)
17. [向 Tokenizer 中添加新的 Tokens / Special Tokens 并且初始化Embedding矩阵](https://github.com/KnowAIHub/llm/blob/main/sft/add_tokens.ipynb)
18. [对多个 LoRA 权重进行卸载和切换使用](https://github.com/KnowAIHub/llm/blob/main/sft/PEFT_Multi_LoRA_Inference.ipynb)
19. [对新添加 Tokens 进行 Embedding 训练 (`区别于13和17`)](https://github.com/KnowAIHub/llm/tree/main/sft/special_token-sft)
20. [在 VGG19 图像分类任务中应用 LoRA 方法进行微调测试](https://github.com/KnowAIHub/llm/tree/main/sft/lora_in_image)
21. [实现 Position Embedding、测试 Word Embedding、测试 GPT-2 的NTP过程、实现 Transformer 的模型训练与测试](https://github.com/KnowAIHub/llm/tree/main/transformer)
22. [实现 vLLM 在 GPU 和 CPU 情况下进行推理](https://github.com/KnowAIHub/llm/tree/main/inference)
23. [对 LLM 实现类似于 o1 逻辑推理的 Prompt](https://github.com/KnowAIHub/llm/blob/main/inference/o1-reasoning.py)
24. [使用代码数据对CodeLlama进行微调](https://github.com/KnowAIHub/llm/blob/main/sft/codellama_code_sft.ipynb)
25. [微调 Llama 进行文本分类任务](https://github.com/KnowAIHub/llm/tree/main/huggingface/LlamaForClassification)
26. [利用预训练的 BERT 系模型实现 LLM Router，同时进行 CPT 50%和80% 评测计算](https://github.com/KnowAIHub/llm/tree/main/llm_router)
27. [结合Autotrain-advanced 对 LLM 进行白盒知识蒸馏](https://github.com/KnowAIHub/llm/tree/main/knowledge_distillation)
28. [使用 Transformers 和 Faiss 实现图片相似检索](https://github.com/KnowAIHub/llm/tree/main/huggingface/image_similarity)
29. [解析如何利用 CLIP 为 VLMs 的 Visual Encoder 提供视觉信息](https://github.com/KnowAIHub/llm/blob/main/vlm/vlm_visual_encoder_clip_image_feature.ipynb)
30. [对比多模态模型中不同的 Input Projector 的特点以及简单实现](https://github.com/KnowAIHub/llm/blob/main/vlm/vlm_input_projector.ipynb)
31. [基于 SetFit 实现 NLP 模型的知识蒸馏](https://github.com/KnowAIHub/llm/tree/main/knowledge_distillation/setfit_kd)
32. [Ollama的基本使用与并发多模型使用](https://github.com/KnowAIHub/llm/blob/main/inference/ollama_infer.ipynb)

# Reference

1. https://github.com/taishan1994/sentencepiece_chinese_bpe
2. https://github.com/Glanvery/LLM-Travel
3. https://github.com/hyunwoongko/transformer
4. https://github.com/zyds/transformers-code
5. https://github.com/leeguandong/MiniLLaMA3
6. https://github.com/datawhalechina/self-llm
7. [使用huggingface的PEFT库在千问2基础上进行Lora指令微调](https://www.ethanzhang.xyz/2024/07/09/%E3%80%90%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E3%80%91%E4%BD%BF%E7%94%A8huggingface%E5%9C%A8%E5%8D%83%E9%97%AE2%E5%9F%BA%E7%A1%80%E4%B8%8A%E8%BF%9B%E8%A1%8CLora%E6%8C%87%E4%BB%A4%E5%BE%AE%E8%B0%83/)
8. https://github.com/monologg/JointBERT
9. https://github.com/Linear95/bert-intent-slot-detector
10. https://github.com/Coobiw/MPP-LLaVA
