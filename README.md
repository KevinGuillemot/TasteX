# TasteX
Food Explorer

## Datasets:

### Recipe/Ingredient database
- Source: http://s3.amazonaws.com/wikia_xml_dumps/c/co/cookbook_import_pages_current.xml.7z
- As of: 8/7/2017
- Version: "2017-05-10 22:40:17"
- Format: XML
- Website: http://recipes.wikia.com/wiki/Special:Statistics


### Ingredient/Chemistry database
TODO








## References

1. Smart Recipe  
   Source: http://pub.tik.ee.ethz.ch/students/2015-FS/BA-2015-15.pdf  
   Description: Recipe classification from ingredients  
   Tools: Classification trees, k-means

2. The Recipe Learner  
   Source: http://cs229.stanford.edu/proj2013/DengSafreno-TheRecipeLearner.pdf  
   Description: Given n-1 ingredients and their quantities find quantity of nth ingredient  
   Tools: EDA on sparse recipe/ingredient matrix. Several dimension reduction teechinques explored  

3. Spices form the basis of food pairing in Indian cuisine  
   Source: https://arxiv.org/ftp/arxiv/papers/1502/1502.03815.pdf  
   Description: Dimension reduction to extract common "flavors" from recipe and then cluster  
      Ingredient contribution to a recipe  
      Detailed approach to deal with spices in recipes  
   Tools: Linear regression


