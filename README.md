# Bioinformatics-code
My codes
2023/10/30下午








TCGA数据处理采用DESeq2包进行数据处理

设置工作路径,例如:"/home/user/TCGA_data"

需要在TCGA(https://portal.gdc.cancer.gov/)下载数据:

gdc_sample_sheet.20xx-xx-xx.tsv
metadata.cart.20xx-xx-xx.json
gdc_download_20xxxxxx_xxxxxx.tar.gz
将gdc_download_20xxxxxx_xxxxxx.tar.gz解压到当前工作路径

修改代码中默认的工作路径为实际工作路径,例如:

work_dir = "/home/user/TCGA_data"

随后运行代码进行数据处理。

  

  



  

  



        
GEO使用说明:    

在getGEO函数中填入需要分析的GSE ID,替换示例中的GSE1402。  

根据数据集的样本信息,修改step3中的分组代码,生成自己需要的分组方式。  

运行代码,即可得到该GSE数据集的PCA结果,差异表达基因列表,以及GO和KEGG富集分析结果。  

代码提供了完整的分析流程,结果可直接用于发表。   





  







