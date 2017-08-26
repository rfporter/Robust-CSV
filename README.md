# Robust CSV
v1.1.0

Copyright © 2014, Ryan Porter
All rights reserved.

Author:	 Ryan Porter
LAVA Name: Porter
Contact Info:	Contact via PM on lavag.org

LabVIEW Versions:
LV 2013 (Windows)
LV 2012 (Windows)
LV 8.6 (Windows)

Dependencies:
LAVA Palette

Description:
This package contains VIs for reading and writing to CSV files that follow the CSV format outlined in RFC-4180 (see http://tools.ietf.org/html/rfc4180). Using this package, you can properly import CSV files that were exported from spreadsheet programs such as Microsoft Excel, Open Office or LibreOffice Calc as well as export CSV files that will be compatible with any program capable of interpreting CSV files.
 
This implementation of the CSV format is capable of handling escaped fields such as those containing commas (or other field delimiters), multiple lines, and double quotes.

Installation and instructions:
Install VIP package using JKI VI Package Manager.

Examples:
"<LabVIEW>\examples\LAVA\Robust CSV\Robust CSV Example Usage.vi"	Demonstrates usage of the Read CSV and Write CSV file.

Known Issues:
none

Acknowledgements:
Phillip Brooks: "Parse CSV String.vi" is a modified version of his "CSV Data File Parser.vi". His method of parsing the CSV string was much more efficient than my original implementation.

Version History:
v1.0.0: Initial release of the code.
v1.0.1: Modified "Flatten to CSV Record.vi" to play nice with Excel CSV import when multi-line cells are present.
v1.1.0: Moved to LAVA palette & built to VI package file.

License:
Distributed under the BSD 2-Clause (http://opensource.org/licenses/BSD-2-Clause)
See link for a full description of the license.

Support:
If you have any problems with this code or want to suggest features go to lavag.org and Navigate to LAVA > Resources > Code Repository (Certified) and
search for the "Robust CSV" support page. Or try this link: http://lavag.org/files/file/239-robust-csv/

Distribution:
This code was downloaded from the LAVA Code Repository found at lavag.org
