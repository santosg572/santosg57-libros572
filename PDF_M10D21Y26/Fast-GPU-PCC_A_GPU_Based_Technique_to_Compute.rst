Fast-GPU-PCC: A GPU Based Technique to Compute Pairwise Pearson’s Correlation Coefficients for Big fMRI Data - 2018
======================================================

Abstract: Functional Magnetic Resonance Imaging (fMRI) is a non-invasive brain imaging technique
which is heavily used for studying brain’s functional activities in the past few years. A popular
measure for capturing functional connectivities between brain regions is Pearson’s correlation
coefficient. fMRI data consists of huge number of small elements called voxels. Computing pairwise
correlation coefficient between them using traditional CPU based technique is time consuming. In this
paper, we propose a GPU-based algorithm called Fast-GPU-PCC for computing pairwise Pearson’s
correlation coefficient. Based on symmetric property of Pearson’s correlation, this approach returns
N(N − 1)/2 correlation coefficients located at strictly upper/lower triangle part of correlation matrix.
Storing correlations in an 1-dimensional array with the order as proposed in this paper is useful for
further usage. Our approach is based on matrix multiplication and reordering its result which is
performed on GPU. We performed some experiments on real and synthetic fMRI data for different
number of voxels and varying length of time series. The proposed approach outperformed two other
GPU-based techniques as well as the sequential version of computing correlation coefficient on CPU.
We show that Fast-GPU-PCC runs 62.2 × faster than CPU-based version and 2.21 × and 4.05 × faster
than two other GPU-based techniques. The implementation of our approach will be available as
GPL license on GitHub portal of our lab (https://github.com/PCDS) after the paper is accepted for
publication.

