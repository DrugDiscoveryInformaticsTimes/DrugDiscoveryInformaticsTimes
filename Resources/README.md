# Resources

創薬に関連する研究を行う際によく使われるDBやデータセットについてまとめています。

## Datasets 

* [DUD](http://dud.docking.org/)  
ligand(active化合物)群とdecoy(非active化合物)群を40個のターゲット1つ1つに用意したデータセット。

* [DUD-E](http://dude.docking.org/)  
DUDにはdecoyにactive化合物が含まれている、ターゲットが少ない。などの課題があり、課題を解決するように、より汎用的なligand(active化合物)群とdecoy(非active化合物)群のデータセット。

* [MOSES](https://github.com/molecularsets/moses)
SMILESなどの配列ベースのGenerative modelを評価するためのデータセット。いくつかの複数の手法との比較ができる。

## Databases

### Small molecule

* [PubChem](https://pubchem.ncbi.nlm.nih.gov/)  
幅広いソースから収集した有機化合物のデータベース。Compounds(SMLESやMOLなど), Substances(混合物、抽出物、錯体など), BioAssays(化合物のスクリーニングの結果など)の3つカテゴリーがある。

* [ChEMBL](https://www.ebi.ac.uk/chembl/)  
医薬品や医薬候補化合物などの低分子化合物のデータベース。

* [ZINC database](https://zinc20.docking.org/)  
バーチャルスクリーニング用の商用化合物データベース

* [DrugBank](https://go.drugbank.com/)  
医薬品及び医薬候補化合物とそれらターゲットのデータベース。

* [Quantum-Machine.org](http://www.quantum-machine.org/)  
quantum machineのための化合物データベースで、比較的小さい化合物データベース。 例えばQM9 Datasetは重原子(C,O, N, F)が9個までのサブセット。

* [eModel-BDB](http://brylinski.org/emodel-bdb-0)  
Binding DatabaseとPDBから取得した相互作用データを元に、薬物結合タンパク質の構造予測されたモデル約20万件を収録したデータベース。

### Protein-Protein inhibitor/stabilizer

* [iPPI-DB](https://ippidb.pasteur.fr/)  
PPI阻害剤・安定剤のバイオアッセイが行われた論文から手動でキュレーションしているデータベース。

* [TIMBAL](http://mordred.bioc.cam.ac.uk/timbal/)

### Protein sequence

* [UniProt](https://www.uniprot.org/)  
タンパク質配列と機能に関するのデータベース。

### Protein structure

* [PDB](https://www.rcsb.org/)  
タンパク質と核酸の3次元構造データのデータベース

* [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/)  
DeepMindとEMBL-EBIが提携して作成した、ヒトプロテオームと他の20種の主要生物のタンパク質構造予測データベース。今後、UniRef90に掲載されている1億以上のタンパク質の大部分をカバーするようにデータベースを拡張される予定。

### Genome

* [ENCODE](https://www.encodeproject.org/)  
ENCODEは、ヒトゲノムの機能的な領域を包括的なリストにまとめたデータベース。様々な細胞種でChIP-seq, RNA-seq, DNase-seq, ATAC-seqなどゲノムの機能的領域を捉える手法の結果、サンプル概要、実験条件、replicon, 解析フローなどがまとめられている。