This page was created in response to the benchmarks from a much earlier version of `dplyr` (v0.1), which (incorrectly) claimed to be faster than `data.table` in many aspects of data manipulation (due to oversights).

Because it was a response to that benchmark, we used the same dataset. And it's size is <10MB, which is very very small. It is hard to conclude the performance of tools designed for really large data with such small datasets.

Since then, there have been many releases and improvements from both `data.table` and `dplyr`. For the most recent version of benchmarks, on **data sizes upto 100GB in RAM**, visit the [data.table wiki page](https://github.com/Rdatatable/data.table/wiki). We compare `data.table`, `dplyr` **and** `pandas`, although only *grouping* for now. 

We hope to benchmark other operations and add it to the wiki when we find more time.
