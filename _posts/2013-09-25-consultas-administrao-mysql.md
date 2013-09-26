---
layout: post
title: "Consultas administração MySQL"
---

Listar todos usuários:

	SELECT User FROM mysql.user GROUP BY User

Corrigir problema citado pela mensagem “Connection for controluser as defined in your configuration failed” no phpmyadmin.

	GRANTT ALL PRIVILEGES ON phpmyadmin.* TO 'phpmyadmin'@'localhost' IDENTIFIED BY '[pass]';

\[pass\] é a senha do usuário phpmyadmin. Pode ser pego no arquivo `/etc/phpmyadmin/config-db.php`.
