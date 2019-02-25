Machine Learning Bootcamp for Software Engineers
================================================

*by [Infinia ML](https://infiniaml.com/).*

This repository is for participants in the Infinia ML Machine Learning Bootcamp for Software Engineers.

The last bootcamp was held on February 13 2019 at [The Frontier](https://www.rtp.org/about-us/the-frontier/) in RTP, NC.

**FYI: this repository was renamed on 2/25/19.** GitHub redirects requests to the new name but we recommend updating your remote URL:
    
    # if using SSH (preferred)
    git remote set-url origin git@github.com:infiniaml/ml-bootcamp.git

    # if using HTTPS
    git remote set-url origin https://github.com/infiniaml/ml-bootcamp

# Setup steps - before the bootcamp

**Estimated time: 30 minutes**

1. Clone this repository to your laptop:  `git clone https://github.com/infiniaml/ml-bootcamp`
    - This should create a new folder called "ml-bootcamp" with the repository files.
2. Install Anaconda - see [Anaconda_Installation.pdf](https://github.com/infiniaml/ml-bootcamp/blob/master/Anaconda_Installation.pdf) for OS-specific instructions.
3. Create the Python environment by opening a terminal and running `conda env create` while your terminal is the cloned repo directory, "ml-bootcamp". This will download and install the dependencies specified in environment.yml.
    - If this doesn't work for some reason, you can achieve the same results by running `conda create -n mlbootcamp python=3.6 tensorflow numpy matplotlib jupyter tqdm`.
4. Activate the Python environment by running `source activate mlbootcamp` (or just `activate mlbootcamp` on Windows).
    - *Important: you must always activate the "mlbootcamp" environment in your terminal, to ensure the correct environment and dependencies are being used by subsequent commands.*
5. Launch the Jupyter notebook server by running `jupyter notebook`. This should open a web browser window at [http://localhost:8888](http://localhost:8888).
6. Click the "Bootcamp.ipynb" notebook file to open it.
7. Run all the commands in cells 1, 2, 3, and 4. To run a single cell, select it with your mouse and click the "play" / "run" button.
    - *If you encounter any issues with these setup instructions, please create a GitHub issue with helpful notes and we'll be happy to assist.*
8. Come to the bootcamp! We look forward to meeting you.
