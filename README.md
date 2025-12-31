# Chemical Graph Series

A journey from basic cheminformatics to advanced Graph Neural Networks (GNNs) and Transformers for molecular modeling.

## 🚀 Curriculum Overview

### Phase 1: Foundations of Cheminformatics
*   **01: Chemical Representations**: SMILES, InChI, and RDKit basics.
*   **02: Molecules as Graphs**: Atom-node mapping and NetworkX visualization.

### Phase 2: Graph Features & Spectral Analysis
*   **03: Featurization**: Node/Edge encoding and one-hot encoding.
*   **04: Positional Encodings**: Laplacian Eigenvectors and Random Walk Positional Encodings (RWPE).

### Phase 3: Graph Neural Networks (GNNs)
*   **05: Message Passing**: The core framework and Intro to PyTorch Geometric (PyG).
*   **06: Core Architectures**: GCN, GAT, and GIN.

### Phase 4: Advanced Modeling & Property Prediction
*   **07: Graph Transformers**: Global attention and edge feature integration.
*   **08: Property Prediction**: Training on ESOL/FreeSolv datasets.

## 🛠️ Setup

1.  **Environment**: Python >= 3.13 recommended.
2.  **Dependencies**:
    ```bash
    pip install rdkit torch torch-geometric networkx matplotlib pandas
    ```

## 📂 Project Structure
*   `notebooks/`: Interactive lessons and examples.
*   `src/`: Shared utility functions for featurization and model building.
