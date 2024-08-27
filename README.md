# first_papi
This repository is for test and execute bioinformatics pipelines
 ### You will know How to use QIIMNE2 to do Bioinformatics
 Download and unzip the
---
### step1 : 👽 QIIME2 installation
1. For Windows Users
  - Open the commmand prompt in the Admistrator mode and run
```bash
wsl --install -d Ubuntu-22.04
```
- Or install windows Subsystem for Linux

👽 Then install QIIME2 environnement
```bash
  conda env create -n qiime2-amplicon-2024.5 --file https://data.qiime2.org/distro/amplicon/qiime2-amplicon-2024.5-py39-linux-conda.yml 
```

2. For Linux Users
```bash
mkdir -p ~/miniconda3/
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

After installing initialize with :
```bash
~/miniconda3/bin/conda init bash 
```
👽 Then install QIIME2 environnement
```bash
  conda env create -n qiime2-amplicon-2024.5 --file https://data.qiime2.org/distro/amplicon/qiime2-amplicon-2024.5-py39-linux-conda.yml 
```
3. For MacOS User
```bash
mkdir -p ~/miniconda3
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

After installing initialize with :
```bash
 ~/miniconda3/bin/conda init bash
```
👽 Then install QIIME2 environnement
```bash
wget https://data.qiime2.org/distro/amplicon/qiime2-amplicon-2024.2-py38-osx-conda.yml
conda env create -n qiime2-amplicon-2024.2 --file qiime2-amplicon-2024.2-py38-osx-conda.yml
```
5. Activate the QIIME2 environnement
```bash
   conda activate qiime2-amplicon-2024.5 

```
   you can also use
```bash
export PATH=~/miniconda3/bin:$PATH
source activate qiime2-amplicon-2024.2 
```
- Checking if QIIME2 has been properly installed
```bash
qiime --help
```

### step 2 : ⬇️ [Download the file in the zip format](https://drive.google.com/drive/folders/1KZaWv0tQ5px65ijkcvxRsuNw_kXEVcjz?usp=sharing)

- The main Directory is [Mammal_datat](https://drive.google.com/drive/folders/1KZaWv0tQ5px65ijkcvxRsuNw_kXEVcjz?usp=sharing)
- This Folder contain all the necessary tools to perform analysis
- In the Folder Mammal_dataset:
- files names : [echidna_metadata.tsv](https://drive.google.com/file/d/190YIV1RSzE1v31S5IN7FbUzxqa8ZYO_d/view?usp=sharing) and [silva_138_16s_515-806_classifier.qza](https://drive.google.com/file/d/1M-CNVJmrXBzfhFltWm7rVsPR4XQ4PwJt/view?usp=sharing)
-  folder [raw_data](https://drive.google.com/drive/folders/1OfQqv3Hk57eTgfDQ7LeXwmahMFODur9y?usp=sharing)

---
After that follow steps describes in the [New_QIIME2_demo.ipynb]()

 [^1]:[Hongo](hkoffianderson@gmail.com)
 ## :blush:
