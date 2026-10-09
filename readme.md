# Tianyu Ma (马天宇)

**Prospective Ph.D. Student | Model Compression · Quantization · Pruning · Efficient AI**

📧 **Email:** [wa24201030@stu.ahu.edu.cn](mailto:wa24201030@stu.ahu.edu.cn)  
📄 **Curriculum Vitae:** [View my full CV (PDF)](./Curriculum%20Vitae-MTY.pdf)

---

## About Me & Ph.D. Opportunities

Hello! I am **Tianyu Ma**, a researcher with a background in computer science and a strong interest in **efficient deep learning and model compression**. My research focuses on **post-training quantization, model pruning, and efficient inference**, particularly for Transformers, vision transformers (ViTs), and large language models (LLMs).

**I am actively seeking Ph.D. opportunities to continue my research in model compression.** I am especially interested in developing practical and principled methods that make large models more efficient, flexible, and deployable across resource-constrained hardware. **If my research background aligns with your group's interests, I would be very grateful for the opportunity to discuss potential Ph.D. positions. Professors and prospective advisors are welcome to contact me by email.** Thank you for your time and consideration!

## Research Interests

- **Model compression:** post-training quantization, elastic / mixed-precision quantization, pruning, sparsity, and knowledge distillation.
- **Efficient inference and deployment:** hardware-aware model optimization, inference acceleration, and deployment on resource-constrained devices.
- **Parameter-efficient adaptation:** efficient fine-tuning and low-rank methods.
- **Efficient Transformer models:** compression of ViTs and LLMs.

## Publications & Manuscripts

### Accepted

- **PEQuant: Prompt-Driven Activation Reconstruction for Elastic Quantization of Vision Transformers**  
  K. Xu, **T. Ma**, X. Shen, et al.  
  *ACM International Conference on Multimedia (ACM MM), 2026.*  
  **Accepted — Oral Presentation.**

### Submitted / Under Review

- **EQ-GPTQ: Towards Finetuning-Free Elastic Precision Quantization for Transformers**  
  K. Xu, **T. Ma**, X. Wang, et al.  
  *Submitted to IEEE Transactions on Emerging Topics in Computational Intelligence, 2026.*

- **CoDrift: Mitigating Compensation Drift in Reconstruction-Based LLM Pruning at High Sparsity**  
  **T. Ma**, X. Shen, K. Xu, et al.  
  *Submitted to ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2027.*

- **PRISMQ: Noise-Aware Resource Allocation for Elastic Post-Training Quantization**  
  K. Xu, L. Yang, **T. Ma**, et al.  
  *Submitted to International Conference on Learning Representations (ICLR), 2027.*

### In Preparation

- **EP-GPT: Nested Weight Slices for Storage-Efficient Multi-Sparsity Pruning of LLMs**  
  **T. Ma**, J. Wang, K. Xu, et al.  
  *Manuscript in preparation; planned submission to Design Automation Conference (DAC), 2027.*

> **Publication status note:** Only PEQuant is listed as accepted. Other works are under submission or in preparation, as indicated above.

## Research Experience

### 1. EQ-GPTQ — Fine-Tuning-Free Elastic Quantization for Transformers

- Developed an **elastic post-training quantization** framework to support multiple precision configurations using a single calibrated set of model weights.
- Explored **token-level activation fusion** based on similarity and cross-layer importance, alongside **Hessian-aware, column-level weight fusion**.
- Targeted flexible mixed-precision deployment without requiring separate optimization for every bit-width configuration.

### 2. PEQuant — Prompt-Driven Activation Reconstruction for ViTs

- Investigated activation-space error compensation for **elastic post-training quantization of vision transformers**, rather than relying solely on weight reconstruction.
- Designed **stacked low-rank additive prompts** for efficient activation reconstruction without increasing sequence length, together with artifact-absorbing prompts to address quantization-induced outliers.
- Incorporated **cascaded LoRA parameterization and cross-precision activation fusion** to support robust joint calibration across bit widths.

### 3. CoDrift — Compensation-Drift-Aware LLM Pruning

- Studied compensation drift in **training-free, reconstruction-based pruning** of LLMs at high sparsity.
- Anchored the reconstruction objective to **the original full-precision model's outputs** to reduce drift introduced by iterative weight compensation.
- Investigated **column-residual proxies, compensation-matrix techniques, and pruning-loss-aware global reordering** to improve pruning decisions.

### 4. EP-GPT — Storage-Efficient Multi-Sparsity LLM Pruning

- Developed a **nested-mask and weight-slicing** approach for supporting multiple sparsity levels from a single calibration process.
- Organized weights into **shared core weights and incremental slices** for on-demand loading at inference time.
- Explored **slice-consistent reconstruction and hardware–software co-design** for resource-constrained deployment.

## Education

| Institution | Field | Level |
| --- | --- | --- |
| **Anhui University** | Computer Science and Technology | Master's studies |
| **Nanchang University** | Information and Computing Science | Bachelor's degree |

**Master's advisor:** Prof. **Ke Xu** — neural network model compression, embedded AI systems and deployment, and generative model optimization.

## Patent

- **A Dual-Mode Activation Superposition and Prompt Compensation Method and Apparatus for Elastic-Precision Quantization** (2026).  
  Inventors: **Ke Xu, Tianyu Ma, Xinghua He**. *Patent application in preliminary review.*

## Academic Activities

- Assisted in preparing a **National Natural Science Foundation of China (NSFC) General Program** research proposal.
- Assisted my advisor with manuscript reviews for venues including **ICLR, CVPR, IJCAI, ICML, SIGKDD, ACM MM, AAAI**, and **IEEE TCSVT**.

## Honors & Qualifications

- **Special-Class Scholarship**, School of Artificial Intelligence, Anhui University.
- **College English Test Band 6 (CET-6)**.

## Contact

I am eager to pursue a **Ph.D. in model compression and efficient artificial intelligence**. If you are a professor or prospective supervisor working on related topics and think my experience could be a good fit for your research group, please feel free to reach out.

- **Email:** [wa24201030@stu.ahu.edu.cn](mailto:wa24201030@stu.ahu.edu.cn)
- **Full CV:** [Curriculum Vitae (PDF)](./Curriculum%20Vitae-MTY.pdf)

Thank you for visiting my page and considering my application.
