# pyaf3
python API for local Alphafold3

## install
It was found CUDA12.6 best to install, and you should apply the af3 weights and put it in ./af3/model/
```
git clone https://github.com/google-deepmind/alphafold3.git ./af3
cd ./af3
conda create -n af3 python=3.11 
conda activate af3
conda install -c bioconda hmmer
pip install -r dev-requirements.txt 
pip install . --no-deps 
./fetch_databases.sh [<DB_DIR>]
python run_alphafold_test.py 
```
## 
