# VRR-QA: Visual Relational Reasoning in Videos Beyond Explicit Cues (CVPR 2026, Highlight Paper)

Official repository for VRR-QA, CVPR 2026
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
`python eval_seq.py --input-dir <path to data> --model-type <model_type> --num-frames 16`

## Cite

If you use this code in your research, please cite:

```bibtex
@article{swetha2025vrrqa,
  title={VRR-QA: Visual Relational Reasoning in Videos Beyond Explicit Cues},
  author={Swetha, Sirnam and Gupta, Rohit and Kulkarni, Parth Parag and Shatwell, David G and Santiago, Jeffrey A Chan and Siddiqui, Nyle and Fioresi, Joseph and Shah, Mubarak},
  journal={arXiv preprint arXiv:2506.21742},
  year={2026}
}
```

## Contact

If you have any problems with the code or have a question, please open an issue or email swetha(dot)sirnam at ucf.edu. 
I'll try to answer as soon as possible.
