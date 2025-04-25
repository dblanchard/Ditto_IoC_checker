# Ditto_IoC_checker
Ditto is a powerful clipboard manager for Windows that can run scripts on the clipboard contents at time of copy and at time of paste. This ChaiScript (http://chaiscript.com/) enables Ditto to check a file of known indicators of compromise (by IP, domain name, or hash or add to the file at the user's discretion. Ditto also supports "friends" i.e. users on the same network can selectively share individual pieces of clipboard content.

## Example Use Case
A threat intelligence analyst receives a CISA or MS-ISAC report with some command and control IPs and a hash value for an image that is used in a phishing campaign. The analyst copies the IPs and hash value causing Ditto to check the file. If found, the script displays the existing record(s) including:
- IP
- Domain
- Filename
- Hash
- Timestamp
- Threat Level
- Source
- Description
- Campaign
- Attribution	Notes

The script will also allow the user to share the found data with Ditto "friends".

If the data aren't found, the user can choose to add it to the file.

