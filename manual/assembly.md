
## Assembly

Assemble preprocessed read data, using Megahit, Spades or both. Evaluates result with Quast. Accepts a tab-delimited input table, specified in the config.yaml (see example below). Comment lines are specified with the # character. An input table is automatically generated at the end of the preprocessing pipeline and can be found at `01_processing/assembly_input.txt`.

```
#Sample Reads1.fq[.gz][,Reads2.fq[.gz][,orphans.fq[.gz]]]
sample_a    a_1.fq,a_2.fq,a_orphans.fq
sample_b    b_1.fq,b_2.fq,b_orphans.fq
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcyNjMyNjgwNl19
-->