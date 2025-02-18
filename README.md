# Supply Chain Visualization Using File Handling in Python

## Project Overview
This project is designed to visualize supply chain data using Python by handling Excel files and generating graphical representations. The program reads sales data from two Excel files, compares the data, and generates insights such as total sales profit, item-wise sales trends, and the most sold items. The results are visualized using Matplotlib graphs.

## Features
- Reads and processes multiple Excel files.
- Compares sales data from two selected files.
- Displays key statistics such as total sales profit and most sold items.
- Generates line and bar graphs for better visualization.
- Stores past records in a text file for reference.
- Allows users to delete stored records.

## Requirements
### Hardware:
- A computer with Windows/Linux/macOS.

### Software & Libraries:
- Python 3.x
- OpenPyXL (`pip install openpyxl`)
- Matplotlib (`pip install matplotlib`)

## File Structure
```
F:\Python-project\exelfoldersheets\  # Directory containing Excel files
records.txt  # Stores past sales records
main.py  # Python script to run the project
```

## Installation & Setup
1. Install Python 3.x if not already installed.
2. Install required dependencies using:
   ```bash
   pip install openpyxl matplotlib
   ```
3. Ensure that your Excel files (.xlsx) are placed inside the `exelfoldersheets` directory.
4. Run the script using:
   ```bash
   python main.py
   ```

## How to Use
1. Enter the username and password (default password: `0987`).
2. Select any two existing Excel files from the directory for comparison.
3. View the total sales profit for each file.
4. Identify the most sold item in each dataset.
5. Analyze the sales data through generated graphs.
6. Optionally, delete stored records if needed.
7. Exit the program when done.

## Graphical Representation
- **Sales in First Sheet** (Bar Graph)
- **Sales in Second Sheet** (Bar Graph)
- **Sales Trend Comparison** (Line Graph)

## Output Examples
```
Total sales profit in sheet 1 is Rs. XXXX
Total sales profit in sheet 2 is Rs. YYYY
Most sold item in sheet 1: Item A (ZZZ units)
Most sold item in sheet 2: Item B (YYY units)
```

## Security
- Password protection is implemented to restrict unauthorized access.
- Users can reattempt login if the password is incorrect.

## Future Enhancements
- Implementing a GUI for better user interaction.
- Adding real-time database integration for dynamic updates.
- Improving error handling and logging mechanisms.



