# keepassX2lastpass
Python script to export KeePassX password vault to LastPass format 

Steps to run:

1. Export KeePassX file as csv.
2. Open KeePassX csv file in Excel, LibreCalc, or equivalent.
3. Save cvs file as xlsx file.
4. From a command line: python<version> keepassx2lastpass.py -i <step3filename>.xlsx -o <outputfilename>.txt -s <L for Linux, W for Windows, A for OSX>
5. Import to LastPass as a generic csv file.

