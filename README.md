# Children’s Reading Sentiment Recognition Dataset

This dataset is designed to provide high-quality training data for sentiment Recognition of children's reading. The dataset is derived from 62 well-known Chinese children's stories, covering a wide range of emotional expressions and narrative styles, and reflects the language and emotional features of children's reading.

## Dataset Description

By carefully selecting content from these 62 stories, we manually split and selected over 2000 sentences as the initial corpus. Each sentence has undergone data cleaning and normalization to remove meaningless symbols, redundant information, and language errors, ensuring high data quality.

To ensure the professionalism and scientific rigor of the data labeling process, three experienced child psychology researchers were invited to participate. Each sentence was classified based on its emotional impact on children. If all three researchers agreed on a sentence's classification, that classification became the final label for that sentence. In cases where disagreements occurred, the sentence was discarded to avoid bias caused by subjective labeling.

### Label Explanation

The emotional labels in this dataset are divided into three categories:

- **Total number of sentences**: 1166.
- **Positive Sentiment** (1): Sentences that have a positive, encouraging impact on children. There are 513 sentences, accounting for 44.01%.
- **Negative Sentiment** (-1): Sentences that may have a negative impact on children. There are 450 sentences, accounting for 38.57%.
- **Neutral Sentiment** (0): Sentences that have neither a clear positive nor negative impact on children. There are 203 sentences, accounting for 17.42%.

### Data Format

The dataset is stored in CSV format with the following two fields:

- **text**: The sentence text.
- **vote**: The sentiment label, with values 1 (positive), 0 (neutral), or -1 (negative).

### License
This dataset is licensed under the CC BY 4.0 License, allowing anyone to copy, distribute, and modify the dataset, as long as they provide appropriate credit to the original author.

### Contributors

Hongtao Mao: Dataset construction and processing

Xingwei Yan, Jiang Li, Qu Yang: Data labeling

### Acknowledgements

We would like to thank all the child psychology researchers who contributed to the labeling and verification of the dataset.

### Contact

For any questions or suggestions, please contact:
Hongtao Mao: maohongtao@mails.ccnu.edu.cn


