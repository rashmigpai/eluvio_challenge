Eluvio DS Intern Project
------------------------------------------

### Contents of table:

* `Report.md` ([report](Report.md) for the analysis containing problem definition, EDA and model training and prediction)
* `Eluvio.ipynb` (jupyter notebook containing the necessary analysis)
* `requirements.txt` (`pip freeze` of local python dependencies)

---
### Appendix

Hardware, Operating System and Python Spec
```bash
$ sw_vers
ProductName:	macOS
ProductVersion:	11.2
BuildVersion:	20D5042d

$ python --version
Python 3.8.7

$ system_profiler SPHardwareDataType 
Hardware:

    Hardware Overview:

      Model Name: MacBook Pro
      Model Identifier: MacBookPro14,2
      Processor Name: Dual-Core Intel Core i7
      Processor Speed: 3.5 GHz
      Number of Processors: 1
      Total Number of Cores: 2
      L2 Cache (per Core): 256 KB
      L3 Cache: 4 MB
      Hyper-Threading Technology: Enabled
      Memory: 16 GB
```
----
### Instructions to run the jupyter notebook

Please place the `Eluvio_DS_Challenge.csv` in the same folder as the `Eluvio.ipynb`

```bash
# Assuming you are in a virtual environment
(.venv)$ pip install -r requirements.txt
(.venv)$ jupyter notebook Eluvio.ipynb
```