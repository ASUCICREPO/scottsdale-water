## Disclaimers
Customers are responsible for making their own independent assessment of the information in this document.

This document:

(a) is for informational purposes only,

(b) references AWS product offerings and practices, which are subject to change without notice,

(c) does not create any commitments or assurances from AWS and its affiliates, suppliers or licensors. AWS products or services are provided "as is" without warranties, representations, or conditions of any kind, whether express or implied. The responsibilities and liabilities of AWS to its customers are controlled by AWS agreements, and this document is not part of, nor does it modify, any agreement between AWS and its customers, and

(d) is not to be considered a recommendation or viewpoint of AWS.

Additionally, you are solely responsible for testing, security and optimizing all code and assets on GitHub repo, and all such code and assets should be considered:

(a) as-is and without warranties or representations of any kind,

(b) not suitable for production environments, or on production or other critical data, and

(c) to include shortcuts in order to support rapid prototyping such as, but not limited to, relaxed authentication and authorization and a lack of strict adherence to security best practices.

All work produced is open source. More information can be found in the GitHub repo.

1  Introduction

This document explains how eCognition was used to
automate landscape classification and provides the script needed to do this.

2 eCognition

eCognition makes a radical departure from conventional
approaches to data analysis due to its ability to emulate the human mind's
cognitive powers and fuse geospatial input data. Using patented segmentation
and classification processes, eCognition developed a robust method of rendering
knowledge in a semantic network. The technology examines pixels/ points not in
isolation, but in context. It builds up a picture iteratively, recognizing
groups of pixels as objects. Just like the human mind, it uses the color,
shape, texture and size of objects as well as their context and relationships
to draw the same conclusions and inferences as an experienced analyst, but
adding the advantages of automation and standardization. Though somewhat
simplified, the following example illustrates the basic principles.

3 What is needed to run the script?

The following things are needed to run the script in
Ecognition.

1.    Red Green Blue (RGB) image
2.    LIDAR Data (Light Detection and Ranging) (See appendix for point clouds)
3.    Infrared

Load the following datasets into Ecognition and run the
script. It will output the surface area of the different types of landscapes.

4 Results from running the script

This shows an example output from a randomly ingested
dataset.
