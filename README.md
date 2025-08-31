# Table Structure Recognition
Master thesis at FIT (B|V)UT 2024/2025. Table structure recognition using multimodal transformers

Final thesis text in ENG: [Vlach_Master_thesis_Table_structure.pdf](Vlach_Master_thesis_Table_structure.pdf)

## Keywords
Table Structure Recognition, Table detection, Document Structure Analysis, Multimodal transformer, Word relation prediction, Optical Character Recognition, Deep learning, Computer vision

## Abstract
This thesis introduces the topic of Table Structure Recognition (TSR), which is used to analyze and reconstruct scanned tables. Current methods are introduced and expanded upon to create a Table Structure Recognition system. First, the Optical Character Recognition (OCR) system detects and transcribes words. The table structure is created using adjacency matrices representing word relation classes (same cell, column clusters, row clusters). The proposed architecture consists of a CNN backbone, a multimodal decoder transformer, class-wise prediction heads, and post-processing table reconstruction algorithm. The architecture is proven to work and is comparable with refference literature on the PubTables-1M dataset. The trained models are also fine-tuned on a custom HeritageTabNet dataset with positive improvement on both datasets.
