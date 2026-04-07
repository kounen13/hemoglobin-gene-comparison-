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
7. calculate G~C content %.

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

### phylogenetic tree

![phylogenetic tree](https://github.com/kounen13/hemoglobin-gene-comparison-/blob/ce4603739886e9f36a06b4947e1f6f6f06da3e4e/Result/phylogenetic_tree.jpg)

#### biological interpretation 
- **closest relative:** human and mice share most rcent common ancestry, shown by their close branching 
- **Divergence:** zebrafish most diverged compare to mice from human due to early divergence of fish
- **evolutionary divergence:** the braching order reflects history of evolution zebrafish(fish) diverged first
then frog(amphibian) lastly mammals (human and mice)
- **branch length:** represent genetic ditance like zebrafish show 0.34 units change which is highest mean 
most genetically distinct species

## G~C content %

|species  | count of G| count of C | G~C %  |
|----------|----------|------------|--------|
 |human |325 |320| 40.1|
|mouse |161 |160 |51|
|frog |382 |382 |35.9|
|zebrafish |210 |212 |46.1|

Here i measure Guanine and Cytosine percentage 
- can be use this formula G+C/A+T+G+C ×100
- here i used [GC online calculator ](https://www.sciencebuddies.org/science-fair-projects/references/genomics-g-c-content-calculator)

