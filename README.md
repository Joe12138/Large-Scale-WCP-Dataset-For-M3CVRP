# Large-Scale-WCP-Dataset-For-M3CVRP

This is the code for the paper "Region-Focused Memetic Algorithms With Smart Initialization for Real-World Large-Scale Waste Collection Problems" accepted by IEEE TEVC.

Please use this bibtex if you use this repository in your work:

```
@ARTICLE{lan2022region,
  author={Lan, Wenxing and Ye, Ziyuan and Ruan, Peijun and Liu, Jialin and Yang, Peng and Yao, Xin},
  journal={IEEE Transactions on Evolutionary Computation}, 
  title={Region-Focused Memetic Algorithms With Smart Initialization for Real-World Large-Scale Waste Collection Problems}, 
  year={2022},
  volume={26},
  number={4},
  pages={704-718},
  doi={10.1109/TEVC.2021.3123960}}
```

**Notice:** C++ implementation of algorithms introduced in the paper could be found in [SUSTechGameAI](https://github.com/SUSTechGameAI/M3CVRP). Please kindly contact us with email or issue if you have any questions about this work.

## Description

The dataset for real-world large-scale waste collection problem: multi-depot multi-trip multi-disposal-facility capacitated vehicle routing problem (M3CVRP)

**File Description:**

- `Depots.json`: The information of depots.
- `DisposalFacilities.json`: The information of disposal facilities.
- `WasteCollectionSites.json`: The information of waste collection sites.



**The meaning of key field in json file:**

- `id`: The id of that site.
- `lng`: The longitude of that site.
- `lat`: The latitude of that site.

