# Reading huge size of data which is bigger than RAM

## What is Dask and why do we use it?

Dask is a parallel computing library that scales the existing Python ecosystem. This tutorial will introduce Dask and parallel data analysis more generally.

Dask can scale down to your laptop and up to a cluster. Here, we’ll use an environment you setup on your laptop to analyze medium sized datasets in parallel 
locally.

![image](https://user-images.githubusercontent.com/27494848/140326448-061b3357-0760-4f5f-ae15-ef4afa56256d.png)

## Usage

- Install required modules with `pip install -r requirements.txt`
- Start `jupyter notebook`
- Put your csv file into project folder
- Set `blocksize` variable for partitions blocksizes
- Set `cols` variable to specify column names which is used in csv file
- Run all cells in ipynb

## Time Complexity

Time complexity is O(n) where n is count of rows.
