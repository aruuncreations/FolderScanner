# FolderScanner
A lightweight tool that scans folders and generates an Excel report with file details and clickable hyperlinks for easy retrieval.
Overview

This project provides a simple tool to scan all files in a directory and its subdirectories, generating an interactive HTML report (file_scanner_results.html). The report includes file details like type, path, name, size, and modification date, with features for searching, sorting, filtering, and opening folders directly in Windows Explorer.

The tool is distributed as a standalone executable (folder_scanner_html_new.exe) for Windows, so you don’t need Python installed to use it.

Features





Scan Files: Recursively scans the current directory and subdirectories for all files (excluding .html files).



Generate HTML Report: Creates an interactive file_scanner_results.html with:





🔍 Search by file name, path, or type.



🎯 Filter by file type using a dropdown.



📊 Sort by clicking column headers (e.g., file type, size).



📁 Open folder paths in Windows Explorer by clicking them.



📋 Copy file paths to the clipboard.



💾 Export filtered results to a new file.



User-Friendly Output: Displays a pop-up message (via tkinter) when the scan is complete, showing the number of files found and the path to the HTML report.



File Size Formatting: Converts file sizes to human-readable formats (e.g., KB, MB, GB).



File Type Statistics: Shows a summary of file types and their counts in the report.

Download





Download the executable: folder_scanner_html_new.exe





Note: Replace link-to-your-release with the actual GitHub release link after uploading (see below for upload instructions).

Usage





Run the Executable:





Place folder_scanner_html_new.exe in the directory you want to scan.



Double-click the .exe to run it.



The tool will scan the directory and its subdirectories.



View Results:





Once the scan is complete, a pop-up will confirm the creation
