# Large language models surpass human experts in predicting neuroscience results
![brainbench](https://github.com/braingpt-lovelab/BrainBench/assets/32969920/6e3a5a93-1f26-41bf-b93e-995fd8bd42fd)

BrainBench's code base is currently divided into 3 parts, each of which is a tracked repo.

### Repos:
- `experiments`: repo hosting all analyses scripts that can be used to obtain raw results (pre-plotting) to replicate the findings from scratch.
- `finetuning`: repo hosting the finetuning part of the paper.
- `plotting`: repo hosting plotting scripts to remake all figures from the paper using results produced in `experiments`.

For step-by-step guidance, please refer to README in each dedicated repo.

### To work with this repo locally:
```
git clone git@github.com:braingpt-lovelab/BrainBench.git --recursive
```

### Hardware requirements:
- Nvidia A100 (80GB) * 4
- 2TB storage

### Attribution
```
@article{luo_large_2024,
	title = {Large language models surpass human experts in predicting neuroscience results},
	issn = {2397-3374},
	url = {https://www.nature.com/articles/s41562-024-02046-9},
	doi = {10.1038/s41562-024-02046-9},
	abstract = {Abstract
            Scientific discoveries often hinge on synthesizing decades of research, a task that potentially outstrips human information processing capacities. Large language models (LLMs) offer a solution. LLMs trained on the vast scientific literature could potentially integrate noisy yet interrelated findings to forecast novel results better than human experts. Here, to evaluate this possibility, we created BrainBench, a forward-looking benchmark for predicting neuroscience results. We find that LLMs surpass experts in predicting experimental outcomes. BrainGPT, an LLM we tuned on the neuroscience literature, performed better yet. Like human experts, when LLMs indicated high confidence in their predictions, their responses were more likely to be correct, which presages a future where LLMs assist humans in making discoveries. Our approach is not neuroscience specific and is transferable to other knowledge-intensive endeavours.},
	language = {en},
	urldate = {2024-11-29},
	journal = {Nature Human Behaviour},
	author = {Luo, Xiaoliang and Rechardt, Akilles and Sun, Guangzhi and Nejad, Kevin K. and Yáñez, Felipe and Yilmaz, Bati and Lee, Kangjoo and Cohen, Alexandra O. and Borghesani, Valentina and Pashkov, Anton and Marinazzo, Daniele and Nicholas, Jonathan and Salatiello, Alessandro and Sucholutsky, Ilia and Minervini, Pasquale and Razavi, Sepehr and Rocca, Roberta and Yusifov, Elkhan and Okalova, Tereza and Gu, Nianlong and Ferianc, Martin and Khona, Mikail and Patil, Kaustubh R. and Lee, Pui-Shee and Mata, Rui and Myers, Nicholas E. and Bizley, Jennifer K. and Musslick, Sebastian and Bilgin, Isil Poyraz and Niso, Guiomar and Ales, Justin M. and Gaebler, Michael and Ratan Murty, N. Apurva and Loued-Khenissi, Leyla and Behler, Anna and Hall, Chloe M. and Dafflon, Jessica and Bao, Sherry Dongqi and Love, Bradley C.},
	month = nov,
	year = {2024},
}
```
