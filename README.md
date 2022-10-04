# STAT_201 Group 19 Project

| Milestones          | Deadline         | Who is submitting? |
| ------------------- | ---------------- | ------------------ |
| Group Contract      | Oct 8th 11:59PM  |                    |
| Project Proposal    | Nov 5th 11:59PM  |                    |
| Project Peer Review | Nov 12th 11:59PM |                    |
| Team Evaluation     | Nov 26th 11:59PM |                    |
| Final Report        | Nov 26th 11:59PM |                    |

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

2. Setup with:
  ```sh
    conda env create --no-default-packages -f src/conda_env.yml
  ```

  > This uses `v3.7 Python` and `R` due to an dependency error for Python >=v3.8. Read more about the issue [here](https://github.com/executablebooks/jupyter-book/issues/906).

3. Activate the notebook env and run the kernel.
  ```sh
    conda activate stat_201_proj
    cd src
    jupyter notebook
  ```

4. Edit the notebook in the browser (or your jupyter supported editor/IDE) as you please!

