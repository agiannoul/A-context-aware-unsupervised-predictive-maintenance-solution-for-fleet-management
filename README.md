# A context aware unsupervised predictive maintenance solution for fleet management

## Methods:
TranAD folder : **TranAD** method. (pytorch library is requiered to run)

HybridTest folder: **2Stage** method. In order to run 2Stage method, you will need to use our version of Grand package, which is provided under the grand folder.

ClusterJoint folder: **ClusterJoint** method in paper.

KR_TEST folder: distance-based outlier detection method (brute force python implementation of MCOD, you can find faster implementation in java here: https://infolab.usc.edu/Luan/Outlier/) reffered as **DOD** in paper.

test_grand folder: **Grand** method. Group Anomaly Detection algotrithm used in paper as baseline.

Each folder contains a README file fo further explaination of the parameters and methods.

## Install modified grand package (before run any experiment)

GrandPackage folder contains the modified library of Grand method.

Install the package inside GrandPackage/ folder using 
```
pip install .
```
or 
```
pip3 install .
```

## Fleet dataset construction (Turbofan C-MPAS data)

In CreateFleetDataset folder are the raw data and four notebooks to produce a fleet dataset using them.

## Final cost Results

Use showBestCost.py in order to plot the lowest cost achived by the methods used in expiriements


# Reference

```
@Article{Giannoulidis2023,
author={Giannoulidis, Apostolos
and Gounaris, Anastasios},
title={A context-aware unsupervised predictive maintenance solution for fleet management},
journal={Journal of Intelligent Information Systems},
year={2023},
month={Apr},
day={01},
volume={60},
number={2},
pages={521-547},
issn={1573-7675},
doi={10.1007/s10844-022-00744-2},
url={https://doi.org/10.1007/s10844-022-00744-2}
}


```
