# Character-AI-Project
Project to make a Character AI for Class.

## Run the Cortana demo

Open `index.html` from a local web server (for example, `python -m http.server`) in a modern browser. Press **Download model** to fetch the 4-bit `HuggingFaceTB/SmolLM2-360M-Instruct` model (approximately **230 MB**, depending on the exact browser-cached files). Transformers.js tries WebGPU first and falls back to WASM. The model is cached by the browser and, after its first download, generation runs locally on the device; no chat messages are sent to a server. A modern browser and an internet connection are required for the initial download.

The chat keeps only the latest four exchanges in its prompt to limit context use. Cortana's role prompt is written to cover memories through the events of *Halo 4*.
