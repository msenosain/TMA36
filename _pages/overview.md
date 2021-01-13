---
permalink: /overview/
title: "Project overview"
---

1. [Project title](#title)
2. [Rationale](#rationale)
3. [Hypothesis](#hypothesis)
4. [Original Specific Aims](#osa)
5. [Working Specific Aims](#wsa)

## **Project title** <a name="title"></a>
Investigating early lung adenocarcinoma behavior through the integration of multiple datasets

## **Rationale** <a name="rationale"></a>
Lung adenocarcinoma is a heterogeneous group of tumors associated with dramatically different survival rates, even when detected at an early stage. LADC detected through CT screening range from indolent to aggressive, with most lethal tumors having doubling times of 50 to 150 days, while CT screen can detect tumors with doubling times >400 days. Even though the radiomics field has made great progress for early detection, the biological determinants of aggressiveness remain unclear.

## **Hypothesis** <a name="hypothesis"></a>
We hypothesize that integration of biological, clinical and radiomics data of early stage will improve the discrimination between indolent and aggressive tumors which in turn may offer novel and personalized avenues for intervention.

## **Original Specific Aims** <a name="osa"></a>
1.	To test whether early-stage ADC behavior is predicted by heterogeneity of protein expression and pathway activity in distinct cellular populations.
2.	To investigate whether differentially expressed genes in early-stage ADC are associated with distinct predicted clinical outcomes. 
3.	To integrate cellular and molecular determinants of tumor behavior together with clinical and CT imaging features and determine whether machine learning algorithms can predict behavior of early-stage ADCs.

## **Working Specific Aims** <a name="wsa"></a>
1.	To test whether ADCs with short predicted survival (SPS) have a different CyTOF-based protein expression profile compared to tumors with long predicted survival (LPS)
	* 	Done:
		*  Identify/cluster and annotate cellular populations in the samples. Further cluster each main cell type (so far this has only been done for epithelial cells).
		*  Get the cell type distribution per patient (each pt will have a profile of distribution).
		*  Get median protein expression per cell type per patient (need to rethink if this is a sensible approach).
		*  Compare indolent vs aggressive proportions/protein expression for each cell type.
		*  Do unsupervised analysis of the summarized data.
	*  To-Do:
		*  Use the SILA to reclassify patients into two groups, play with the median, IQR, and reassess the results
		*  Use SILA score as continuous variable
		*  Answer cell population bias question using the TMA
		*  Bring the context of HLA-DR across different cell types.
2.	To test whether ADCs with short predicted survival (SPS) have a different transcriptomic profile compared to tumors with long predicted survival (LPS)
	* Done:
		* Only use top variant genes (top 25%), summarize these with gene clustering algorithm.
		* Infer cell types with deconvolution algorithms (benchmark with CyTOF)
		* Infer transcription factor activity
		* Do unsupervised analysis of the previous 3.
	* To-do:
		* Ideally compare indolent vs aggressive but there are too few indolent tumors. One option could be to set a new threshold using the SILA score, or to do G+I vs P. Then compare: DEG, deconvolution results, TF. 
		* Look at the list of genes from Zhora (including collagen deposition related enzymes), EMC related, see if there is any correlation between SILA and these transcriptional programs.
		* Metabolic profiles/response, indolent vs intermediate vs aggressive (Dalton)
		* Assess epithelial markers differentially expressed in indolent vs aggressive tumors (cells of origin) (TTF1 Related with type 2 derived tumors).
3.	To test whether ADCs with short predicted survival (SPS) have a different genomic profile compared to tumors with long predicted survival (LPS)
	* Done:
		* So far, this data has been analyzed in a qualitative way (yes/no mutation) and the visualizations generated are descriptive only.
	* To-do:
		* Clonality reconstruction and phylogenetic analysis (progression of mutations by stage)
		* Validate list of genes associated with outcome from Jun’s paper.
		* Assess mutation in pathways that affect tumor behavior 
			* Stiffness, 
			* TGF beta signaling, 
			* Wnt and beta catenin pathway, 
			* notch pathway (ask JL, VQ)
			* STK11/LKB1 mutations
			* EPPK1 (Ken) (look into transcriptomic as well)
			* And more (Literature review!)
4.	To integrate biological determinants of tumor behavior as well as clinical and CT imaging features and determine whether machine learning algorithms can predict behavior of early-stage ADCs
	* Done:
		* MOFA: CyTOF + RNA Seq + mutations
	* To-do:
		* Integrate similar data sets only (e.g. RNA and WES, CyTOF and MxIF…)
