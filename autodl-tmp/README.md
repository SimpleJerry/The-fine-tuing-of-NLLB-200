# autodl-tmp

目录结构：

> autodl-tmp/
>     README.md
>     nllb-200-distilled-600M/
>         .gitattributes
>         config.json
>         generation_config.json
>         pytorch_model.bin
>         README.md
>         sentencepiece.bpe.model
>         special_tokens_map.json
>         tokenizer.json
>         tokenizer_config.json
>     zh2ko_based_on_nllb-200-distilled-600M_20240618/
>         config.json
>         generation_config.json
>         model.safetensors
>         special_tokens_map.json
>         tokenizer.json
>         tokenizer_config.json
>         training_args.bin
>         checkpoint-315000/
>             config.json
>             generation_config.json
>             model.safetensors
>             optimizer.pt
>             rng_state.pth
>             scheduler.pt
>             trainer_state.json
>             training_args.bin

说明：

nllb-200-distilled-600M为nllb-200预训练模型

zh2ko_based_on_nllb-200-distilled-600M_20240618为在nllb-200-distilled-600M预训练模型基础上进行微调的中韩翻译模型，实验日期为2024.06.18，数据使用了한국어-중국어 번역 말뭉치(기술과학)中的자동차/교통/소재(30만)部分
