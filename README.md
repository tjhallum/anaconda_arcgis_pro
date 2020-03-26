## Setup Anaconda to Manage Cloned ArcGIS Pro Python Environments

 1. Run ArcGIS Pro as Administrator
	 2. ![Run ArcGIS Pro as Admin](https://raw.githubusercontent.com/tjhallum/anaconda_arcgis_pro/master/1-run_arc_as_admin.png)
 2. Create a new Python deep learning environment as depicted in the screen snip below by cloning the default Python environment arcgispro-py3 (while you can use any unique name for your cloned environment, the steps below use deep learning).
	 3. ![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/2-create_new_virtual_env.png)
 3. Install Anaconda
	 4. Check for the new cloned ArcGIS Pro Python virtual environment in Anaconda:
		 5. Uh oh...it's not listed:
			 6. ![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/3-anaconda_cant_see_arcgis_pro_python_env.png)
		 6. Locate Anaconda's .condarc file:
			 7. Path: C:\Users\XXXXXXXX\.condarc
				 8. Original file content:
					 9. ![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/4-orig_condarc_file.png)
			 8. Make the necessary edits to the .condarc file:
				 9. ![enter image description here](https://github.com/tjhallum/anaconda_arcgis_pro/raw/master/5-amended_condarc_file.png)
		 7. There, now the ArcGIS Pro Python environment that we cloned for the purposes of deep learning is available to us for configuration in Anaconda’s familiar GUI & Command Line interfaces:
			 8. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU5NjkzOTM2NV19
-->