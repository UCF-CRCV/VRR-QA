# [VRR-QA: Visual Relational Reasoning in Videos Beyond Explicit Cues](https://openaccess.thecvf.com/content/CVPR2026/papers/Swetha_VRR-QA_Visual_Relational_Reasoning_in_Videos_Beyond_Explicit_Cues_CVPR_2026_paper.pdf) (CVPR 2026, Highlight Paper)

Official repository for VRR-QA, CVPR 2026 [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Swetha_VRR-QA_Visual_Relational_Reasoning_in_Videos_Beyond_Explicit_Cues_CVPR_2026_paper.pdf)
## Install
```
conda create -n implicit python==3.9 -y
conda activate implicit
pip install torch torchvision torchaudio
mamba install ffmpeg -c conda-forge
ffmpeg -decoders | grep -i nvidia
pip install torchcodec --index-url=https://download.pytorch.org/whl/cu124
pip install vllm
pip install pandas
```


## Evaluation 
`python eval.py --input-dir <path to data> --model-type <model_type> --num-frames 16`

## Cite

If you use this code in your research, please cite:

```bibtex
@InProceedings{Swetha_2026_CVPR,
    author    = {Swetha, Sirnam and Gupta, Rohit and Kulkarni, Parth Parag and Shatwell, David G and A Chan Santiago, Jeffrey and Siddiqui, Nyle and Fioresi, Joseph and Shah, Mubarak},
    title     = {VRR-QA: Visual Relational Reasoning in Videos Beyond Explicit Cues},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2026},
    pages     = {32840-32849}
}
```

## Contact

If you have any problems with the code or have a question, please open an issue or email swetha(dot)sirnam at ucf.edu. 
I'll try to answer as soon as possible.
