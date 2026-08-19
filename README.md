# MLTox

MLTox is a browser-based application for predicting molecular phototoxicity and inspecting the factors behind each prediction.

The complete chemistry engine, trained model, reference data, and interface are embedded in a single HTML file. Analysis runs locally using WebAssembly, with no server, account, database, or network connection required.

**Live application:** [mltox.online](https://mltox.online/)

## Features

- Phototoxicity prediction from compound names or SMILES
- Batch analysis of up to 20 compounds
- Molecular structure visualization
- Molecular attribution heatmaps
- Exact TreeSHAP feature contributions
- Original MLTox molecular descriptors
- Static reference outcomes for known compounds
- Expandable detailed results
- PDF report export through the browser print dialog
- Fully responsive interface
- Completely local and offline inference

## Privacy

All molecular processing and inference happen inside the browser.

MLTox does not upload compounds, store results, use analytics, or communicate with an inference server. Once loaded, the application can operate without an internet connection.
# mltox-wasm
# mltox-wasm
