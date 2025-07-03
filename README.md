# Awesome-ImageRestoration

本项目旨在收集和整理与图像恢复（Image Restoration）相关的论文、资料和资源，方便自己和相关研究者和查阅。

## 目录结构

- `asserts/`：项目相关的图片和资源文件。
- `papers-md/`：以Markdown格式整理的论文笔记或摘要。
- `papers/`：收集的论文PDF文件。


## 论文整理

### 2022

- **Complexity Experts are Task-Discriminative Learners for Any Image Restoration** (CVPR 2025)
  - [论文链接](https://openaccess.thecvf.com/content/CVPR2025/papers/Zamfir_Complexity_Experts_are_Task-Discriminative_Learners_for_Any_Image_Restoration_CVPR_2025_paper.pdf) ｜ [开源代码](https://github.com/eduardzamfir/MoCE-IR) ｜ [论文解读](paper-md/2025-CVPR-Complexity%20Experts%20are%20Task-Discriminative%20Learners%20for%20Any%20Image%20Restoration.md)
  - 近年来，集多种功能于一体的图像恢复模型在通过统一框架处理多样性退化问题方面取得了突破性进展。然而，**绑定于特定任务的参数在面对其他任务时常常处于非激活状态，这使得专家混合（Mixture-of-Experts, MoE）架构成为自然的延伸选择。**尽管如此，MoE 往往表现出不一致的行为：有些专家会在多个任务间意外泛化，而另一些专家甚至在其目标任务内表现不佳。这种情况阻碍了在推理过程中通过跳过无关专家以提升计算效率的尝试。我们认为，传统 MoE 的统一和僵化架构导致了这种不理想的表现。**为此，我们提出了“复杂度专家”——采用不同计算复杂度和感受野的灵活专家模块。**一个核心挑战是如何为每个专家分配任务，因为退化的复杂性事先未知。因此，我们在执行任务时采取了简单地偏向较低复杂度的策略。令人惊讶的是，这种偏好实际上有效推动了任务的特定分配，使任务能匹配到合适复杂度的专家。大量实验验证了我们的方法，在保证卓越性能的同时，实现了在推理时绕过无关专家的能力。我们提出的 MoCE-IR 模型超越了最新方法，展现出其高效性和实际应用价值。源代码和模型已在 eduardzamfir.github.io/MoCE-IR/ 公开发布。


## 用途

- 便于查找和学习最新的图像恢复相关论文。
- 提供论文笔记和摘要，帮助快速理解论文内容。
- 汇总相关资源，促进学术交流。

