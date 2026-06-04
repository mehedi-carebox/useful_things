# Useful Things


**uninstall all pip packages :**  `pip uninstall -r requirements.txt -y`  

**add comma end of allline (vim):**  `:%norm A,`

**add quote begin of allline (vim):**  `:%norm I"`

**add quote begin and end of allline(vim) :** `:%s/^\(.*\)$/"\1"/`

**create file with directory(bash):** `install -D /dev/null data/logs/app.log`

**Auto Locking Screen(CRON):** `*/60 * * * * loginctl lock-session 2`
