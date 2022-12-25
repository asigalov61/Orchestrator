# Orchestrator Training Code

***

## NOTES ON MODEL TRAINING SETTINGS

### 1) 4096 seq_len @ 512 local window attention size seem to be optimal for music
### 2) 24 layers @ 1024 model dimension seems to be the optimum for model size/speed and resulting loss/accuracy
### 3) Training @ 4 batches with gradient accummulation every 4 steps seems to be optimal
### 4) Fully random sampling seems to produce optimal results
### 5) Fully random sampling helps to condition model for masking/inpainting generation
### 6) Fully random sampling helps to greately reduce training dataset size without significant loss in music learning performance

***

### Project Los Angeles
### Tegridy Code 2022
