# Naturalistic Variation in Goal-Oriented Dialog datasets

## Motivation
Existing benchmarks used to evaluate the performance of end-to-end neural dialog systems lack a key component: `natural variation present in human conversations`.  
  
Most datasets are constructed through crowdsourcing, where the crowd workers follow a fixed template of instructions while enacting the role of a user/agent.

This results in _straight-forward, somewhat routine, and mostly trouble-free_ conversations, as crowd workers do not think to represent the full range of actions that occur naturally with real users. 


## Datasets
This directory contains the new and more effective testbeds for bAbI dialog task 5 and Stanford Multi-Domain datasets, which incorporate naturalistic variation by the user.

We observe that there is a significant drop in performance (more than 60% in Ent. F1 on SMD and 85% in per-dialog accuracy on bAbI task) of recent state-of-the-art end-to-end neural methods such as BossNet and GLMP on both datasets.

#### bAbI dialog task
The updated test sets for bAbI dialog task follow the same data format as the original dataset explained here: https://research.fb.com/downloads/babi/  

The train, validation and original test files for bAbI dialog task 5 are available at the link mentioned above.

#### Stanford Multi-Domain Dataset (SMD)
The updated test set for Stanford Multi-Domain Dataset (SMD) dataset follows the same data format as the original dataset explained here: https://nlp.stanford.edu/blog/a-new-multi-turn-multi-domain-task-oriented-dialogue-dataset/

The train, validation and original test files for Stanford Multi-Domain Dataset (SMD) are available at the link mentioned above.

## License

The dataset is released under [**Apache 2.0**](https://www.apache.org/licenses/LICENSE-2.0) license. For the full
license, see [LICENSE](LICENSE). Please cite the following paper if you
use this dataset in your work

```shell
@inproceedings{ganhotra-etal-2020-effects,
    title = "Effects of Naturalistic Variation in Goal-Oriented Dialog",
    author = "Ganhotra, Jatin  and
      Moore, Robert  and
      Joshi, Sachindra  and
      Wadhawan, Kahini",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: Findings",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.findings-emnlp.358",
    pages = "4013--4020",
    abstract = "Existing benchmarks used to evaluate the performance of end-to-end neural dialog systems lack a key component: natural variation present in human conversations. Most datasets are constructed through crowdsourcing, where the crowd workers follow a fixed template of instructions while enacting the role of a user/agent. This results in straight-forward, somewhat routine, and mostly trouble-free conversations, as crowd workers do not think to represent the full range of actions that occur naturally with real users. In this work, we investigate the impact of naturalistic variation on two goal-oriented datasets: bAbI dialog task and Stanford Multi-Domain Dataset (SMD). We also propose new and more effective testbeds for both datasets, by introducing naturalistic variation by the user. We observe that there is a significant drop in performance (more than 60{\%} in Ent. F1 on SMD and 85{\%} in per-dialog accuracy on bAbI task) of recent state-of-the-art end-to-end neural methods such as BossNet and GLMP on both datasets.",
}
```


## Dataset Metadata
The following table is necessary for this dataset to be indexed by search
engines such as <a href="https://g.co/datasetsearch">Google Dataset Search</a>.
<div itemscope itemtype="http://schema.org/Dataset">
<table>
  <tr>
    <th>property</th>
    <th>value</th>
  </tr>
  <tr>
    <td>name</td>
    <td><code itemprop="name">Naturalistic Variation in Goal-Oriented Dialog datasets</code></td>
  </tr>
  <tr>
    <td>alternateName</td>
    <td><code itemprop="alternateName">Naturalistic Variation in Stanford Multi-Domain (SMD) and bAbI dialog task 5 datasets</code></td>
  </tr>
  <tr>
    <td>url</td>
    <td><code itemprop="url">https://github.com/IBM/naturalistic-variation-goal-oriented-dialog-datasets</code></td>
  </tr>
  <tr>
    <td>sameAs</td>
    <td><code itemprop="sameAs">https://github.com/IBM/naturalistic-variation-goal-oriented-dialog-datasets</code></td>
  </tr>
  <tr>
    <td>description</td>
    <td><code itemprop="description">The datasets are new and more effective testbeds for bAbI dialog task 5 and Stanford Multi-Domain datasets, which incorporate naturalistic variation by the user. Existing benchmarks used to evaluate the performance of end-to-end neural dialog systems lack a key component: natural variation present in human conversations. Most datasets are constructed through crowdsourcing, where the crowd workers follow a fixed template of instructions while enacting the role of a user/agent. This results in straight-forward, somewhat routine, and mostly trouble-free conversations, as crowd workers do not think to represent the full range of actions that occur naturally with real users. We observe that there is a significant drop in performance (more than 60% in Ent. F1 on SMD and 85% in per-dialog accuracy on bAbI task) of recent state-of-the-art end-to-end neural methods such as BossNet and GLMP on both updated datasets which incorporate naturalistic variation by the user.</code></td>
  </tr>
  <tr>
    <td>provider</td>
    <td>
      <div itemscope itemtype="http://schema.org/Organization" itemprop="provider">
        <table>
          <tr>
            <th>property</th>
            <th>value</th>
          </tr>
          <tr>
            <td>name</td>
            <td><code itemprop="name">IBM</code></td>
          </tr>
          <tr>
            <td>sameAs</td>
            <td><code itemprop="sameAs">https://en.wikipedia.org/wiki/IBM</code></td>
          </tr>
        </table>
      </div>
    </td>
  </tr>
  <tr>
    <td>citation</td>
    <td><code itemprop="citation">https://www.aclweb.org/anthology/2020.findings-emnlp.358</code></td>
  </tr>
</table>
</div>