# Hadoop Word Count Program

This repository contains a basic implementation of a Hadoop word count program using Google Colab. The project demonstrates the fundamental intuition behind Hadoop's MapReduce model by processing a text file (`UUD.txt`) and counting the occurrences of each word.

## Key Components:
- **mapper.py**: A script that maps input text into key-value pairs (word, 1).
- **reducer.py**: A script that reduces the mapped data by summing up the occurrences of each word.
- **UUD.txt**: The input text file used for word counting (can be replaced with your own data).

## Objective:
This project serves as a learning tool to understand the core concepts of Hadoop and MapReduce through a simple word count program.

## How to Run:
1. **Google Colab Setup:**
   - Upload your input file (e.g., `UUD.txt`) to your Google Drive.
   - Mount your Google Drive in Colab using the `drive.mount()` command.
2. **Hadoop Setup:**
   - Set up a Hadoop environment in Colab.
   - Upload your input file from Google Drive to HDFS.
   - You can either upload the `mapper.py` and `reducer.py` scripts to your Colab environment or write the code directly in Colab cells.
3. **Run the Hadoop Job:**
   - Execute the Hadoop job using the provided `mapper.py` and `reducer.py` scripts.

## Customization:
- Feel free to modify the `mapper.py` and `reducer.py` scripts to suit your specific needs.
- You can also replace the `UUD.txt` file with your own data for custom word counting tasks.

Happy coding and learning with Hadoop!

