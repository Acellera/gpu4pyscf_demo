# Demostration of using gpu4pyscf for a GPU enabled DFT calculation on Linux

## Install for linux:
```
conda create -n gpu4pyscf_demo
conda activate gpu4pyscf_demo
conda install -c conda-forge pyscf cuda-libraries-dev cuda-version

pip install gpu4pyscf-cuda12x
```

# Running test script for linux:
```
python test.py > output_linux.txt
```

# Output

[output_linx.txt](output_linux.txt)

