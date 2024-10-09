# Sort and Save the Data Table in LabVIEW

This LabVIEW project provides a solution for sorting and saving a data table with multiple columns. The program allows for sorting based on user-defined criteria and saves the sorted data into a file for further analysis or reporting.

## Key Features

1. **Data Input**:  
   The program accepts multi-column data as input. Users can define their data table with specific row and column values.

2. **Sorting Mechanism**:  
   The program features a sorting functionality that allows the user to sort the data based on a specific column. The sorting algorithm ensures accurate ordering of the data in ascending or descending order as per the user’s choice.

3. **User-Defined Sorting**:  
   - The user selects the column by which to sort the data.
   - Sorting can be performed on any selected column, and the entire data set is rearranged accordingly.
   
4. **Saving to File**:  
   After sorting, the user can save the sorted data to a specified file location. The saved file format is compatible with common data processing tools.

## Program Workflow

1. **Initialize Data Table**:  
   The program begins by loading or initializing a data table with multiple columns. This data is displayed to the user for review.
   
2. **Column Selection for Sorting**:  
   The user selects the column that they wish to sort by using a drop-down or input field. The program ensures that the sorting applies to all rows, rearranging them based on the values in the chosen column.
   
3. **Sorting Execution**:  
   The data is sorted using a built-in sorting algorithm. Sorting can be in ascending or descending order, which the user specifies.

4. **Saving Sorted Data**:  
   Once the sorting is complete, the user can choose a file location where the sorted data will be saved. The file can be stored in a text-based or spreadsheet format for later analysis or reporting.

5. **Error Handling**:  
   The program incorporates error handling to ensure that data sorting and saving are performed smoothly. If any issues arise (e.g., invalid input or file save errors), they are handled, and meaningful feedback is provided to the user.

## Inputs and Outputs

- **Input**:  
  A multi-column data table for sorting, with each column representing a different data field.
  
- **Output**:  
  - A sorted data table displayed to the user.
  - A file containing the sorted data, saved in a specified location.

## How to Use

1. Load or enter the data into the program.
2. Select the column to sort by from the available columns.
3. Choose the sorting order (ascending or descending).
4. Save the sorted data to a file by selecting the desired file format and location.

## Requirements

- **LabVIEW** version XX.X or later
- Any required toolkits for handling file input/output operations

## Notes

- Ensure that the data format is correct before inputting it into the program.
- If sorting by a numeric column, ensure that all values in that column are numbers to avoid errors.

## Code
![image](https://github.com/user-attachments/assets/22736e6e-9c65-4ca0-9c52-3a1f195dbd6c)
![image](https://github.com/user-attachments/assets/e6f42087-9f63-420f-a879-46ac0d6fec85)
![image](https://github.com/user-attachments/assets/ff65a0b7-b4c0-409b-95cd-c4f293930e92)
![image](https://github.com/user-attachments/assets/3fb722f7-0181-4caa-82fe-91ac30b05de7)
![image](https://github.com/user-attachments/assets/3983f116-a6b8-4470-84ae-086c533214f6)
![image](https://github.com/user-attachments/assets/b78d8350-4037-4673-8f67-70be48c0db05)
![image](https://github.com/user-attachments/assets/382a787f-c4bb-4827-a458-4a7de0893aad)
![image](https://github.com/user-attachments/assets/26a1e6d2-5e55-451c-aeea-5f7641815816)
