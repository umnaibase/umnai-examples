# UMNAI Examples

## Setup

Once you have [set up the UMNAI Platform](https://docs.umnai.com/set-up-your-environment), you can proceed to run the example notebooks.

If you do not have access to the UMNAI Platform, [join our Beta Program](https://umnai.com/beta).

## License

For Terms of Use, please refer to [LICENSE.md](LICENSE.md) or [https://umnai.com/eula](https://umnai.com/eula).

## Datasets
The datasets used in the notebooks are read in to each notebook directly from the repository, so you do not need to download them explicitly.

## Notebook Environment Settings
The Quickstart Notebook comes in three flavours, corresponding to the three supported environments. 

All other notebooks are set up to run on a local machine (Jupyter). To use them on Google Colab or Databricks you must add the relevant commands, which you can copy from the Quickstart notebooks.

See [here](https://docs.umnai.com/workspaces/manage-workspaces) for more information on Workspace and experiment paths.

### Jupyter
Suitable for a local machine setup. 

If you run the notebooks on a local machine, the workspaces will be created in the **/resources/workspaces/** folder relative to the notebook run directory.

### Google Colab
Includes commands to enable vars.env file usage on Google Colab and sets workspace and experiment paths so models are stored on Google Drive.

If you run the notebooks on Google Colab, the UMNAI workspaces should be created in the **/content/gdrive/MyDrive/Colab Notebooks/resources/workspaces/** folder.

### Databricks
Includes commands to set up and create workspace and experiment directories and paths on DBFS. It can be set to the user's or the shared Databricks workspace.

If you run the notebooks on Databricks, the UMNAI workspaces will be created in the **/dbfs/FileStore/workspaces/** folder.

## Pre-induced Models
If you want to speed up the execution of the notebooks, you can use the pre-induced models supplied in the GitHub notebook workspaces. To use these models, download and save the workspaces to the appropriate folder, as explained in the previous section.

## Available Notebooks
The following notebooks are available for download with this release. We hope you enjoy exploring Hybrid Intelligence with them.

All the notebooks use the Adult Income dataset.

### [Quickstart](Quickstart.ipynb)

Gives an overview of the key functionality within the XNN Platform and get you up to speed with the Hybrid Intelligence framework. This notebook uses the Adult Income dataset.

### [Quickstart Colab](Quickstart-Colab.ipynb)

Google Colab version of the quickstart notebook.

### [Quickstart Databricks](Quickstart-Databricks.ipynb)

Databricks version of the quickstart notebook.

### [Save Load Register ESM](Save-Load-Register-ESM.ipynb)

Demonstrates the various options available for saving and loading ESMs. This notebook uses the Adult Income dataset.

### [Unseen Categories](Unseen-Categories.ipynb)

Demonstrates how to enable and use Unseen Category Handling with data onboarding, induction and explanation views. This notebook uses the Adult Income dataset.

### [Infrequent Categories](Infrequent-Categories.ipynb)

Demonstrates how to enable and use Infrequent Categories with data onboarding, induction and explanation views. This notebook uses the Adult Income dataset.

### [Feature Groups](Feature-Groups.ipynb)

Demonstrates how to enable and use Feature Groups with data onboarding, induction and explanation views. This notebook uses the Adult Income dataset.

### [Test-And-Evaluate-Classification-Model](Test-And-Evaluate-Classification-Model.ipynb)

Demonstrates how to onboard test data and use it with the Classification Evaluation View. This notebook uses the Adult Income dataset.

### [Model Update](Model-Update.ipynb)

Demonstrates how to update (re-train) a model and compare two models using the Model Comparison View. This notebook uses the Adult Income dataset.

### [Save-Load-Configs](Save-Load-Configs.ipynb)

Demonstrates how to save an Induction configuration and load it into a new workspace to replicate the induction setup. This notebook uses the Adult Income dataset.

### [Partial Dependency Plot](Partial-Dependency-Plot.ipynb)

Demonstrates how to plot partial dependency data for various modules with different numbers and types of input features.
