---
inference: false
---

<br>
<br>

# LLaVA Model Card

This is a pretrained checkpoint, you can use it to instruct tune your multimodal models.

Check out the instructions [here](https://github.com/haotian-liu/LLaVA/blob/main/README.md#visual-instruction-tuning)

## Model details

**Model type:**
LLaVA is an open-source chatbot trained by fine-tuning LLaMA/Vicuna on GPT-generated multimodal instruction-following data.
It is an auto-regressive language model, based on the transformer architecture.

**Model date:**
LLaVA-336px-Pretrain-Vicuna-13B-v1.3 was trained in July 2023.

**Paper or resources for more information:**
https://llava-vl.github.io/

## License
Non-commerical Use.

**Where to send questions or comments about the model:**
https://github.com/haotian-liu/LLaVA/issues

## Intended use
**Primary intended uses:**
The primary use of LLaVA is research on large multimodal models and chatbots.

**Primary intended users:**
The primary intended users of the model are researchers and hobbyists in computer vision, natural language processing, machine learning, and artificial intelligence.

## Training dataset
- 558K filtered image-text pairs from LAION/CC/SBU, captioned by BLIP.
