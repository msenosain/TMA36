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


|     Antigen           |     Isotope    |     Working conc (ug/ml)    |     Dilution    |     Vol in 100 ul rx    |     Level    |     Clone         |     Source       |     Catalog #    |
|-----------------------|----------------|-----------------------------|-----------------|-------------------------|--------------|-------------------|------------------|------------------|
|     EpCAM             |     141-Pr     |                             |     1:1600      |     0.0625              |     S        |     9C4           |     Fluidigm     |     3141006B     |
|     c caspase3        |     142-Nd     |                             |     1:400       |     0.25                |     I        |     D3E9          |     Fluidigm     |     3142004A     |
|     * TP53            |     143-Nd     |     50                      |     1:200       |     0.25                |     I        |     DO-7          |     Biolegend    |     645802       |
|     HLA-ABC           |     144-Nd     |                             |     1:800       |     0.125               |     S        |     W6/32         |     Fluidigm     |     3144017B     |
|     CD31              |     145-Nd     |                             |     1:200       |     0.5                 |     S        |     WM59          |     Fluidigm     |     3145004B     |
|     Thioredoxin       |     146-Nd     |                             |     1:800       |     0.125               |     I        |     2G11/TRX      |     Fluidigm     |     3146016B     |
|     b-CAT             |     147-Sm     |                             |     1:800       |     0.125               |     I        |     D10A8         |     Fluidigm     |     3147005A     |
|     HER2              |     148Nd      |                             |     1:400       |     0.25                |     S        |     29D8          |     Fluidigm     |     3148011A     |
|     p-STAT6           |     149-Sm     |                             |     1:200       |     0.5                 |     I        |     18/P-Stat6    |     Fluidigm     |     3149004A     |
|     p-stat5           |     150-Nd     |                             |     1:200       |     0.5                 |     I        |     Y694          |     Fluidigm     |     3150005A     |
|     * TTF1            |     151-Eu     |     100                     |     1:200       |     0.5                 |     I        |     D2E8          |     CST          |     12373        |
|     p-AKT             |     152-Sm     |                             |     1:400       |     0.25                |     I        |     D9E           |     Fluidigm     |     3152005A     |
|     * ki67            |     153-Eu     |     100                     |     1:200       |     0.5                 |     I        |     ki67          |     Biolegend    |     350523       |
|     CD45              |     154-Sm     |                             |     1:800       |     0.125               |     S        |     HI30          |     Fluidigm     |     3154001B     |
|     CD56/NCAM         |     155-Gd     |                             |     1:100       |     1                   |     S        |     B159          |     Fluidigm     |     3155008B     |
|     Vimentin          |     156-Gd     |                             |     1:800       |     0.125               |     I        |     RV202         |     Fluidigm     |     3156023A     |
|     p-STAT3           |     158-Gd     |                             |     1:200       |     0.5                 |     I        |     Y705          |     Fluidigm     |     3158005A     |
|     * CD4             |     159-Tb     |     100                     |     1:400       |     0.25                |     S        |     RPA T4        |     Biolegend    |     300502       |
|     * MDM2            |     160-Gd     |     100                     |     1:200       |     0.5                 |     I        |     Polyclonal    |     Abcam        |     ab38618      |
|     * Cytokeratin     |     161-Dy     |     50                      |     1:400       |     0.25                |     I        |     C-11          |     Abcam        |     ab7753       |
|     * MET             |     162-Dy     |     50                      |     1:300       |     0.32                |     S        |     L6E7          |     CST          |     8741         |
|     * TP63            |     163-Dy     |     ?                       |     1:200       |     0.5                 |     I        |     W15093A       |     Biolegend    |     687202       |
|     CK7               |     164-Dy     |                             |     1:400       |     0.25                |     I        |     RCK105        |     Fluidigm     |      3164020A    |
|     * total EGFR      |     165-Ho     |     50                      |     1:250       |     0.4                 |     S        |     AY13          |     Biolegend    |     352902       |
|     CD44              |     166-Er     |                             |     1:800       |     0.125               |     S        |     BJ18          |     Fluidigm     |     3166001B     |
|     p-ERK             |     167-Er     |                             |     1:400       |     0.25                |     I        |     D13.14.4E     |     Fluidigm     |     3167005A     |
|     CD8               |     168-Er     |                             |     1:200       |     0.5                 |     S        |      RPA-T8       |     Fluidigm     |     3168002B     |
|     CD24              |     169-Tm     |                             |     1:200       |     0.5                 |     S        |     ML5           |     Fluidigm     |     3169004B     |
|     CD3e              |     170-Yb     |                             |     1:400       |     0.25                |     S        |     SP34-2        |     Fluidigm     |     3170007B     |
|     * CD11b           |     171-Yb     |     50                      |     1:400       |     0.25                |     S        |     ICRF44        |     Biolegend    |     301337       |
|     p-S6              |     172-Yb     |                             |     1:400       |     0.5                 |     I        |     N7-548        |     Fluidigm     |     3172008A     |
|     HLA-DR            |     174-Yb     |                             |     1:400       |     0.5                 |     S        |     L243          |     Fluidigm     |     3172008A     |
|     CD274/PDL1        |     175-Lu     |                             |     1:800       |     0.125               |     S        |     29E.2A3       |     Fluidigm     |     3175017B     |
|     Histone H3        |     176-Yb     |                             |     1:200       |     0.5                 |     I        |     D1H2          |     Fluidigm     |     3176016A     |


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