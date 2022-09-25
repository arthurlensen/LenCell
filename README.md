# LenCell

This repository holds a macro written by Arthur Lensen during a 6 months internship in the Mostowy lab (Sept 2021-Feb 2022) under the supervision of Margarida Castro Gomes Spencer.

This macro applies a bandpass filter to microscopy images, in order to clean the image and count the number of fluorescent "blobs" in it. It was designed to count neutrophils in zebrafish larvae hindbrain or full body, in single planes or Z-stacks datasets, but it can likely be modified to work on other types of images.
The macro can be optimized using an "optimization" datasets of 5-10 single planes images, for which the number of blobs was hand counted. Tha macro will then try to find parameters able to provide results the closest possible (in average) to the handcounted results.
