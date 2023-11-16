# spelling-mistake-maker
Make realistic spelling mistakes (i.e. data augmentation for NLP)

# *WIP*

this project is a work in progress - feel free to take a look but there is lots to do before it'll make sense

# dev environment setup

conda create -n spelling_mistake_maker python==3.9 -y
conda activate spelling_mistake_maker
pip install torch transformers datasets sentencepiece pandas matplotlib wikipedia jupyter notebook==6.*

```
conda create -n spelling_mistake_maker python==3.9 -y
conda activate spelling_mistake_maker
pip install torch --index-url https://download.pytorch.org/whl/cu121
pip install transformers accelerate datasets pandas matplotlib wikipedia jupyter notebook==6.*
```

in case the env gets messed up and you need to start again

`conda remove --name spelling_mistake_maker --all`