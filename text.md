# ProSOT: Distribution-Robust Integration of Single-Cell Protein Data via Unbalanced Optimal Transport![](assets/17704363704599.png)
## Installation
It is recommended to create a new environment for ProSOT.
```
conda create -n ProSOT python==3.8
conda activate ProSOT
``` 
The clone the ProSOT repository:
```
git clone https://github.com/VitaIntelli-CQU/ProSOT.git
```
and then install the required packages below:
```
pip install -r requirements.txt
```
## Usage
All processed data have already been placed in the corresponding folders under the Data.
If you want to obtain the results after batch mixing of the PBMC dataset, you can train the model using the following code.
```
cd Data/PBMC
python Data/PBMC/pbmc_proSOT.py
```
If you want to evaluate the quality of the obtained embeddings, you can use the following code.
```
python Data/PBMC/evaluate_embedding.py
```