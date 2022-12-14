# Overview
Welcome to the Jupyter Notebook for the research project.

## See Notebooks
See `src/` for the `.ipynb` notebook pages.

See the branch [`gh-pages`](https://github.com/Mapleia/STAT_201_proj/tree/gh-pages) for the HTML pages.

## Deadline

| Milestones          | Deadline         | Who is submitting? |
| ------------------- | ---------------- | ------------------ |
| Group Contract      | Oct 8th 11:59PM  |    @Mapleia        |
| Project Proposal    | Nov 6th 11:59PM  |    @Mapleia        |
| Project Peer Review | Nov 12th 11:59PM |    @Mapleia        |
| Team Evaluation     | Nov 26th 11:59PM |    @Mapleia        |
| Final Report        | Nov 26th 11:59PM |    @Mapleia        |

## Written By:
* Akash Raut
* Alp Tutar
* Andrew Levner
* Kaede Ito

## Useful Links
* [Group Project Outline from STAT 201](https://ubc-stat.github.io/stat-201/group-project.html)

* [Group Contract](https://docs.google.com/document/d/1oAqF9jbTbj9C6QhEW-NYKRDmF-C4MRixj4sham7cDfs/edit?usp=sharing)

# Install and Environment Setup
## Recommended: Anaconda (Miniconda)
1. [Install Anaconda](https://docs.anaconda.com/anaconda/install/index.html), a Python environment manager. You can also install Miniconda (a miniature version of Anaconda without all the bells and whistles.)
    > Remember to run `conda init` after install.
2. Setup with:
    ```sh
      conda env create --no-default-packages -f conda_env.yml
    ```
3. Activate the notebook env and run the kernel.
    ```sh
      conda activate stat_201_proj
      jupyter notebook
    ```
4. Edit the notebook in the browser (or your jupyter supported editor/IDE) as you please!

## Publish Online to GitHub Pages
### Following [this tutorial](https://jupyterbook.org/publish/gh-pages.html):

Run these steps after every major update to publish the changes.

1. In a terminal (with the conda environment activated), move to the notebook directory.
    ```
    cd C:/ABSOLUTE/PATH/TO/PROJECT/ROOT/FOLDER
    ```
2. Run `jupyter-book build .`
3. Run `ghp-import -n -p -f _build/html`
