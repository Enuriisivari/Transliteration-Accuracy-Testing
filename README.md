
# Transliteration Test Automation - IT23357426

This script runs UI test automation for the **https://www.pixelssuite.com/transliteration** page using Playwright + Python and writes results back to an Excel file.

---

## Requirements (Download/Install First)

1. **Python 3.10+**
   - https://www.python.org/downloads/

2. **Google Chrome** 
   - https://www.google.com/chrome/

3. **Python packages**
   ```bash
   pip install playwright openpyxl
   ```

> You do **NOT** need to install Playwright browsers if you are using your local Chrome.

---

## Files Needed


Place these files in the same folder:

```
IT23357426.py
Assignment 1 - Test cases.xlsx
README.md
```

---


## Run Command

```bash
python IT23357426.py --browser-executable "C:\Program Files\Google\Chrome\Application\chrome.exe"
```

---

## Optional Arguments

| Argument | Description |
|---------|-------------|
| `--excel` | Path to Excel file |
| `--sheet` | Excel sheet name |
| `--headless` | Run without showing the browser |
| `--wait-ms` | Wait time after clicking Translate |
| `--retries` | Retry count if output is empty |

Example:

```bash
python IT23357426.py --excel "Assignment 1 - Test cases.xlsx" --headless
```

---

## Output

The script writes:

- **Actual output**
- **PASS / FAIL / COLLECTED**

directly into the same Excel file.

---

## Notes

If Chrome is in another location, update the path in the `--browser-executable` flag.