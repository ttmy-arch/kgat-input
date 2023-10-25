# What is this?
The input datasets for KGAT-pytorch: https://github.com/LunaBlack/KGAT-pytorch

## Contents
* ```kg-all, kg-mal, kg-wikidata and none```
  * Quantitative Aspect: Recommendation Experiment 1
* ```wikidata-ablation_outX```
  * Quantitative Aspect: Recommendation Experiment 2
  * ```outX``` means remapped id of each property excluded respectively.
  * A map of property is ```relation_list.txt```.

##  Usage
1. Download this datasets
2. Clone https://github.com/LunaBlack/KGAT-pytorch
3. Replace ```KGAT-pytorch > datasets``` with  ```kgat-input > datasets```
4. Run KGAT for recommendation

