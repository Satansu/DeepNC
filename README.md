# DeepNC

# Software requirements:
- Python >= 3.7
- pytorch >= 1.6
- torch-geometric >= 1.6.1
- rdkit

# Running steps in terminal:
**1. Prepare data**

> python prepare_data.py

**2. Train a model**

> python training.py x y z

- x=[0,1,2]: 0 for Davis dataset, 1 for Kiba dataset, 2 for Allergy dataset.
- y=[0,1]: 0 for GEN, 1 for HGC-GCN
- z is the index of CUDA you use (choose 0 if you use 'cuda:0')

**3. Train a model with validation**

> python training_validation.py x y z

- x=[0,1,2]: 0 for Davis dataset, 1 for Kiba dataset, 2 for Allergy dataset.
- y=[0,1]: 0 for GEN, 1 for HGC-GCN
- z is the index of CUDA you use (choose 0 if you use 'cuda:0')
