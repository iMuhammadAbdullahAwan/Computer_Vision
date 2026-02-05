# Quiz_2 Folder

Contents: Dollar bill detection quiz notebook and dataset notes.

Main notebook
- Dollar_Bill_Detection_Quiz2.ipynb — CNN training, evaluation, and simple prediction visualization.

Dependencies (example)
- Python 3.8+
- tensorflow
- matplotlib

Install example

```powershell
pip install tensorflow matplotlib
```

How to run
1. Open `Dollar_Bill_Detection_Quiz2.ipynb` in Jupyter / Colab.
2. Ensure the dataset is available. The notebook expects a `Bill_dataset.zip` or a `train/` and `test/` layout.
3. Run cells sequentially. The notebook will save `best_model.h5` and `final_model.h5` in the working directory.

Reports
- Place analysis, plots, or writeups in a `reports/` directory inside `Quiz_2/`.

Notes
- The notebook splits a provided dataset into `train/` and `test/` and now uses a validation split during training.
- If running on limited hardware, reduce `batch_size` or `img_size` in the notebook.
