# COM424 Lab Exercises

## 1. Setup Instructions
1. Install Python 3.10 - configure PATH to run from console terminal
2. Create virtual environment named `com424` in project directory
```bash
python -m venv com424
```
3. Activate virtual environment as follows
- On UNIX systems
    ``` bash 
    source ./com424/bin/activate
- Windows
    ``` bash
    .\com424\Scripts\activate
    ```
4. Install packages specified in the `requirements.txt` file using `pip` - Python's package manager with virtual environment activated
```bash    
pip install -r requirements.txt
```