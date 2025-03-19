# Med-R1-Alpha
Unleashing Reasoning in Medical Large Language Models

## Overview  

Building on the advancements of [DeepSeek-R1](https://huggingface.co/deepseek-ai/DeepSeek-R1) in enhancing reasoning through reinforcement learning (RL), recent open-source projects have explored RL’s potential in training LLMs. However, these efforts have remained confined to limited domains and smaller-scale models, without fully expanding to complex, large-scale applications.  

Med-R1 is designed to unleash the reasoning capability of medical LLMs through RL training, relying only on low-cost, small-scale multiple-choice QA data rather than the construction of large-scale Chain-of-Thought (CoT) datasets or distillation from proprietary models like GPT. Unlike conventional methods that depend on costly supervised fine-tuning with extensive CoT annotations, Med-R1 demonstrates that a well-trained instruction-tuned LLM can develop strong reasoning skills with minimal training samples.  

In our early experiments, Med-R1-Alpha, trained with RL using only a small set of multiple-choice QA data, has already outperformed Huatuo-O1, which was trained via supervised fine-tuning on large-scale CoT data distilled from GPT-O1. This result highlights that reinforcement learning can effectively incentivize and refine reasoning capabilities without relying on expensive CoT supervision. Similar to DeepSeek-R1-Zero, Med-R1-Alpha shows that RL-trained models can achieve superior reasoning ability with fewer samples and without the need for complex, manually annotated CoT data.  

Beyond textual reasoning, we have also unleashed this capability in medical Vision-Language Models (VLMs). Our work, [MedVLM-R1](https://arxiv.org/abs/2502.19634), demonstrates how reinforcement learning can significantly enhance multi-modal reasoning within medical AI. Med-R1 represents a step towards building cost-efficient, highly capable medical LLMs that leverage RL to develop strong reasoning abilities without dependence on large-scale, closed-source CoT data.  

# Preview Results

![image](https://github.com/user-attachments/assets/70af2b9f-3285-4e00-be62-dc8c4958809b)


# TODO

- [x] Release preview results
- [ ] Release technical report
- [ ] Release model weights
- [ ] Release evaluation results
- [ ] Release training dataset

# Citation

```bibtex
@Misc{med-r1-alpha,
  title = {Med-R1-Alpha: Unleashing Reasoning in Medical Large Language Models},
  author = {Med-R1 Team},
  howpublished = {\url{https://github.com/cheliu-computation/Med-R1-Alph}},
  year = {2025}
}
```
