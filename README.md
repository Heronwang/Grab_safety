# Grab_safety 

## Download
Since some files exceed the file size limit set by GitHub, please download from this link:
https://drive.google.com/file/d/14zeTMn67k7W1dLmlCVEr-npfOLAKKucn/view?usp=sharing      
for the workable folder and documentation.           
                        
                                                  
## Run                                                                          

### 1.     
Unzip the linked file.Drag the testing labels (the one csv file only) under `testlabels` folder, and drag the files containing testing features (csv files only) under `testfeatures` folder. From there, open ipython notebook within a python3 environment.            
             
             
### 2.     
Open the .ipynb file named `final_code.ipynb`** Run the code. Environment requirements are listed below:    


- **python3.6**  
    
Along with standard libraries (`math`,`os`,`time`,`warnings`) and conventional data science libraries (`scipy`, `numpy`, `pandas`, `matplotlib`, `sklearn`). Noticebly, you also need to have `pywt` library.    
     
     
- **pywt**     
   
It is different from the native pywt library. You may need to uninstall it to avoid name conflicts by **pip uninstall pywt**.  Then install the one here by:   

**pip install PyWavelets**   

(or if you have conda: `conda install pywavelets`)      

- **peakdetect.py**
    
This is a script kindly provided for public use from here https://gist.github.com/antiface/7177333

It is under current directory already. 

- **library versions**    
    
`scipy: 0.19.1    
numpy: 1.14.2    
pandas: 0.20.3    
sklearn: 0.20.0    
matplotlib: 2.1.0`   
