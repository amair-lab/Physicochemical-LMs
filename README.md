## Leveraging Large Language Models for Explaining Material Synthesis Mechanisms

#### 🎉 This work is accept to NeurIPS 2024 - AI4Mat Workshop!

<div align="center">
  <img src="assets/img.png" alt="Image-1" width="800"/>
</div>

**Figure 1: Semantic illustration of our proposed framework for large language model evaluation in nanomaterial synthesis prediction, highlighting concepts and workflow.** a) nanosynthesis study loop: begins with basic conditions, leading to the discovery of novel synthesis rules through experiments involving variable adjustments. b) exemplifies the synthesis mechanism, dissected into causality and correlations, with an emphasis on correlations described through condition-observation pairs. c) outlines the process from sourcing relevant literature (using key area keywords) for benchmark construction and model evaluation.


## 💻 Test your model? 

Before running, the deployment of [🚀FastChat](https://github.com/lm-sys/FastChat) is recommended for inferencing LLMs with OpenAI API fashion. It is an open platform for training, serving, and evaluating large language model based chatbots.

After deployed LLMs, you may start the inference API in LAN, e.g., http://10.11.50.197:7860, and IP address `10.11.50.197` should be your machine's actual IP. The port can also be configured in FastChat. Then you should change the configuration of address and port in `eval_opensourced_llms.py`, it is easy to config. 

Finally, you could run each evaluation by simply run `python eval_opensourced_llms.py`

If you have `OpenAI API`, you could change the API Key in the code. And the `Claude API` configuration is in similar.


## 📖 Notes

This study focus on the evaluation of LLMs in science mechanisms understanding, trying to open a new perspective for AI for Science Research.  If anyone is interested, please see our manuscript.


### Contact

If you have any questions, please feel free to email: `yingmingpu@gmail.com`

### Citation

```bibtex
@inproceedings{
  pu2024leveraging,
  title={Leveraging Large Language Models for Explaining Material Synthesis Mechanisms: The Foundation of Materials Discovery},
  author={Yingming Pu and Liping Huang and Tao Lin and Hongyu Chen},
  booktitle={AI for Accelerated Materials Design - NeurIPS 2024},
  year={2024},
  url={https://openreview.net/forum?id=I6jYRbaai8}
}
```
