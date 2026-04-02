<div align="center">
<img src="https://github.com/user-attachments/assets/3e44e70f-d0f9-4560-b75f-5860b574935d" alt="Image" width="300"/>
</div>

Conda is a powerful command line tool for package and environment management that runs on Windows, macOS, and Linux. 

This guide to getting started with conda goes over the basics of starting up and using conda to create environments and install packages. 

## Install conda  by conda-forge/miniforge 
- gitclone

You can use either wget or curl to download the latest installer script for your system:
```cmd
wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh" 
```
or
```cmd 
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh" 
```

- Run the script with: 
```bash
bash Miniforge3-$(uname)-$(uname -m).sh 
```
- Source .bashrc
```bash
source ~/.bashrc
```

- Test conda

```bash
conda
```
If everything is working, you'll see output similar to:
  <div align="center">
    <img src="https://github.com/user-attachments/assets/a94bfdbd-f082-421a-97ea-15785d593b06" alt="Image" width="550"/>
</div>
    
## Conda environment

It is an isolated directory that contains a specific set of software packages and their dependencies.

### Essential Commands

To manage environments, use these common commands in your terminal or Anaconda Prompt: 
|  Task  | Command | 
|---------|-------------|
|Create |	conda create --name myenv python=3.9|
|Activate |	conda activate myenv|
|Deactivate	| conda deactivate|
|List Envs | conda env list (or conda info --envs)|
|List Packages	| conda list (shows packages in the active env)|
|Delete |	conda remove --name myenv --all|

### Core Benefits
  - Isolation: Prevents version conflicts between projects by keeping their libraries and even the Python interpreter separate.
  - Reproducibility: You can export your environment to a YAML file, allowing others to recreate the exact setup on different machines.
  - Multi-language Support: Manages binary libraries and multiple programming languages beyond Python.
