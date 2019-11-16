## catsndogs Dataset

- A simple compact and free to use dataset with images of cats and dogs
- Both categories contain 400 pictures (total 800) of various sizes
- Originally this dataset was used to train convolutional neural networks

To download the files for trainging, add these lines to Jupyter notebook:
```python
!wget 'https://github.com/arathus/catsndogs/blob/master/catsndogs_data.zip?raw=true'
import zipfile
with zipfile.ZipFile('./catsndogs_data.zip?raw=true', 'r') as zip_ref:
    zip_ref.extractall('./data')
```
