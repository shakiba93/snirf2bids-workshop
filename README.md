# Instructions for the Hands-On snirf2bids Conversion Experience


The workflow is fully implemented in [Cedalion](https://doc.ibs.tu-berlin.de/cedalion/doc/dev/)Cedalion. If you already have Cedalion installed on your system, you can directly open the ```snirf2bids```.ipynb example and go through the steps. However, for simplicity, we will run everything on [Google Colab](https://colab.research.google.com/), which is accessible to all and does not require a local installation of Cedalion.
A [sample dataset](https://drive.google.com/drive/folders/1O3LwW-PW4rOWIXVXF-R7j7nRaixViyTV?usp=sharing) has been shared with you. Please ensure you have access before starting.

## Using a Local System
If you have Cedalion installed locally, follow these steps to prepare:
1. Open the ```snirf2bids``` example notebook located at:
 ```cedalion/examples/snirf2bids.ipynb```
2. Download the sample dataset to a preferred location on your system.
3. Set the ```dataset_path``` variable to the location of the downloaded dataset.
4. Set the ```destination_path``` variable to your desired BIDS output folder.
 *(You do not need to create this folder manually — it will be generated automatically.)*
## Using Google Colab
If you prefer to avoid local installation, Colab is the easiest way to participate (and this is what we will use during the webinar). Follow these preparation steps:
1. **Install Cedalion on Colab:**
 
 Follow the [instructions](https://doc.ibs.tu-berlin.de/cedalion/doc/dev/getting_started/colab_setup.html#) in the Cedalion documentation for running notebooks on Colab. This will set up both Cedalion and your Google Drive folder.
2. **Access the sample dataset:** Use the [shared link](https://drive.google.com/drive/folders/1O3LwW-PW4rOWIXVXF-R7j7nRaixViyTV?usp=sharing) to the dataset and create a shortcut in your **My Drive** folder.
3. **Editing JSON/TSV files in Colab:** During the workflow, you may need to modify some JSON or TSV files. Since these cannot be directly edited in Colab’s file browser, you have two options:
- Open/download the files in your Drive/Local storage, edit them, and save/re-upload.
- Or, add coding cells in the notebook to edit the files programmatically within Colab.
 *(A notebook version for editing CSV, TSV, or JSON files in Colab is provided.)*
4. Set the ```dataset_path``` variable to the location of the dataset in your Drive.
5. Set the ```destination_path``` variable to your desired BIDS output folder.
 (No need to create it manually — it will be automatically generated.)
You are now ready 🙂
