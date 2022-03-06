Сделал форк Котлин2020
Создал папку gitHomework и клонировал туда этот форк
Командой *git remote add upstream-my* указал KotlinAsFirst2021 в качестве апстима
Создал ветку backport *git branch backport* и переместился туда *git checkout backport*
Замёрджил backport и upstream-my *git merge remotes/upstream-my/master*
Запушил backport *git push origin backport:backport*
Сделал второй апстрим upstream-treirs и смёрджил его и upstream-my в ветке master
Затем создал файл remotes *> remotes* и записал в него вывод из *git remote -v*
и комитнул *git add remotes* *git commit -m "Добавил файл remotes"*
Создал файл howto.md и записал сюда ход работы.
