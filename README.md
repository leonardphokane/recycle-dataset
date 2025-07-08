# 🗂️ Data Directory

This project’s training and test datasets are **not included** in the Git history to keep the repository lightweight and GitHub-compliant.

## 🔍 Excluded Folders

The following directories are ignored via `.gitignore`:

- `recycle_model/` – TensorFlow/Keras saved model directory
- `Toxic/`, `Organic/`, `Residue/`, `Paper/`, `Plastic/`, `Glass/`, `Metal/` – Image datasets for recyclable classification

## 📦 How to Rehydrate the Data

Download the datasets and model files from:

- [Google Drive Folder](https://drive.google.com/your-link-here)

Place them back into the root directory like this:

project/ ├── recycle_model/ ├── Toxic/ ├── Organic/ └── ...

Download the trained model files from:

- [`recycle_model.keras`](https://huggingface.co/your-model-link)
- [`recycle_model.tflite`](https://drive.google.com/your-link-here)

Place them in the `recycle_model/` directory:

project/ └── recycle_model/ ├── recycle_model.keras └── recycle_model.tflite


## 📝 Notes

- For questions or dataset access, contact [leonardphokane](mailto:your-email@example.com)
