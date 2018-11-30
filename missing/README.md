# Environment

To setup the environment do the following (remove command listed for convenience, don't run it if you don't want to remove the environment).

```bash
conda env create -f environment.yml
conda activate ds-missing
python -m ipykernel install --user --name ds-missing --display-name "ds-missing"
conda remove --name ds-missing --all
```

On Windows, you need to download the [Build Tools for Visual Studio 2017](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2017).