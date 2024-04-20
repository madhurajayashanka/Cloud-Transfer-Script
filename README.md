
# Cloud Transfer Tool - Colab Notebook

Transfer files between different cloud services without downloading to your PC. This Colab notebook uses Python for HTTP requests, supports authentication, and displays progress bars. Saves on internet charges by streaming transfers in chunks.

## Usage

1. Open the Colab notebook `cloud_transfer_tool.ipynb`.

2. Modify the `download_url`, `upload_url`, `username`, and `password` variables in the notebook to your specific URLs and credentials.

3. Run the notebook in Google Colab.

## Requirements

- Google Colab
- Python 3.6+
- requests
- tqdm
- python-magic

## Setup

1. Open the notebook in Google Colab.

2. Install dependencies:

   ```python
   !pip install requests tqdm python-magic
   ```

3. Follow the instructions in the notebook to set up and run the cloud transfer tool.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

Created by <img src="https://avatars.githubusercontent.com/u/77890309?v=4" alt="Madhura Jayashanka" style="border-radius: 50%;" width="20" height="20">[Madhura Jayashanka](https://github.com/madhurajayashanka)