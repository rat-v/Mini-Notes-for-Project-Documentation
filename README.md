# Mini Notes for Project Documentation

Type out the full writeup on Google Docs
Save as docx
Use pandoc with **for %f in (*.docx) do pandoc "%f" -o "output\%~nf.md" --extract-media="output\%~nf"** in powershell to convert to markdown w/ images exported
Create a folder in the project repository as images/placeholder.txt/ . Upload all images to that folder
Run [powershell script](https://pastebin.com/bVf2627j)
Paste new md in github,  check if images are correct
