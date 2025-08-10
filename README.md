# DBLP_AI_Knowledge


### Differences in Knowledge Maturity between Industry and Academia from the Perspective of Core-Periphery Structure: A Case Study of Artificial Intelligence

Knowledge maturity plays an important role in promoting academic innovation and industrial transformation. Accurately identifying differences in knowledge maturity between academia and industry not only provides a basis for policymakers to optimize innovation resource allocation but also offers insights for planning individual career development paths. However, existing studies often use entire papers as proxies for knowledge and estimate knowledge maturity based on the average publication year of references, overlooking the fine-grained knowledge embedded within papers and their heterogeneous maturation trajectories, thereby limiting the precision of measurement. To address this, this paper proposes a dynamic evaluation framework for knowledge maturity based on a core-periphery structure, targeting the fine-grained knowledge level. 


.
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


![情报学年会 - 中文 drawio](https://github.com/user-attachments/assets/73f8116a-7d91-4265-b409-4fb71d62e0f7)


<img width="914" height="354" alt="image" src="https://github.com/user-attachments/assets/78ec0b24-b1e6-4dfa-a654-f045a0f10685" />
<div align="center"><b>Figure 2. 每年的发文量。(a)代表三种机构类型数量 (b)不同子领域的发文数量</b></div>



<img width="855" height="320" alt="image" src="https://github.com/user-attachments/assets/0f8d2e7c-0b62-4a2b-bf9a-3ec9b26b05e9" />
<div align="center"><b>Figure 3. 核心节点的变化趋势</b></div>






