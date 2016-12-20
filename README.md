# mytetra
Репозиторий базы знаний MyTetra

Скачать её можно с сайта разработчика (http://webhamster.ru/site/page/index/articles/projectcode/105). К заметке приложены файлы актуальны на момент написания заметки
Копируем содержимое архива в Programm files, создаем ярлык mytetra и копируем его в автозагрузку
<ui>
<li>Устанавливаем git</li>
<li>Регистрируемся на github.com </li>
<li>Запускаем Git Bash и пишем </li>
<li>	ssh-keygen.exe -t rsa -C 'email, с которым регались ГХ'</li>
<li>Создается ssh ключ в <каталог пользователя>/.ssh/</li>
<li>В этой же консоли делаем базовые настройки Git</li>
<li>  git config --global user.name "GitHub Login"</li>
<li>	git config --global user.emal "GitHub email"</li>
<li>Копируем публичный ключ (.pub) на ГХ в SSH keys (делается в настройках аккауна ГХ)</li>
<li>Форкаем репу https://github.com/SorokinRed/mytetra или просим у меня (sorokin.red@gmail.com) collaboration</li>
<li>Получили права на изменение или изменяете форк, не важно. Переходим к мясу</li>
<li>В настройках программы находим расположение директории с данными (data). По-умолчанию в C:\Users\<USER_NAME>\.config\mytetra\data и удаляем все содержимое</li>
<li>Жмем ПКМ -> Git Bash here. откроется консоль в текущем каталоге</li>
<li>клониуем репу на диск (в конце пробел с точкой, они нужны чтоб файлы скопировались в текущий каталог. А не в <current_dir>\<repo_name>\)</li>
<li>	git clone git@github.com:USER-NAME/mytetra.git . </li>
<li><s>Если не хотите делится с миром своими изменениями просто запускайте mytetra и работайте</s></li>
<li>В настройках mytetra добавляем строку синхронизации и протыкиваем нужные галки</li>
<li>	cd \ & cd "%a" & git add . & git commit -a -m MyTetraCommit & git pull -s recursive & git push</li>
<li>фывфыв</li>
</ui>
