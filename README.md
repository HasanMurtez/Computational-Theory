# Computational-Theory

## Setup Instructions

### Prerequisites

- Python 3.12.1 or higher
- pip (Python package manager)
- Git

### Installation Steps

1. **Clone the repository:**

```bash
   git clone [https://github.com/HasanMurtez/Computational-Theory.git]
   cd computational-theory
```

. **Create a virtual environment:**

```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate

   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
```

. **Install dependencies:**

```bash
   pip install -r requirements.txt
```

. **Launch Jupyter Notebook:**

```bash
   jupyter notebook
```

. **Open `problems.ipynb`** in the Jupyter interface that opens in your browser.

### Running the Code

- All code is in `problems.ipynb`
- Run cells in order from top to bottom
- Use "Restart and then Run All" to execute all cells in sequence.
- All required imports are in the first code cell.

### Troubleshooting

If you encounter import errors:

```bash
pip install --upgrade numpy jupyter notebook
```

If Jupyter wont start:

```bash
pip install --upgrade jupyter-core jupyter-client
```
