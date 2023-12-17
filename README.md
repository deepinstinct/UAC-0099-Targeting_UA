# UAC-0099-Targeting_UA
UAC-0099 is a threat actor that targets Ukraine since mid-2022


# CVE-2023-38831 exploited during the campaing - POC
RARLAB WinRAR before 6.23 allows attackers to execute arbitrary code when a user attempts to view a benign file within a ZIP archive. The issue occurs because a ZIP archive may include a benign file (such as an ordinary .JPG file) and also a folder that has the same name as the benign file, and the contents of the folder (which may include executable content) are processed during an attempt to access only the benign file. This was exploited in the wild in April through October 2023
