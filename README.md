# Turkish Character Replacer

This PowerShell script recursively renames all files and folders by replacing Turkish characters with their English equivalents.

## Example
Before:
C:\Projects\şifre\öğrenci.txt

After:
C:\Projects\sifre\ogrenci.txt

## Usage
1. Save the script as `rename-turkish.ps1`
2. Run PowerShell as Administrator
3. Navigate to the target folder:
   ```powershell
   cd "C:\path\to\your\folder"
   
Execute:
.\rename-turkish.ps1

Replacements
Turkish	English
ç	c
ğ	g
ı	i
ö	o
ş	s
ü	u
Ç	C
Ğ	G
İ	I
Ö	O
Ş	S
Ü	U
