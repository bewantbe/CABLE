## Code dependencies.  
Code dependencies are in 'requirement.txt'.  
```sh
pip install -r requirements.txt
```

## Example data and usage.  
* The example data 'CJ4TEST.h5' can be accessed via XXX.

* We use 'Mrtrix3' for estimating response function(or use response.nii in this repository directly) and constrained spherical deconvolution(CSD), which can be accessed via 'https://www.mrtrix.org/download/'.  

* After installing 'Mrtrix3', execute the python file:

```sh
python main.py CJ4TEST.h5
```

* If the code in 'main.py' encounters difficulties in calling 'Mrtrix3'(e.g. executing on Windows) please execute it manually.  
* The program will generate odf and tck files which can be viewed with 'mrview' in 'Mrtrix3', use 'ODF Display' and 'Tractography' in 'Tools' to view them.

![image ](https://github.com/Euyz/CABLE/assets/33593212/e1d11bad-6171-4077-97b4-680b15ebdd21)
![image](https://github.com/Euyz/CABLE/assets/33593212/b65d6905-4924-4cc2-851d-e3de5d551a20)

