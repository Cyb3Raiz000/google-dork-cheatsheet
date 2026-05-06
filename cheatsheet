# === EXPOSED FILES ===
site:target.com filetype:env
site:target.com filetype:log
site:target.com filetype:sql
site:target.com filetype:bak
site:target.com ext:conf OR ext:config OR ext:cfg
site:target.com ext:xml intext:password

# === ADMIN PANELS ===
site:target.com inurl:admin
site:target.com inurl:login
site:target.com intitle:"admin panel"
site:target.com inurl:dashboard
site:target.com inurl:wp-admin

# === DIRECTORY LISTING ===
site:target.com intitle:"index of /"
site:target.com intitle:"index of" "parent directory"
site:target.com intitle:"index of" passwd
site:target.com intitle:"index of" ".git"

# === SENSITIVE DATA ===
site:target.com intext:"api_key"
site:target.com intext:"secret_key"
site:target.com intext:"Authorization: Bearer"
site:target.com filetype:xls intext:password
site:target.com filetype:pdf "confidential"

# === ERROR PAGES (leak tech stack) ===
site:target.com intext:"sql syntax near"
site:target.com intext:"Warning: mysql_fetch"
site:target.com intext:"ORA-01756"
site:target.com intext:"Microsoft OLE DB"
site:target.com intext:"Stack trace:"

# === SUBDOMAINS ===
site:*.target.com
site:*.*.target.com

# === LOGIN PAGES ===
site:target.com inurl:login filetype:php
site:target.com intitle:"Please Login"

# === CAMERA / IoT ===
intitle:"webcamXP 5" site:target.com
inurl:"/view/index.shtml" site:target.com
