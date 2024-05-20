Commands to create the environment 'tensorflow_env':
1. Create the conda environment:
   conda create -n tensorflow_env python=3.8
2. Activate the conda environment:
   conda activate tensorflow_env
3. Install conda packages:
   conda env update --file tensorflow_env_environment.yml --prune
4. Install pip packages:
   pip install -r tensorflow_env_requirements.txt
