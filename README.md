# SCRMshaw
Improved accuracy of supervised CRM discovery with interpolated Markov models and cross-species comparison

Majid Kazemian, Qiyun Zhu, Marc S. Halfon and Saurabh Sinha

 

Motif-blind, genome-wide discovery of cis-regulatory modules in Drosophila and mouse

Miriam R. Kantorovitz, Majid Kazemian, Sarah Kinston, Diego Miranda-Saavedra, Qiyun Zhu, Gene E. Robinson, Berthold Gottgens, Marc S. Halfon, and Saurabh Sinha

 

 

SCRMshaw is a genome-wide CRM prediction program, described and used in the following papers: Majid Kazemian et al 2011 and Miriam R. Kantorovitz and MajidKazemian et al 2009. For details about the methods and procedures of this program please see the METHOD part of these two papers. The SCRMshaw program learns parameters from a list of CRMs that regulates the same spatial/temporal gene expression pattern, and predicts CRMs with similar functionality genome-wide. This verson of SCRMshaw program is designed for predicting CRMs in the genome sequence of model/non-model species given the known CRMs provided by users. Users can also choose three different scoring schemes as described in the papers to predict CRMs: IMM, PAC and HexMCD. To use this program, please download the source code file below, and go through the README.txt file for detailed instructions. You can also download the CRM training sets used in Majid Kazemian et al 2011 paper: 1) crm.dmel.tar.gz is the Dmel training sets; 2) crm.dros.tar.gz is the multiple drosophila species training sets.

 Download code from here: http://halfonlab.ccr.buffalo.edu/scrmshaw.html
 Dmel CRM training sets: crms.dmel.tar.gz
 Multiple drosophila species CRM training sets: crms.dros.tar.gz
 Pipeline for enrichment test: enrich.pipeline.tar.gz
