# Estadistica

Statistics coursework notebooks using Python and Jupyter, covering descriptive statistics concepts such as mean, median, mode, variance, standard deviation, and data visualization.

## Tech Stack

- Python 3.x
- NumPy
- SciPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Structure

```
Estadistica/
├── homework_clase01_resuelto.ipynb   # Class 1 homework: descriptive statistics with NumPy, Pandas, and Matplotlib
├── requirements.txt                  # Python dependencies
├── .gitignore                        # Git ignore rules
├── LICENSE                           # MIT License
└── README.md                         # Project documentation
```

## Setup / Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/dinnocenzo/Estadistica.git
   cd Estadistica
   ```

2. **Create and activate a virtual environment** (recommended)

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

## Usage

Open any `.ipynb` file from the Jupyter Notebook interface in your browser. Each notebook is self-contained and demonstrates statistical concepts applied to sample datasets.

**Example — running a notebook directly from the command line:**

```bash
jupyter nbconvert --to notebook --execute homework_clase01_resuelto.ipynb
```

### Topics Covered

- **Descriptive statistics**: mean, median, mode, variance, standard deviation, coefficient of variation
- **Data structures**: NumPy arrays, Pandas DataFrames
- **Visualization**: histograms using Matplotlib
- **Outlier analysis**: effect of outliers on mean and standard deviation

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
