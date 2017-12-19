# commands
pkill -f 'слово из процесса'  = убивает процесс где встречается слово 'слово из процесса'

ps ax = список запущеных процессов

ps ax | grep [template] = список процессов с уточнением, по ключевому слову [template]

kill -KILL [nomer] = удаление процесса по номеру прочесса [nomer]

crontab -l -u <user> = список крон тасков юзера
  
cat /var/spool/cron/crontabs/<user> = список крон тасков юзера
  
cd /var/spool/cron/crontabs/ && grep . * = список крон тасков всех юзеров
