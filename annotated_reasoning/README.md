# MUStReason Dataset

This directory contains the **gold-standard** and **silver-standard** reasoning annotations used in MUStReason.

## Files

### `gold.csv`

Contains the **gold-standard annotations**, manually verified and corrected by two annotators to ensure:

* correctness of modality descriptions,
* relevance to sarcasm classification,
* coherence of the overall reasoning.

Samples with label discrepancies were excluded.

### `silver.csv`

Contains the **silver-standard annotations**, automatically generated and sanity-checked to remove irrelevant content.

The silver annotations were evaluated against the gold data and achieved strong semantic alignment, with an average quality rating of **4.51/5** from GPT-based evaluation, further supported by a human user study.

## Citation

If you use this dataset, please cite our paper.

```bibtex
@misc{saha2025mustreasonbenchmarkdiagnosingpragmatic,
      title={MUStReason: A Benchmark for Diagnosing Pragmatic Reasoning in Video-LMs for Multimodal Sarcasm Detection}, 
      author={Anisha Saha and Varsha Suresh and Timothy Hospedales and Vera Demberg},
      year={2025},
      eprint={2510.23727},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.23727}, 
}
```
