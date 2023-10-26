# What is this?
The input datasets for KGAT-pytorch: https://github.com/LunaBlack/KGAT-pytorch

## Datasets
* ```kg-all, kg-mal, kg-wikidata, none```
  * for "4.2 Quantitative Aspect: Recommendation Experiment 1"
* ```wikidata-ablation_outX```
  * for "4.3 Qualitative Aspect: Recommendation Experiment 2"
  * ```outX``` means remapped id of each property excluded respectively.
  * See ```relation_list.txt``` for property mappings.

##  Usage
1. Download this datasets
2. Clone https://github.com/LunaBlack/KGAT-pytorch
3. Replace ```KGAT-pytorch > datasets``` with  ```kgat-input > datasets```
4. Run KGAT for recommendation

