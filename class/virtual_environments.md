#Virtual Environments
Python: `python3 -m venv [NAME OF FOLDER]` [[https://docs.python.org/3/library/venv.html|Python Docs]]

 To activate this environment, use:
 > cd [DIRECTORY] && source /bin/activate

 To deactivate an active environment, use:
 > deactivate
 
Conda: `conda create -n yourenvname python=x.x anaconda` [[https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/|Conda docs]]

 To activate this environment, use:
 > conda activate condavenv
 * Note: you will need to run `conda init` first.  This will load some crap into your .bashrc

 To deactivate an active environment, use:
 > conda deactivate
