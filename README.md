# UMNAI Examples

## Setup

Once you have [set up the UMNAI Platform](https://docs.umnai.com/set-up-your-environment), you can proceed to run the example notebooks.

If you do not have access to the UMNAI Platform, [join our Beta Program](https://umnai.com/beta).

## License

For Terms of Use, please refer to [LICENSE.md](LICENSE.md) or [https://umnai.com/eula](https://umnai.com/eula).

## Datasets
The datasets used in the notebooks are read in to each notebook directly from the repository, so you do not need to download them explicitly.

## Workspace Paths
The notebooks include in-built functionality that detects whether you are running on a local machine or on Databricks and sets workspace and experiment paths accordingly and automatically.

If you run the notebooks on a **local machine**, the workspaces will be created in the **/resources/workspaces/** folder relative to the notebook run directory.

If you run the notebooks on **Databricks**, the UMNAI workspaces will be created in the **/dbfs/FileStore/workspaces/** folder.

## Pre-induced Models
If you want to speed up execution of the notebooks, you can use the pre-induced models supplied in the Github notebook workspaces. To use these models, download and save the workspaces to the appropriate folder as explained in the previous section on Workspace Paths.

## Notebooks
The following notebooks are available for download with this release. We hope you enjoy exploring Hybrid Intelligence with them.

### [Quickstart](Quickstart.ipynb)

Gives an overview of the key functionality within the XNN Platform and get you up to speed with the Hybrid Intelligence framework. This notebook uses the Adult Income dataset.

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

