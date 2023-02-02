# BWS-Upgrade-Notes
Script to consolidate updatedatabase individual scripts into one for review.

## Usage 
Go to: 
```bash
installer/data/mysql/db_revs/
```
List files in the directory using: 
```bash
ls
```

To combine **all** files use:
```bash
cat *.pl > everything.txt
```

To combine only **a range** of desired files use:
```bash
cat {filename1..filename100}.pl > results.txt
```
Example: cat {220600000..220600077}.pl > results.txt

To view combined files use:
```bash
cat results.txt
```
-- replace with file name if changed from results.txt
