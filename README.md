## Project Overview

The PyChain Ledger is a project I've been working on to develop a basic blockchain implementation using Python. This blockchain is designed to store financial transaction records. To interact with and visualize the blockchain, I've built a user interface using Streamlit.

## Code Description

In this project, I've accomplished the following:

### Step 1: Create a Record Data Class

I created a new data class named `Record`. This class serves as the blueprint for financial transaction records that are stored in the blocks of the ledger.

### Step 2: Modify the Existing Block Data Class

I modified the existing `Block` data class to replace the generic `data` attribute with a `record` attribute of type `Record`. This change allows me to store transaction records in each block.

### Step 3: Add Relevant User Inputs to the Streamlit Interface

I extended the Streamlit interface to include input areas for capturing sender, receiver, and amount details for each financial transaction. This allows users to interact with the blockchain by adding new transactions through the user interface.

### Step 4: Test the PyChain Ledger

I've been in the process of testing the PyChain Ledger by storing records and validating the blockchain. However, I have encountered issues with properly running Streamlit, which has hindered my testing progress.

## Issues Encountered

Unfortunately, I've faced difficulties in getting Streamlit to work as expected. This has impacted my ability to fully test the PyChain Ledger and demonstrate its functionality.

I'm actively working on resolving these issues and will update this README once I have successfully addressed them.

While I'm resolving the Streamlit issues, you can still explore the code and the project structure. 


![Screenshot](C:\Users\RAMZI\Desktop\Screenshot 2023-09-25 000954.png)
