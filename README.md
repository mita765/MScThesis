# IMPORTANT --- If you want to run these notebooks (rather than look at the embedded outputs):
### Windows Users
- Make sure you have Jupyter notebooks working (including your base kernel)
- Open your terminal in .../MScThesis
- Run the following snippet:
  ```
  cmd /k "conda init && conda env create -f thesis.yml && python -m ipykernel install --user --name=thesis && exit"
  ```

### Linux Users
- Make sure you have Jupyter notebooks working (including your base kernel)
- Open your terminal in .../MScThesis
- Run the following ssnippet:
  ```
  conda init && conda env create -f thesis.yml && python -m ipykernel install --user --name=thesis
  ```
  
This will install all the necessary libraries used in Thesis-TR and Thesis-ML.

## After running `create_env_kernel`:
Open the notebook you would like to run and select the `thesis` Jupyter kernel. Then, simply run all.
