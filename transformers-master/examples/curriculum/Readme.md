# In-sample Curriculum Learning by Sequence Completion for Natural Language Generation

**Requirements**
* python3.7
* pytorch1.7.0
* transformers 4.7.0


**Implementation of ICL-SC on dialogue summarization**

* Replace the original "modeling_bart.py" in the original transformer packages.

* Download and put the data into corresponding directories.

* Run ICL-SC by:
```
bash train_samsum_icl.sh
```