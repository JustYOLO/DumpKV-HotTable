## DumpKV: Learning based lifetime aware garbage collection for key value separation in LSM-tree

## Build 
```
mkdir build && cd build
cmake -DCMAKE_BUILD_TYPE=Release .. && make -j16
```

## Run benchmark
Test YCSB workload for different skewness
```
cd ../tools && ./call_run_blob_multiple_ycsba.sh   zipfian-ycsba-default                                                                        
```

## Paper link
[DumpKV: Learning based lifetime aware garbage collection for key value separation in LSM-tree](https://dl.acm.org/doi/10.14778/3717755.3717778)
Cite our paper if it's helpful to your work
```
@article{10.14778/3717755.3717778,
author = {Zhuang, Zhutao and Zeng, Xinqi and Chen, Zhiguang},
title = {DumpKV: Learning Based Lifetime Aware Garbage Collection for Key Value Separation in LSM-Tree},
year = {2025},
issue_date = {December 2024},
publisher = {VLDB Endowment},
volume = {18},
number = {4},
issn = {2150-8097},
url = {https://doi.org/10.14778/3717755.3717778},
doi = {10.14778/3717755.3717778},
journal = {Proc. VLDB Endow.},
month = may,
pages = {1223–1236},
numpages = {14}
}
```

See the [github wiki](https://github.com/facebook/rocksdb/wiki) for more explanation.


DumpKV is developed based on RocksDB. Please see License of RocksDB.
## License

RocksDB is dual-licensed under both the GPLv2 (found in the COPYING file in the root directory) and Apache 2.0 License (found in the LICENSE.Apache file in the root directory).  You may select, at your option, one of the above-listed licenses.
