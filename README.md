
# Panel Tree Factor Model

This is the public R package for Panel Tree factor model. More details are in the [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3949463).

# How to install **TreeFactor**

- assume Mac/Linux user
- use command line, go to folder where you store github repos
- git clone this repo to your machine
- run `ls` command, you should see **TreeFactor** printed
- run `R CMD INSTALL TreeFactor`

For windows users, install the package in R session:
*install.packages("your_directory/TreeFactor", repos = NULL, type = "source")*

# How to start using **TreeFactor**

- run `cd TreeFactor`
- run `sh demo.sh`
    - simulate R data
    - run demo1 for basic boosted tree
    - run demo2 for market adjusted boosted tree
    - run demo3 for time series split.
- you can find the printed output in `test/demo` folders.

For windows users, please run each demo in the corresponding folder.

# Reference

- You are encouraged to cite our paper for P-Tree factor model.
- Working paper version: [Asset Pricing with Panel Trees under Global Split Criteria](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3949463)

