# DeMAND-algorithm
The Drug Mechanism of Action Algorithm Developed in the Califano Lab

## Introduction

The DeMAND algorithm is a method to elucidate drug mechanism of action by detecting which interactions in a network are dysregulated by the drug. Given gene expression profiles before and after the drug pertubation, as well as a molecular interaction network, DeMAND detects which nodes (i.e. proteins or genes) have dysregulated edges after the pertubation.

The DeMAND algorithm was developed in the lab of Andrea Califano. The first authors are Jung Hoon Woo and Yishai Shimoni. The corresponding authors are Mukesh Bansal and Andrea Califano. For further information about the algorithm, please see the included guide, and the original paper https://www.ncbi.nlm.nih.gov/pubmed/26186195.

The original version of DeMAND was written by Jung Hoon Woo. A faster version (DeMANDfast) was written by Alexander Lachmann. In my benchmark analysis, DeMANDfast is about 3-10 times faster than DeMAND, and the results are nearly identical.
