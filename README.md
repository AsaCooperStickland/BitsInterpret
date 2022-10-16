# Transparent: Understanding Transformer Internals

# Installation

```
git clone git@github.com:AsaCooperStickland/BitsInterpret.git
cd BitsInterpret
pip install -e .
```

Training a language model with activation either `relu`,`gelu` or `solu`.
You can add a penalty to the Fisher information matrix with `--fisher-penalty-weight`, or add an L1 norm penalty to the activations with `--l1-norm-penalty`.
```
python rebasin/scripts/train_wikitext_transformer.py --act-type $ACTIVATION 
```