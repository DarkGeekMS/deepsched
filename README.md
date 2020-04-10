# DeepSched for Heterogeneous Systems Scheduling 

A PyTorch implementation for DeepSched, a deep neural network for learning a deep representation of heterogeneous distributed systems task scheduling.
The proposed network approximates the scheduling algorithms much faster. It takes as an input the machines specs and the jobs specs and generates for each job: a machine to run on, the actual start time and the actual finish time.

### Dataset

For more information about dataset format, please refer `data` folder for samples of required data format.

### Installation

```
pip install torch torchvision
```

### Training
```
python trainer.py
```
Provide optional arguments, if needed.
__Note:__ Training takes up to 1.5 GB of VRAM.

### Inference
```
python inference.py
```
Provide optional arguments, if needed.