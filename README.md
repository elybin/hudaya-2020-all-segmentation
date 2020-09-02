# Hudaya (2020) ALL Segmentation
Acute lymphoblastic leukemia (ALL) segmentation method based on clustering algorithm modification of Vogado's (2016)<a href="#ref"><sup>[1]</sup></a> method.

# Datasets 
ALL-IDB by F. Scotti<a href="#ref"><sup>[2]</sup></a> being used on this research. 

# Index of Files
### ./README.me (this file)
### ./vogado_method.m
original source code of Vogado's<a href="#ref"><sup>[1]</sup></a> method. Forked from <a href="https://github.com/lhvogado/Recent-Computational-Methods-for-White-Blood-Cell-Nuclei-Segmentation-A-Comparative-Study">this repo</a>.
### ./vogado_method.py
Rewritten version in Python.
### ./proposed_method.py
Proposed method source code.
### ./vogado_vs_proposed.py
Two methods being obtained in single operation.

# Result 
| paper | python | matlab | title |
|--------|---------|---------|---------|
| <img src="https://user-images.githubusercontent.com/4969689/85573787-653f8a00-b660-11ea-93d0-9e41c3f6f964.jpg" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85572249-04fc1880-b65f-11ea-85dd-e3283aebcb47.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929612-9a5a0f80-b8e0-11ea-85df-7bf6d71499c1.png" width="200"/> | (a) |  
| <img src="https://user-images.githubusercontent.com/4969689/85574460-ff9fcd80-b660-11ea-90f5-a73d131e06f0.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85574568-17775180-b661-11ea-856d-9dc56913d797.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929658-e1e09b80-b8e0-11ea-99ad-215359b1ebdf.png" width="200"/> | (b) |  
| <img src="https://user-images.githubusercontent.com/4969689/85575346-ae440e00-b661-11ea-9f2d-4ee09f1ec7d3.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85575436-c0be4780-b661-11ea-92d3-75f7832ba8f1.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929677-fb81e300-b8e0-11ea-963c-cb4aeedaaf25.png" width="200"/> | (c) |  
| <img src="https://user-images.githubusercontent.com/4969689/85575614-e6e3e780-b661-11ea-94ef-b9b6bfc1db8b.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85575726-00852f00-b662-11ea-9187-e9eaa310626f.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929781-adb9aa80-b8e1-11ea-9feb-f74e0e24e256.png" width="200"/> | (d) |  
| <img src="https://user-images.githubusercontent.com/4969689/85576084-4e019c00-b662-11ea-9a89-9a9a443eaaed.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85870053-c39e7100-b7f6-11ea-8852-f1cb870673b0.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929691-118fa380-b8e1-11ea-827a-9dbf2add632b.png" width="200"/> | (e) |  
| <img src="https://user-images.githubusercontent.com/4969689/85576163-5fe33f00-b662-11ea-8d2a-528ff120da5f.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85870085-cdc06f80-b7f6-11ea-8bc7-bfedaa80b147.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929701-253b0a00-b8e1-11ea-9d63-ecf76f3b8e51.png" width="200"/> | (f) |  
| - | <img src="https://user-images.githubusercontent.com/4969689/85928220-91177580-b8d5-11ea-8d82-7b1e98095ea1.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929710-3ab03400-b8e1-11ea-871e-a0f50fdf2603.png" alt="drawing" width="200"/> | (k-means) |  
| <img src="https://user-images.githubusercontent.com/4969689/85576235-6ffb1e80-b662-11ea-90bb-ef3ba33529e3.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/86241483-2912a900-bbcd-11ea-81ff-338d9008efc2.png" alt="drawing" width="200"/>| <img src="https://user-images.githubusercontent.com/4969689/85929726-616e6a80-b8e1-11ea-9ad6-fa72b6c450c9.png" width="200"/> | (g) |  



# Ref
<ol>
<li>Vogado, L. H., de MS Veras, R., Andrade, A. R., e Silva, R. R., De Araujo, F. H., & De Medeiros, F. N. (2016, December). Unsupervised leukemia cells segmentation based on multi-space color channels. In 2016 IEEE International Symposium on Multimedia (ISM) (pp. 451-456). IEEE. [DOI: 10.1109/ISM.2016.0103]
</li>
<li>R. Donida Labati, V. Piuri, F. Scotti, "ALL-IDB: the acute lymphoblastic leukemia image database for image processing", in Proc. of the 2011 IEEE Int. Conf. on Image Processing (ICIP 2011), Brussels, Belgium, pp. 2045-2048, September 11-14, 2011. ISBN: 978-1-4577-1302-6. [DOI: 10.1109/ICIP.2011.6115881]
</li>
</ol>

