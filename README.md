# Experiment 4: Reproducibility Using Python & Git

## 1. Objective
To ensure project portability by documenting dependencies in a `requirements.txt` file and verifying the environment setup through a repository clone and re-installation process.

## 2. Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/Namanbhardwaj1/211-A.git
cd 211-A
```

### Step 2: Create and Activate Virtual Environment
```bash
python -m venv mlops
# Windows
mlops\Scripts\activate
# macOS / Linux
source mlops/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Run the Project
```bash
python main.py
```

Expected output:
```
Array: [1 2 3]
Sum: 6
```

## 3. Files in This Repository
| File | Description |
|------|-------------|
| `main.py` | Simple NumPy script demonstrating array operations |
| `requirements.txt` | Locked dependency versions for reproducibility |
| `README.md` | Setup and run instructions |

## 4. Observations & Learning
- **Version Locking**: `requirements.txt` prevents Dependency Drift by pinning exact library versions.
- **Portability**: Cloning and running in a fresh directory proves the project works on any machine.
- **Best Practices**: Combining Git versioning with Python environment management ensures work is shared and verifiable.

## 5. Conclusion
This experiment successfully demonstrated reproducibility by combining Git versioning with Python environment management, creating a robust pipeline that can be verified by anyone who clones the repository.
