## Setup Anaconda to Manage Cloned ArcGIS Pro Python Environments

 **1. Run ArcGIS Pro as Administrator.**
 
![Run ArcGIS Pro as Admin](https://raw.githubusercontent.com/tjhallum/anaconda_arcgis_pro/master/1-run_arc_as_admin.png)

**2. Create a new Python virtual environment in ArcGIS Pro as depicted below by cloning the default Python environment arcgispro-py3 (while you can use any unique name for your cloned environment, the steps below use deep learning).**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/2-create_new_virtual_env.png)

**3. Install Anaconda. Then, check for the new cloned ArcGIS Pro Python virtual environment in Anaconda. Uh oh...it's not listed:**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/3-anaconda_cant_see_arcgis_pro_python_env.png)

**4. Locate Anaconda's .condarc file (C:\Users\XXXXXXXX\.condarc). Original file content:**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/4-orig_condarc_file.png)

**5. Make the necessary edits to the .condarc file:**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/5-amended_condarc_file.png)

**6. There, now the ArcGIS Pro Python environment that we cloned for the purposes of deep learning is available to us for configuration in Anaconda’s familiar GUI & Command Line interfaces:**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/6-anaconda_sees_arcgis_pro_python_env.png)

**7. Finally, now that our Python environment for deep learning in ArcGIS Pro is properly configured, we just need to make sure that we set it as the active Python environment for our project in ArcGIS Pro:**

![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/7-arcgis_pro_make_new_python_env_active.png)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMTE0OTk2MiwtMTk0MzA2OTI4MCwtMT
M2NDk4MDUwOV19
-->