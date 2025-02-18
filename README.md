## Late Returns of Books

	We are being hired by a local library with a problem, their books are being checked out and then returned late way too often. They would love to understand the cause of the issue and what they can learn from the data to proactively monitor the situation going forward.
	
	The goal is to analyze the library data located [here](https://drive.google.com/drive/folders/12Rx8fqey6TSvBhg-CsgB0mDq6mQStSo5)

	Additional geo data is located [here](https://github.com/scpike/us-state-county-zip/blob/master/geo-data.csv)

	Questions we want to answer with this analysis are following:
		- Which are the factors connected to late returns?
		- How can we mitigate them?
		- What can we do to improve library records?

	Content of this repo is as following:
		- data - store download csv files here
		- docs - you can find task instructions and resulting presentation here
		- images - used to store visualizations for presentation
		- notebooks - contains jupyter notebooks

## Installation Instructions
	
	1. Clone the Repository
		git clone https://github.com/zelenbaba/billups_test
		cd your-repo

	2. Setup Virtual Environment
		python -m venv venv
		venv\Scripts\activate
	
	3. Install Dependencies
		pip install -r requirements.txt


## Usage

	After installing all required prerequisites, run jupyter notebook scripts in following order:
	
		1. data_preparation.ipynb
		2. data_exploration.ipynb
	
	Note that draw_visualizations.ipynb can be ignored as it is not relevant for analysis but used solely for creating images for presentation.