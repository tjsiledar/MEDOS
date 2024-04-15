# Product Description and QA Assisted Self-Supervised Opinion Summarization

Paper Link: [Product Description and QA Assisted Self-Supervised Opinion Summarization](https://arxiv.org/abs/2404.05243)

## Abstract
In e-commerce, opinion summarization is the process of summarizing the consensus opinions found in product reviews. However, the potential of additional sources such as product description and question-answers (QA) has been considered less often. Moreover, the absence of any supervised training data makes this task challenging. To address this, we propose a novel synthetic dataset creation (SDC) strategy that leverages information from reviews as well as additional sources for selecting one of the reviews as a pseudo-summary to enable supervised training. Our Multi-Encoder Decoder framework for Opinion Summarization (MEDOS) employs a separate encoder for each source, enabling effective selection of information while generating the summary. For evaluation, due to the unavailability of test sets with additional sources, we extend the Amazon, Oposum+, and Flipkart test sets and leverage ChatGPT to annotate summaries. Experiments across nine test sets demonstrate that the combination of our SDC approach and MEDOS model achieves on average a 14.5% improvement in ROUGE-1 F1 over the SOTA. Moreover, comparative analysis underlines the significance of incorporating additional sources for generating more informative summaries. Human evaluations further indicate that MEDOS scores relatively higher in coherence and fluency with 0.41 and 0.5 (-1 to 1) respectively, compared to existing models. To the best of our knowledge, we are the first to generate opinion summaries leveraging additional sources in a self-supervised setting.

## Citation
```
@misc{siledar2024product,
      title={Product Description and QA Assisted Self-Supervised Opinion Summarization}, 
      author={Tejpalsingh Siledar and Rupasai Rangaraju and Sankara Sri Raghava Ravindra Muddu and Suman Banerjee and Amey Patil and Sudhanshu Shekhar Singh and Muthusamy Chelliah and Nikesh Garera and Swaprava Nath and Pushpak Bhattacharyya},
      year={2024},
      eprint={2404.05243},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```