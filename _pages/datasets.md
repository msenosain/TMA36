---
permalink: /datasets/
title: "Datasets documentation"
---

1. [CyTOF](#cytof)
2. [RNA Seq](#rna)
3. [WES](#wes)
4. [Single cell RNA Seq](#scrna)
5. [MxIF from UC Davis](#mxifucd)
6. [Radiomics](#rad)
7. [Clinical data](#clin)

## **CyTOF** <a name="cytof"></a>
1. **General info:** Mass Cytometry or CyTOF is a variation of flow cytometry in which antibodies are labeled with heavy metal ion tags rather than fluorochromes. Our antibody panel include the following protein markers:

|    <br>Antigen           |    <br>Isotope    |    <br>Working conc (ug/ml)    |    <br>Dilution    |    <br>Vol in 100 ul rx    |    <br>Level    |    <br>Clone         |    <br>Source       |    <br>Catalog #    |
|--------------------------|-------------------|--------------------------------|--------------------|----------------------------|-----------------|----------------------|---------------------|---------------------|
|    <br>EpCAM             |    <br>141-Pr     |    <br>                        |    <br>1:1600      |    <br>0.0625              |    <br>S        |    <br>9C4           |    <br>Fluidigm     |    <br>3141006B     |
|    <br>c caspase3        |    <br>142-Nd     |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>I        |    <br>D3E9          |    <br>Fluidigm     |    <br>3142004A     |
|    <br>* TP53            |    <br>143-Nd     |    <br>50                      |    <br>1:200       |    <br>0.25                |    <br>I        |    <br>DO-7          |    <br>Biolegend    |    <br>645802       |
|    <br>HLA-ABC           |    <br>144-Nd     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>S        |    <br>W6/32         |    <br>Fluidigm     |    <br>3144017B     |
|    <br>CD31              |    <br>145-Nd     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>S        |    <br>WM59          |    <br>Fluidigm     |    <br>3145004B     |
|    <br>Thioredoxin       |    <br>146-Nd     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>I        |    <br>2G11/TRX      |    <br>Fluidigm     |    <br>3146016B     |
|    <br>b-CAT             |    <br>147-Sm     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>I        |    <br>D10A8         |    <br>Fluidigm     |    <br>3147005A     |
|    <br>HER2              |    <br>148Nd      |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>S        |    <br>29D8          |    <br>Fluidigm     |    <br>3148011A     |
|    <br>p-STAT6           |    <br>149-Sm     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>18/P-Stat6    |    <br>Fluidigm     |    <br>3149004A     |
|    <br>p-stat5           |    <br>150-Nd     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>Y694          |    <br>Fluidigm     |    <br>3150005A     |
|    <br>* TTF1            |    <br>151-Eu     |    <br>100                     |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>D2E8          |    <br>CST          |    <br>12373        |
|    <br>p-AKT             |    <br>152-Sm     |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>I        |    <br>D9E           |    <br>Fluidigm     |    <br>3152005A     |
|    <br>* ki67            |    <br>153-Eu     |    <br>100                     |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>ki67          |    <br>Biolegend    |    <br>350523       |
|    <br>CD45              |    <br>154-Sm     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>S        |    <br>HI30          |    <br>Fluidigm     |    <br>3154001B     |
|    <br>CD56/NCAM         |    <br>155-Gd     |    <br>                        |    <br>1:100       |    <br>1                   |    <br>S        |    <br>B159          |    <br>Fluidigm     |    <br>3155008B     |
|    <br>Vimentin          |    <br>156-Gd     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>I        |    <br>RV202         |    <br>Fluidigm     |    <br>3156023A     |
|    <br>p-STAT3           |    <br>158-Gd     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>Y705          |    <br>Fluidigm     |    <br>3158005A     |
|    <br>* CD4             |    <br>159-Tb     |    <br>100                     |    <br>1:400       |    <br>0.25                |    <br>S        |    <br>RPA T4        |    <br>Biolegend    |    <br>300502       |
|    <br>* MDM2            |    <br>160-Gd     |    <br>100                     |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>Polyclonal    |    <br>Abcam        |    <br>ab38618      |
|    <br>* Cytokeratin     |    <br>161-Dy     |    <br>50                      |    <br>1:400       |    <br>0.25                |    <br>I        |    <br>C-11          |    <br>Abcam        |    <br>ab7753       |
|    <br>* MET             |    <br>162-Dy     |    <br>50                      |    <br>1:300       |    <br>0.32                |    <br>S        |    <br>L6E7          |    <br>CST          |    <br>8741         |
|    <br>* TP63            |    <br>163-Dy     |    <br>?                       |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>W15093A       |    <br>Biolegend    |    <br>687202       |
|    <br>CK7               |    <br>164-Dy     |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>I        |    <br>RCK105        |    <br>Fluidigm     |    <br> 3164020A    |
|    <br>* total EGFR      |    <br>165-Ho     |    <br>50                      |    <br>1:250       |    <br>0.4                 |    <br>S        |    <br>AY13          |    <br>Biolegend    |    <br>352902       |
|    <br>CD44              |    <br>166-Er     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>S        |    <br>BJ18          |    <br>Fluidigm     |    <br>3166001B     |
|    <br>p-ERK             |    <br>167-Er     |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>I        |    <br>D13.14.4E     |    <br>Fluidigm     |    <br>3167005A     |
|    <br>CD8               |    <br>168-Er     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>S        |    <br> RPA-T8       |    <br>Fluidigm     |    <br>3168002B     |
|    <br>CD24              |    <br>169-Tm     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>S        |    <br>ML5           |    <br>Fluidigm     |    <br>3169004B     |
|    <br>CD3e              |    <br>170-Yb     |    <br>                        |    <br>1:400       |    <br>0.25                |    <br>S        |    <br>SP34-2        |    <br>Fluidigm     |    <br>3170007B     |
|    <br>* CD11b           |    <br>171-Yb     |    <br>50                      |    <br>1:400       |    <br>0.25                |    <br>S        |    <br>ICRF44        |    <br>Biolegend    |    <br>301337       |
|    <br>p-S6              |    <br>172-Yb     |    <br>                        |    <br>1:400       |    <br>0.5                 |    <br>I        |    <br>N7-548        |    <br>Fluidigm     |    <br>3172008A     |
|    <br>HLA-DR            |    <br>174-Yb     |    <br>                        |    <br>1:400       |    <br>0.5                 |    <br>S        |    <br>L243          |    <br>Fluidigm     |    <br>3172008A     |
|    <br>CD274/PDL1        |    <br>175-Lu     |    <br>                        |    <br>1:800       |    <br>0.125               |    <br>S        |    <br>29E.2A3       |    <br>Fluidigm     |    <br>3175017B     |
|    <br>Histone H3        |    <br>176-Yb     |    <br>                        |    <br>1:200       |    <br>0.5                 |    <br>I        |    <br>D1H2          |    <br>Fluidigm     |    <br>3176016A     |
Table 1. Antibody panel for lung adenocarcinoma. * In-house conjugated antibodies. S = Surface, I = Intracellular


2. **Description of data files:**
	1. Raw data: FCS files
		* 71 Patient samples
		* 20 (?) running controls (A549 + Ramos)
		* X validation cell lines

	2. Processed data: CSV files
		* 	CSV file with all patient data concatenated and annotation columns for cell types and sub cell types and ptID column
		*  CSV file with all control data concatenated and ID column
		*  CSV file with all validation cell lines concatenated and ID column

3. **Location:**

## **RNA Seq** <a name="rna"></a>
1. **General info:** NGS transcriptomic data. This data set has been pre-processed by Shillin Zhao.
2. **Description of data files:**
	1. Raw data: FASTQ files
		* 	78 samples (X from fresh frozen tissue, Y from single cell suspension, Z patients with overlapping data)
	2. Processed data (align to Hg38): CSV files
		* 	Raw counts
		* 	FPKM normalized counts

3. **Location:**

## **WES** <a name="wes"></a>
1. **General info:** Twist Whole Exome Sequencing data, NGS genomic data. This data set has been pre-processed by Shillin Zhao.
2. **Description of data files:**
	1. Raw data: FASTQ files
		* 	58 tumors and their matching normal tissue controls
	2. Processed data: MAF file
		* 	Mutation data for 58 patients
3. **Location:**

## **Single cell RNA Seq** <a name="scrna"></a>
1. **General info:** NGS single cell transcriptomic data. Platform used for library prep was 10X genomics 5’. This data set has been pre-processed by Shillin Zhao and VANTAGE.
2. **Description of data files:**
	1. Raw data: FASTQ files
		* 	16 samples of “Good” and “Poor” CANARY prognosis.
	2. Processed data:
		* 	16 matrices with raw counts (rows are cells, columns are genes) 
3. **Location:**

## **MxIF from UC Davis** <a name="mxifucd"></a>
1. **General info:** This data was acquired and processed by our MCL grant collaborators in UC Davis, Alexander Borowsky team.
	* Data for 93 patients with duplicates. 2 TMA blocks with 186 punches + controls.
	* Antibody panels
	* 
| Panel 1                    | Panel 2                     |
|---------|------------------|---------|-------------------|
| CD3     | Lymphocytes      | CD3     | Lymphocytes       |
| CD20    | B cells          | CD68    | Macrophages       |
| HLA-DR  | MHC-II           | CKs     | Epithelial cells  |
| FOX-P3  | T regs           | PDL1    | IC protein        |
| CKs     | Epithelial cells | PD1     | IC protein        |
| Ki67    | Proliferation    | CD8     | Cytotoxic T cells |


2. **Description of data files:**
	1. Raw data:
	2. Processed data: 
3. **Location:**


## **Radiomics** <a name="rad"></a>
1. **General info:** This data set is composed by the raw CT scans, the HealthMyne radiomic features, CANARY prognosis predictions and SILA scores. Khushbu Patel is the current person in charge.
2. **Description of data files:**
	1. Raw data:
		* 	92 CT scans
	2. Processed data: CSV files
		* 	HealthMyne radiomic features 
		*  CANARY + SILA scores
3. **Location:**