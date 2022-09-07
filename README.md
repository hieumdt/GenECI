# Event Causality Identification via Generation of Important Context Words
==========

This repo contains our PyTorch implementation for the paper [Event Causality Identification via Generation of Important Context Words](https://aclanthology.org/2022.starsem-1.28.pdf). 


## GenECI

1. Prepare data\
Download the desired corpus (ESL, Causal-TB) and put it in folder ```.\datasets```\
and run:
```
python datasets/preprocessor/preprocessor.py
```

2. Train model:
```
sh ESL_bash.sh
```
or
```
sh CausalTB_bash.sh
```
Note \
Need thís code is still under review 
## License

All work contained in this package is licensed under the Apache License, Version 2.0.

# Reference
Bibtex:
```
@article{Man2022EventCI,
  title={Event Causality Identification via Generation of Important Context Words},
  author={Hieu Man and Minh Nguyen and Thien Huu Nguyen},
  journal={Proceedings of the 11th Joint Conference on Lexical and Computational Semantics},
  year={2022}
}
```
Email: hieuman2708@gmail.com; v.hieumdt@vinai.io

