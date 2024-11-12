# LR6
Лабораторная работа №6
1. Создём форк репозитория
![image](Скриншоты/1.jpg)</br>
2. Заполняем имя пользователя и адрес электронной почты </br>
![image](Скриншоты/2.jpg)</br>
3. Делаем клонирование удаленного репозитория</br>
![image](Скриншоты/3.jpg)</br>
4. Добавляем файл на странице репозитория на GitHub</br>
![image](Скриншоты/4.jpg)</br>
5. Переходим в папку LR6 и добавляем изменения в локальный репозиторий
![image](Скриншоты/5.jpg)
6. Получаем историю для каждой ветки и смотрим последние три изменения ветки 
![image](Скриншоты/6.jpg)
7. Выполняем слияние и разрешаем конфликт </br>
7.1. Переходим в ветку brunch1 </br>
![image](Скриншоты/7.jpg)</br>
7.2. Выполняем слияние и получаем сообщение о конфликте</br>
![image](Скриншоты/8.jpg)</br>
7.3. Выясняем причину конфликта </br>
![image](Скриншоты/9.jpg)</br>
7.4. Меняем файл и решаем причину конфликта </br>
![image](Скриншоты/10.jpg)</br>
7.5. Добавляем содержимое рабочего каталога в индекс, чтобы совершить коммит </br>
![image](Скриншоты/11.jpg) </br>
7.6. Проверяем статус </br>
![image](Скриншоты/12.jpg)
8. Удаляем побочную ветку master </br>
![image](Скриншоты/13.jpg)</br>
9. Добавляем в индекс новый текстовый файл, проверяем статус, добавляем в индекс, делаем коммит</br>
![image](Скриншоты/14.jpg)</br>
10. Делаем изменения в file1.txt, добавляем их в индекс, делаем коммит </br>
![image](Скриншоты/15.jpg)
11. Проверяем статус, добавляем в индекс новый текстовый файл, делаем коммит </br>
![image](Скриншоты/16.jpg)
12. Делаем хард откат коммита </br>
![image](Скриншоты/17.jpg)</br>
12. Создаем ветку для отчета </br>
![image](Скриншоты/18.jpg)</br>
13. Отправляем все данные на удаленный репозиторий </br>
![image](Скриншоты/19.jpg)</br>
# Лог команд
git config global user.name/email </br>
git clone https://github.com/FrogFromTheSwamp/LR6.git </br>
cd LR6 </br>
git pull </br>
git reflog --all </br>
git log -p -3</br>
git checkout branch1 </br>
git merge master </br>
git diff </br>
git add mergefile.txt </br>
git status </br>
git commit -m "Branches merge"</br>
git status</br>
git commit -m "Delete branch master"</br>
git add file1.</br>
git commit -m "New change in the file1.txt"</br>
git status</br>
git add file2.txt</br>
git commit -m "New file2.txt"</br>
git reset --hard HEAD </br>
git checkout -b report </br>
git branch </br>
git push --set-upstream origin report </br>
 # История операций
a9eb337 2024-11-13 | New file2.txt (HEAD -> report, origin/report, branch1) [Группа 4316 Жукова А. А.]</br>
0bf799d 2024-11-13 | New change in the file1.txt [Группа 4316 Жукова А. А.]</br>
db4de96 2024-11-13 | New file [Группа 4316 Жукова А. А.]</br>
d20ca1a 2024-11-13 | Branches merge [Группа 4316 Жукова А. А.]</br>
a4556bd 2024-11-13 | Create Test (origin/master, origin/HEAD, master) [Арина Жукова]</br>
921f53b 2020-11-21 | Обновление информации [Kurtyanik]</br>
0f9f50d 2020-11-21 | Заполнил файл (origin/branch1) [Kurtyanik]</br>
c08a654 2020-11-21 | Файл создан пустым [Kurtyanik]</br>
3c6e913 2020-11-21 | Initial commit [Kurtyanik]</br>
