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
@misc{luo2024large,
      title={Large language models surpass human experts in predicting neuroscience results}, 
      author={Xiaoliang Luo and Akilles Rechardt and Guangzhi Sun and Kevin K. Nejad and Felipe Yáñez and Bati Yilmaz and Kangjoo Lee and Alexandra O. Cohen and Valentina Borghesani and Anton Pashkov and Daniele Marinazzo and Jonathan Nicholas and Alessandro Salatiello and Ilia Sucholutsky and Pasquale Minervini and Sepehr Razavi and Roberta Rocca and Elkhan Yusifov and Tereza Okalova and Nianlong Gu and Martin Ferianc and Mikail Khona and Kaustubh R. Patil and Pui-Shee Lee and Rui Mata and Nicholas E. Myers and Jennifer K Bizley and Sebastian Musslick and Isil Poyraz Bilgin and Guiomar Niso and Justin M. Ales and Michael Gaebler and N Apurva Ratan Murty and Chloe M. Hall and Jessica Dafflon and Sherry Dongqi Bao and Bradley C. Love},
      year={2024},
      eprint={2403.03230},
      archivePrefix={arXiv},
      primaryClass={q-bio.NC}
}
```
