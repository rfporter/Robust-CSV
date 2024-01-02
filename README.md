# Robust CSV for LabVIEW
This package contains VIs for reading and writing to CSV files that follow the CSV format outlined in RFC-4180 (see http://tools.ietf.org/html/rfc4180). Using this package, you can properly import CSV files that were exported from spreadsheet programs such as Microsoft Excel, Open Office or LibreOffice Calc as well as export CSV files that will be compatible with any program capable of interpreting CSV files.
 
This implementation of the CSV format is capable of handling escaped fields such as those containing commas (or other field delimiters), multiple lines, and double quotes.

# Installation and instructions
Install the VIP package using JKI VI Package Manager 2020 or newer.

# Dependencies
- LabVIEW >= 2012
- LAVA Palette

Development should be performed on LabVIEW 2012.

# Examples
Examples are located in <LabVIEW>\examples\LAVA\Robust CSV\
- "Robust CSV Example Usage.vi"	Demonstrates usage of the Read CSV and Write CSV file.

# Version History
- v1.0.0: Initial release of the code.
- v1.0.1: Modified "Flatten to CSV Record.vi" to play nice with Excel CSV import when multi-line cells are present.
- v1.1.0: Moved to LAVA palette & built to VI package file.
- v1.2.0: Marked VIs for re-allocated clone re-entrant execution.

# Distribution
Source code of this project is located here: https://github.com/rfporter/Robust-CSV

Stable releases are available on VIPM: https://www.vipm.io/package/lava_lib_robust_csv/

# Support
Author:	Ryan Porter  
LAVA Name: Porter  
Contact Info: Contact via PM on lavag.org

If you have any problems with this code or want to suggest features please join the discussion here: https://lavag.org/topic/18027-cr-robust-csv/

# Acknowledgements
- Phillip Brooks: "Parse CSV String.vi" is a modified version of his "CSV Data File Parser.vi". His method of parsing the CSV string was much more efficient than my original implementation.

# Licenses
Robust CSV for LabVIEW  
Copyright (c) 2014, Ryan Porter  
Distributed under the BSD 2-Clause (http://opensource.org/licenses/BSD-2-Clause)

# Build Instructions
To build a VIP package from the project's development code, you need to first run the source distribution build specification. Then build the package using the project's vipb file and VI Package Manager.

