ЗВІТ ПРО ВИКОНАННЯ КОМАНД GIT (GITHUB)

1. Перехід у папку проєкту:
cd /d/OPI_Magas/lab7_magas/lab7_start_git

2. Ініціалізація локального репозиторію:
git init

3. Налаштування локального користувача (не зачіпає глобальний проєкт):
git config --local user.name "Diana-Magas"
git config --local user.email "dianamagas23@gmail.com"


4. Створення файлу ігнорування (згідно з п. 7.2):
echo *.txt >> .gitignore

5. Перевірка статусу:
git status

6. Додавання файлів до індексу:
git add .

7. Створення першого коміту (п. 7.3):
git commit -m "02.05.2026 19:15 Initial commit for GitHub"

8. Додавання віддаленого репозиторію GitHub:
git remote add origin https://github.com/Diana-Magas/lab7_start_git.gits

9. Відправка змін на сервер (гілка master):
git push -u origin master

10. Клонування проєкту для іншого користувача (п. 7.4):
cd ..
mkdir lab7_user2_git
cd lab7_user2_git
git clone https://github.com/Diana-Magas/lab7_start_git.git