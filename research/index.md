---
layout: page
title: Research
excerpt: "research"
modified: 2021-12-28
---

My research interests include machine learning, big and high-dimensional data, and computational statistics. Essentially, I am very intrigued and amazed by the possibilities of big data and the questions it can answer.

I am very fortunate to have had [Hua Zhou](http://hua-zhou.github.io/) and [Eric Chi](www.ericchi.com) as my co-advisers.  For the first research project in my dissertation, I derived and compared different algorithms for estimating the constrained lasso ([James et al., 2013](http://www-bcf.usc.edu/~gareth/research/PAC.pdf)), including a novel derivation of an efficient solution path algorithm.  As its name suggests, the constrained lasso augments the standard lasso (Tibshirani, 1996) with linear equality and inequality constraints, providing an additiional vehicle for incorporating prior knowledge into the solution (such as monotonicity or non-negativity of the lasso coefficients).

My other research projects focused on a convex formulation of clustering that has been studied recently ([Chen et al., 2015](http://journals.plos.org/ploscompbiol/article?id=10.1371%2Fjournal.pcbi.1004228); [Chi and Lange, 2015](http://www.tandfonline.com/doi/abs/10.1080/10618600.2014.948181#.VHVPyt5WVzo)).  Clustering is a fundamental unsupervised learning technique that aims to discover groups of objects in a dataset. Biclustering extends clustering to two dimensions where both observations and variables are grouped concurrently, such as simultaneously clustering cancerous tumors and genes or documents and words. Triclustering is then the natural extension of clustering to three dimensions where the data are organized in a three-dimensional array, or tensor.  We develop and study a convex formulation of triclustering that generates an entire solution path of triclustering results as a function of only one tuning parameter, which alleviates the need to specify the number of clusters a priori.  Additionally, convex triclustering has several nice properties, such as always returning the unique global minimum regardless of the initialization, and its solutions are stable with respect to small changes in the data.

### Publications
- Chi, E., **Gaines, B**., Sun, W. W., Zhou, H., and Yang, J. (2020). "[Provable Convex Co-clustering of Tensors](https://jmlr.org/papers/volume21/18-155/18-155.pdf)," *Journal of Machine Learning Research*, 21(214), 55-61. [[BibTeX](http://brgaines.github.io/research/chiEtAll20.bib)]

- Parkinson, L., **Gaines, B**., and Nollens, H. (2019). "Effect of Nutrient Enema on Serum Nutrient Concentrations in White-Spotted Bamboo Sharks (Chiloscyllium Plagiosum)," *Journal of Zoo and Wildlife Medicine*, 50(1), 55-61. [[BibTeX](http://brgaines.github.io/research/parkinsonGainesNollens19.bib)]

- **Gaines, B**., Kim, J., and Zhou, H. (2018). "[Algorithms for Fitting the Constrained Lasso](https://www.tandfonline.com/doi/full/10.1080/10618600.2018.1473777)," *Journal of Computational and Graphical Statistics*, 27(4), 861-871. [[BibTeX](http://brgaines.github.io/research/gainesKimZhou18.bib)] [[MATLAB toolbox](http://hua-zhou.github.io/SparseReg/)] [[Julia package](https://github.com/Hua-Zhou/ConstrainedLasso.jl)]

- Jarrett, M., Bailey, K., Messenger, K., Prange, T., **Gaines, B**., and Posner, L. (2018). “[Recovery of Horses from General Anesthesia After Induction with Propofol and Ketamine Versus Midazolam and Ketamine](https://www.ncbi.nlm.nih.gov/pubmed/29911938),” *Journal of the American Veterinary Medical Association*, 253(1), 101-107. [[BibTeX](http://brgaines.github.io/research/jarrettEtAl18.bib)]

- Balko, J., Wilson, S., Lewbart, G., **Gaines, B**., and Posner, L. (2017). “[Propofol as an Immersion Anesthetic and in a Minimum Anesthetic Concentration (MAC) Reduction Model In Goldfish (Carassius Auratus)](https://www.ncbi.nlm.nih.gov/pubmed/28363074),” *Journal of Zoo and Wildlife Medicine*, 48(1), 48-54. [[BibTeX](http://brgaines.github.io/research/balkoEtAl17.bib)]

- Muller, C., **Gaines, B**., et al. (2016). “[Evaluation of Clinical Metrology Instrument in Dogs with Osteoarthritis](https://www.ncbi.nlm.nih.gov/pubmed/26971876).” *Journal of Veterinary Internal Medicine*, 30(3), 836-846. [[BibTeX](http://brgaines.github.io/research/mullerGaines16.bib)]

- Jarque, A., and **Gaines, B**. (2012). "[Regulation and the Composition of CEO Pay](https://www.richmondfed.org/publications/research/economic_quarterly/2012/q4/pdf/jarque.pdf)." *Federal Reserve Bank of Richmond Economic Quarterly*, 98(4), 309-348. [[BibTeX](http://brgaines.github.io/research/jarqueGaines12.bib)]

- Courtois, R., **Gaines, B**, and Hatchondo, J.C. (2010). "[Is a New Asset Bubble Emerging in Certain Markets?](https://www.richmondfed.org/-/media/richmondfedorg/publications/research/economic_brief/2010/pdf/eb_10-02.pdf)." *Federal Reserve Bank of Richmond Economic Brief*, 10(2). [[BibTeX](http://brgaines.github.io/research/courtoisGainesHatchondo2010.bib)]


### Other Articles
- **Gaines, B**. (2022). "[Accuracy vs. Interpretability? With Generalized Additive Models (GAMs), You Can Have Both](https://blogs.sas.com/content/subconsciousmusings/2022/03/24/accuracy-versus-interpretability-with-generalized-additive-models-gams-you-can-have-both/)." March 24.

- **Gaines, B**. (2022). "[How to Train Generalized Additive Models (GAMs) in Model Studio](https://communities.sas.com/t5/SAS-Communities-Library/How-to-Train-Generalized-Additive-Models-GAMs-in-Model-Studio/ta-p/793597)." March 24.

- **Gaines, B**. (2020). "[How to Develop SAS Code to Train a Deep Learning Model for Image Classification](https://communities.sas.com/t5/SAS-Communities-Library/How-to-Develop-SAS-Code-to-Train-a-Deep-Learning-Model-for-Image/ta-p/663322#)." June 23.

- **Gaines, B**. (2020). "[Writing Custom SAS® Studio Tasks That Use CAS Actions for Advanced Analytics](https://communities.sas.com/t5/SAS-Communities-Library/Writing-Custom-SAS-Studio-Tasks-That-Use-CAS-Actions-for/tac-p/658386)." June 8.

- **Gaines, B**. (2020). "[Tips for Writing Custom SAS® Studio Tasks That Use CAS Actions for Advanced Analytics](https://www.sas.com/content/dam/SAS/support/en/sas-global-forum-proceedings/2020/4376-2020.pdf)." In _Proceedings of the SAS Global Forum 2020 Conference_. Cary, NC: SAS Institute Inc. [[BibTeX](http://brgaines.github.io/research/gainesSGF20.bib)] [[Examples](https://github.com/sascommunities/sas-global-forum-2020/tree/master/papers/4376-2020-Gaines)]

- **Gaines, B**. (2019). "[Organizing a Successful Local Career Fair](https://magazine.amstat.org/blog/2019/07/01/careerfair/)." _Amstat News_, 16-17.

* **Gaines, B**. (2019). "[Learning Data Science with SAS® University Edition and JupyterLab](https://www.sas.com/content/dam/SAS/support/en/sas-global-forum-proceedings/2019/3133-2019.pdf)." In _Proceedings of the SAS Global Forum 2019 Conference_. Cary, NC: SAS Institute Inc. [[BibTeX](http://brgaines.github.io/research/gainesSGF19.bib)] [[Examples](https://github.com/sascommunities/sas-global-forum-2019/tree/master/3133-2019-Gaines)]

* **Gaines, B**. (2017). "[Penalized Estimation in Statistics: Applications & Algorithms](http://www.lib.ncsu.edu/resolver/1840.20/34690) (Doctoral dissertation)." North Carolina State University.

* **Gaines, B**., and Fine, A. (2016). "Multilevel Modeling of Product Sales Data." Unpublished internal technical report, MaxPoint Interactive.

* **Gaines, B**. (2013). "Anomaly Detection via the Graph Scan Statistic." Unpublished written preliminary exam, North Carolina State University.

* **Gaines, B**. (2013). "Anomaly Detection using Multiple Scales of the Graph Scan Statistic: A Simulation Study." Unpublished written preliminary exam, North Carolina State University.