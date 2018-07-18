<img src="https://sites.google.com/site/adambmantz/_/rsrc/1425929804653/work/contours/wtg4_w.png" width=30%>

This repository contains plain-text representations of parameter confidence contours from cosmology papers. Things will be added if/when I feel like it.

This is a repository for *contours*, not Markov chains. The idea is to facilitate making quick plots to compare published results, not to re-weight, resample or otherwise fiddle with those results.

Forking and pull-requesting additions is welcome. There is no standard required format, but please observe the following guidelines:
* contours should be provided as plain text, not binary
* collect contours from a given paper in a directory whose name
  * identifies the first author or collaboration unambiguously, and
  * specifies the [arxiv](https://arxiv.org/) reference.
* provide a README file in that directory that
  * clearly states what figure each set of contours is from, and which set of contours within the figure (or what section of the paper to refer to if the contours in question do not appear in a figure)
  * clearly states the origin of the contours (contributed by the original author, extracted from the figure, computed from publicly released Markov chains, etc.)
  * identifies the contributor, if not the first/corresponding author of the paper
  * explains the format of the file encoding the contours, if not obvious
  * provides any other information that would be helpful. It isn't necessary to exhaustively note the cosmological model being fit, what priors were used, etc., provided that information is available from the referenced paper. But, e.g., explicitly stating the confidence levels would be nice.
