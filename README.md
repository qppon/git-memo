«Разгитить» папку, если что-то пошло не так: rm -rf .git

Добавить все изменённые файлы можно без ключа --all через добавление текущей папки. В таком случае все файлы в ней тоже  станут частью репозитория. Обратиться к текущей папке в терминале позволяет точка(.)

Коммит репозитория
Git commit

Генерация SSH-ключа
ssh-keygen -t ed25519 -C "<ВАШ EMAIL при регистрации в GitHub>"

Сохранить SSH-ключ в Keychain
ssh-add --apple-use-keychain ~/.ssh/id_ed25519

Чтобы запушить репозиторий:
git remote add origin git@github.com:[YOUR USER NAME]/[FILE NAME].git
git branch -M main
git push -u origin main

Чтобы запушить репозитория
Git push

Клонировать репозиторий
git clone git@github.com:<ВАШ НИКНЕЙМ>/first-project-git.git second-project-git
cd second-project-git

Чтобы получить текущую версию репозитория
Git pull

git branch — просматриваем ветки проекта

git branch <название_ветки>: создаём ветку

git checkout <название_ветки>: переключаемся между ветками

git merge new_branch - объединили ветки


