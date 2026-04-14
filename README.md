# Meter Data Prediction AI Project 
Artificial Intelligence - CSI 4130 <br>
Southeastern Oakland County Water Authority <br>
Project duration: March - Mid-April

## Overview
This project aims to use an AI model to predict lost wireless water meter data.

## Main Problem
My employer, SOCWA (Southeastern Oakland County Water Authority), receives wireless data from a collection of water meters via PLCs every 5 minutes in 1 minute batches. Occasionally, the signal is lost, and a batch is not received. This creates gaps in the data when visualizing and analyzing water meter usage. Using an AI model can help predict this missing data for clearer analysis.

This project uses the following dependencies:
pip install pandas numpy matplotlib torch ipywidgets

If using Google Collab:
These packages are already installed

Link to project presentation video:
https://drive.google.com/file/d/1qdoVL8gfkNH65kAucpxx3_4txV-N18WW/view?usp=drive_link

Link to report:
https://drive.google.com/drive/folders/1sehhj31wehFfLuu3HR2AtLZUB3E4vwJh?usp=drive_link

Credits:
Google Gemini for help with debugging and ideas for project, 
Structure of BiLSTM model: https://www.codegenes.net/blog/bi-directional-lstm-attention-pytorch/
