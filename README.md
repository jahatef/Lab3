# Lab3

## Use these scripts to complete lab 3. 


Note: When installing scikit-learn do `pip install scikit-learn` instead of `pip install sklearn` if you encounter that error message.

Inference Command:

```
python run_generation.py \
    --model_type=pythia \
    --model_name_or_path=EleutherAI/pythia-410m
```

Training Command:

```
python train.py \
    --model_name_or_path EleutherAI/pythia-410m \
    --dataset_name enwik8 \
    --dataset_config_name enwik8 \
    --per_device_train_batch_size 1 \
    --per_device_eval_batch_size 1 \
    --do_train \
    --do_eval \
    --output_dir /tmp/train
```
