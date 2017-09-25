# A `bookdown` Template for TRACE Documents


This is a template for writing TRACE documents ("TRAnsparent and Comprehensive model Evaludation"), based on the supplement to 

> Grimm V, Augusiak J, Focks A, Frank B, Gabsi F, Johnston ASA, Kułakowska K, Liu C, Martin BT, Meli M, Radchuk V, Schmolke A, Thorbek P, Railsback SF. 2014. Towards better modelling and decision support: documenting model development, testing, and analysis using TRACE. *Ecological Modelling* 280: 129-139.

The original supplement is Microsoft Word format; the goal here is to allow the TRACE document that is based on analysis in R to be written following the reproducable research philosophy using Rmarkdown files.

## Background
**The following is from the first page of the original template:**

This is a template for producing TRACE documents according to:

> Grimm V, Augusiak J, Focks A, Frank B, Gabsi F, Johnston ASA, Kułakowska K, Liu C, Martin BT, Meli M, Radchuk V, Schmolke A, Thorbek P, Railsback SF. 2014. Towards better modelling and decision support: documenting model development, testing, and analysis using TRACE. *Ecological Modelling* 280: 129-139 

and

> Augusiak J, Van den Brink PJ, Grimm V. 2014. Merging validation and evaluation of ecological models to ‘evaludation’: a review of terminology and a practical approach. *Ecological Modelling* 280: 117-128. 

Before you compile a TRACE document, please read the above two publications, plus:

> Schmolke A, Thorbek P, DeAngelis DL, Grimm V. 2010. Ecological modelling supporting environmental decision making: a strategy for the future. *Trends in Ecology and Evolution* 25: 479-486.

In the template, text in < > provides instructions and explanations and should be replaced by your own text. By filling in your own text, tables, figures, and hyperlinks, and by deleting instructions and explanations, you can create your own TRACE document. 

Please keep the short explanation that is given at the begin of each TRACE element; it will remind you and readers what this element is about.

We recommend keeping the simplistic formatting of this file so TRACE documents produced by different authors not only use the same structure and terminology, but also look similar, making it easier for model users to perceive TRACE as a standard format.

TRACE documents are designed to be supplementary material provided in electronic and/or printed form to add credibility to your model and its results. Please refer in your main article or report, where you present the model and its application, to the TRACE document in the following way:

> "In the Supplementary Material, we provide a TRACE document (TRAnsparent and Comprehensive model Evaludation"; Schmolke et al. 2010; Grimm et al. 2014; Augusiak et al. 2014) containing evidence that our model was thoughtfully designed, correctly implemented, thoroughly tested, well understood, and appropriately used for its intended purpose. A summary of the TRACE document is given in Table <..>."

It is important that you refer to those publications so that model users can check whether you followed the standard defined in Grimm et al. (2014), that they understand the rationale of TRACE (Schmolke et al. 2010) and of model evaludation (Augusiak et al. 2014); it also allows the developers of TRACE to scan the literature for consistent use of TRACE, which is important for future refinements.

See also: http://cream-itn.eu/trace 

## Usage
To be added when complete.

## Requirements
The `bookdown` and `knitr` R packages; development will be easier in RStudio.