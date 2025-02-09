Get-ChildItem -Filter *.php | ForEach-Object { Rename-Item $_.FullName -NewName ($_.Name -replace '\.php$', '.html') }
