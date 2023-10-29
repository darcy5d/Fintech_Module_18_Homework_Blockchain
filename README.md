# Fintech_Module_18_Homework_Blockchain
A repo for my homework assignment for Module 18 - Blockchain

# PyChain Ledger

The PyChain Ledger is an implementation of a basic blockchain ledger, developed using Python and visualized using Streamlit. The goal of the project was to further understand the architecture of blockchains by building a rudimentary version and enabling basic transactions.

![Genesis Block & Successful Block Creation](https://github.com/darcy5d/Fintech_Module_18_Homework_Blockchain/blob/main/screengrabs/01_gif.gif?raw=true)

## Steps Undertaken:

### 1. **Creation of Record Data Class**

The `Record` data class was developed to provide a structured representation of transactions, which includes the sender, receiver, and amount attributes.

### 2. **Modification of the Block Data Class**

The existing `Block` data class was modified to replace the generic `data` attribute with a `record` attribute, which is an instance of the `Record` class.

### 3. **Incorporating User Inputs in Streamlit Interface**

User interface elements were added using Streamlit to capture user inputs for the sender, receiver, and transaction amount. The UI then allows the creation of a new block with this record.

### 4. **Testing the PyChain Ledger**

The PyChain Ledger was tested using the Streamlit interface, allowing multiple blocks to be created and added to the ledger.

![Block Inspector](https://github.com/darcy5d/Fintech_Module_18_Homework_Blockchain/blob/main/screengrabs/02_gif_block_inspector.gif?raw=true)
![Validated Chain with Adjusted Difficulty](https://github.com/darcy5d/Fintech_Module_18_Homework_Blockchain/blob/main/screengrabs/03_gif_validated_chain.gif?raw=true)

### How to Run:

1. Navigate to the project directory.
2. Run the Streamlit application with the command `streamlit run pychain.py`.
3. Use the interface to create blocks and inspect them.
4. Validate the chain at any time using the "Validate Chain" button.
