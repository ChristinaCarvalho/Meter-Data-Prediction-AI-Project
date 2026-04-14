# Meter Data Prediction AI Project 
Artificial Intelligence - CSI 4130 <br>
Southeastern Oakland County Water Authority <br>
Project duration: March - Mid-April

## Overview
This project aims to use an AI model to predict lost wireless water meter data.

## Abstract
SOCWA (Southeastern Oakland County Water Authority) receives batches of wireless data from water meters that occasionally get lost in transmission, leaving gaps in the data. Using a BiLSTM (Bidirectional Long Short Term Memory) model can analyze this sequential data before and after a selected data point. A sliding window was implemented to only evaluate data 15 minutes before and after the selected data point. Additionally, masking techniques were used to train the model since there is only a single dataset. The model achieved an MSE train loss of about 15 and a validation loss of about 9. Overall, the model was accurate within about 2-3 units.

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
