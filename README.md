# 🧬 hemoglobin-gene-comparison-
It is bioinformatics project comparison of hemoglobin gene sequence of human, mice, frog, and zebrafish.  
### species usedd:
```bash
homo sapiens (human)
mus musculus (mouse)
danio rerio (zebrafish)
xenopus laevis (frog)
```
### 📑 Data source
gene sequence were downloaded from NCBI database in FASTA format.

### 🎯Methods 
1. downloaded HBB gene sequence from **NCBI**.
2. store sequence in a **FASTA dataset**.
3. perform multiple sequence alignment using **clustal omega**.
4. calculate sequence similarity between species with help of global alignment( needleman wunsch algorithm )
5. construct phylogenetic tree by using **mega**
6. made 3d protein structure using **UCSF ChimeraX**

### 📌Tools used 
```bash
 FASTA dataset
 Clustal omega
 MEGA
 NCBI 
 UCSF ChimeraX
 Github
 ```
## 🧐 Result
### sequence similarity among species.

|species 1 |species 2 | similarity % |
|----------|----------|--------------|
|human | mouse | 82.10% |
|human |frog |68.40%|
|human | zebrafish | 61.20%|
|mouse |frog |67.90%|
|mouse |zebrafish |60.50% |
|frog |zebrafish | 65.80% |

this table show evolutionary proximity through genetic similarity
like human - mice have highest similarity due to mamalian ancestry 
while human zebrafish low similarity due to early evolutionary divergence.

### you can also see [alignment Here](https://github.com/kounen13/hemoglobin-gene-comparison-/blob/main/Result/alignment%20.jpg)
 


