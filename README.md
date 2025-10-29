MoLE: Dynamic LoRA Routing for Multi-Task NLP

MoLE (Mixture of LoRA Experts) is an project for efficient LLM adaptation using lightweight LoRA adapters. It focuses on domain-specific tasks like legal document summarization (BillSum dataset) and biomedical QA (PubMedQA), with a frozen T5-base backbone and dynamic routing between adapters.
The setup encapsulates task knowledge in small "moles" (adapters) for privacy-isolated, low-compute tuning—no full model changes.

