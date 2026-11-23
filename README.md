# Early Sepsis Detection: Research Paper and Reproducibility Notebook

This repository accompanies a retrospective research paper on hourly sepsis warning using the PhysioNet/Computing in Cardiology Challenge 2019 dataset. The study evaluates temporal convolutional and gradient boosting models, stacking, cross source performance, and alert burden against the first observed benchmark label transition.

## Research materials

- [`sepsis-tcn-paper-reconstruction.ipynb`](sepsis-tcn-paper-reconstruction.ipynb) contains the numbered, explanatory analysis notebook and cells for reviewing the archived model results.

The notebook is provided as research code associated with a manuscript. Its presence does not mean that every analysis in the paper can be regenerated from this file alone. Some archived review analyses have summary tables but lack the original row level predictions or training inputs needed for independent recomputation. The notebook describes these limits in context.

## Study scope

The prediction target is the first positive label in the PhysioNet 2019 benchmark. The labels are derived from the Challenge definition and are not independent adjudications of clinical onset. Site A is used for model development and policy selection, with Site B held for evaluation in the primary analysis. The study reports discrimination together with alert timing, workload, and outcomes that remain unknown because follow up ends.

## Data and execution

The source dataset is publicly distributed through [PhysioNet Challenge 2019](https://physionet.org/content/challenge-2019/1.0.0/) and its [Kaggle mirror](https://www.kaggle.com/datasets/farjanayesmin/the-physionet-challenge-2019-dataset). It is not included in this repository. Follow the notebook's setup cells and the source dataset terms before running the full training pipeline. Full training can require substantial compute and may take more than one notebook session.

To inspect the archived paper results, place `sepsis_review_full_A_to_B.zip` beside the notebook and run the archive review cells. This archive is a separate study artifact and is not included here.

## Paper status

This repository supports a manuscript in preparation. It is not a published paper or a claim of clinical validation. Author affiliations, ethics and consent details, funding, competing interests, contributions, and public analysis archive links must be completed or verified by the authors before submission.

## Citation

A final citation will be added when the manuscript has been accepted or published. Until then, please cite the repository URL and note that the associated manuscript is in preparation.
