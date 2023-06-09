# KEMI

The model and analysis implementation of _Knowledge-enhanced Mixed-initiative Dialogue System for Emotional Support Conversations_ (ACL 2023), which can be downloaded via this [url](https://drive.google.com/drive/folders/1gFlgKxda5O-RSbb3lhaj6oXiopgAsJKg?usp=sharing). 

The code is built upon this [repo](https://github.com/thu-coai/Emotional-Support-Conversation/tree/main/codes_zcj). 

## Run the code
Under the 'blenderbot' directory,
1. Run 'bash RUN/prepare_strat.sh' to prepare the data.
2. Run 'bash RUN/train_strat.sh' to train the model.
3. Run 'bash RUN/infer_strat.sh' to evaluate the model.

## Analysis of Mixed Initiative
Under the 'eafr' directory, you can find the fingerprint data of the analysis results on ESConv and EmpatheticDialogues. 


## Citation
If the code or data is used in your research, please star this repo and cite our paper as follows:
```
@article{DBLP:journals/corr/abs-2305-10172,
  author       = {Yang Deng and
                  Wenxuan Zhang and
                  Yifei Yuan and
                  Wai Lam},
  title        = {Knowledge-enhanced Mixed-initiative Dialogue System for Emotional
                  Support Conversations},
  journal      = {CoRR},
  volume       = {abs/2305.10172},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2305.10172},
}
```
