.. hello documentation master file, created by
   sphinx-quickstart on Sun Apr 29 11:38:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Software Requirements Specification for OMG Version 0.1
=================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


+------------------------+------------+
|      Oh My Genes       |Version 1.0 | 
|                        |            |          
+========================+============+
|SRS                     | 2018.4.28  | 
+------------------------+------------+
|               OMG SRS 1.0           | 
+------------------------+------------+




1. Introduction: 
===============
1.1 Purpose:
-----------------
The computer quickly get differentially expressed genes from the gene expression file that scientists 
uploaded To free the scientists from the tedious data calculation, so that they have more energy to engage in 
scientific research, 
so as to improve the experimental efficiency comprehensively.

1.2 Terminology:
-----------------
Transaction Processing 
Data Processing

1.3 Domain knowledge:
-----------------

Control sample
~~~~~~~~~~~~~~~~~~~~~~

A cell sample prepared in its normal condition. 

Treatment sample 
A cell sample treated by special chemicals£¬ or in which some genes are altered.
-Differentially expressed genes 
The genes which have significantly different expression levels between two samples. 
Up-regulation
a gene is said to be up-regulated if it has higher expression in treatment than in control.
logFC - log fold change of gene expression.
log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level from a control sample.

1.4 Overview:
-----------------
The application has a simple interface with only one button. Our scientists uploaded a plain text file containing 
two samples of gene expression levels representing two experimental conditions. After accepting the document, 
the software will return a table and the genes differentially expressed genes of scatter plot, the genes of the x axis
 is the control sample, the y axis is to process the sample. Given an invalid gene expression,
 the web application will return a page informing the user to provide the correct format.

.. image:: dataflow.jpg

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
