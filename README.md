# DBLP_AI_Knowledge


### Differences in Knowledge Maturity between Industry and Academia from the Perspective of Core-Periphery Structure: A Case Study of Artificial Intelligence

Knowledge maturity plays an important role in promoting academic innovation and industrial transformation. Accurately identifying differences in knowledge maturity between academia and industry not only provides a basis for policymakers to optimize innovation resource allocation but also offers insights for planning individual career development paths. However, existing studies often use entire papers as proxies for knowledge and estimate knowledge maturity based on the average publication year of references, overlooking the fine-grained knowledge embedded within papers and their heterogeneous maturation trajectories, thereby limiting the precision of measurement. To address this, this paper proposes a dynamic evaluation framework for knowledge maturity based on a core-periphery structure, targeting the fine-grained knowledge level. 

<pre>
. 文件结构
├─ code
│    ├─ analysis_entity 
│    │    ├─ concept_struct.ipynb     实体成熟度分析
│    │    └─ cso_recogn.ipynb         实体提取
│    └─ pre_process
│           ├─ connect_openalex.ipynb 链接OpenAlex
│           ├─ preprocess_data.ipynb  解析DBLP XML
│           └─ search_empty_author.ipynb 补全缺失字段
└─ data
       ├─ cso_result_merged.pkl       文章实体dict
       └─ yearly_cso_coreness_0501.pickle  每年的核心边缘节点
</pre>

### 论文框架

![情报学年会 - 中文 drawio](https://github.com/user-attachments/assets/73f8116a-7d91-4265-b409-4fb71d62e0f7)
<div align="center"><b>Figure 1. 框架图</b></div>


### 描述性统计
<img width="914" height="354" alt="image" src="https://github.com/user-attachments/assets/78ec0b24-b1e6-4dfa-a654-f045a0f10685" />
<div align="center"><b>Figure 2. 每年的发文量。(a)代表三种机构类型数量 (b)不同子领域的发文数量</b></div>


<img width="855" height="320" alt="image" src="https://github.com/user-attachments/assets/0f8d2e7c-0b62-4a2b-bf9a-3ec9b26b05e9" />
<div align="center"><b>Figure 3. 核心节点的变化趋势</b></div>


### 分析结果
<div align="center"><b>Table 1. 实体-论文成熟度与机构类型的回归结果</b></div>
<img width="1030" height="600" alt="image" src="https://github.com/user-attachments/assets/d20688f9-8100-4f04-8e60-bba5b6161e9b" />




## Dependency packages

System environment is set up according to the following configuration:

- pytorch 2.0.1
- transformers 4.28.1
- pandas 2.0.0
- pytorch-crf 0.7.2
- tqdm 4.65.0
- nltk 3.8.1
- numpy 1.24.1
&& 
- Stata 17



