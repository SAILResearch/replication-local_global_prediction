# Replication Package for "Think locally, act globally: Improving defect and effort prediction models"

Nicolas Bettenburg, Meiyappan Nagappan, Ahmed E. Hassan  
[Proceedings of the 9th Working Conference on Mining Software Repositories (MSR '12)](http://dx.doi.org/10.1109/MSR.2012.6224300)

Abstract: Much research energy in software engineering is focused on the creation of effort and defect prediction models. Such models are important means for practitioners to judge their current project situation, optimize the allocation of their resources, and make informed future decisions. However, software engineering data contains a large amount of variability. Recent research demonstrates that such variability leads to poor fits of machine learning models to the underlying data, and suggests splitting datasets into more fine-grained subsets with similar properties. In this paper, we present a comparison of three different approaches for creating statistical regression models to model and predict software defects and development effort. Global models are trained on the whole dataset. In contrast, local models are trained on subsets of the dataset. Last, we build a global model that takes into account local characteristics of the data. We evaluate the performance of these three approaches in a case study on two defect and two effort datasets. We find that for both types of data, local models show a significantly increased fit to the data compared to global models. The substantial improvements in both relative and absolute prediction errors demonstrate that this increased goodness of fit is valuable in practice. Finally, our experiments suggest that trends obtained from global models are too general for practical recommendations. At the same time, local models provide a multitude of trends which are only valid for specific subsets of the data. Instead, we advocate the use of trends obtained from global models that take into account local characteristics, as they combine the best of both worlds.

## Bibtex

```bibtex
@INPROCEEDINGS{Bettenburg12,
author={N. Bettenburg and M. Nagappan and A. E. Hassan},
booktitle={2012 9th IEEE Working Conference on Mining Software Repositories (MSR)},
title={Think locally, act globally: Improving defect and effort prediction models},
year={2012},
pages={60-69},
doi={10.1109/MSR.2012.6224300},
ISSN={2160-1852},
month={June}
}
```

## Data and Scripts

You can download all data and R scripts used for this study [here](https://github.com/SAILResearch/replication-local_global_prediction/releases/latest)
