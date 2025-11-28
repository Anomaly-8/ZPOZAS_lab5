# Лабораторная работа №5. Методологии SAST и DAST. Триаж уязвимостей
## Практическая часть (SAST-анализ)

1) Анализ уязвимого файла с помощью утилиты bandit.

<img width="1277" height="834" alt="image" src="https://github.com/user-attachments/assets/4b884b85-14ad-4b2a-8919-c2f2b504914c" />
<img width="1277" height="612" alt="image" src="https://github.com/user-attachments/assets/2c69f9bd-e3e2-43bd-b18f-4de68982cbee" />

3) Анализ уязвимого файла с помощью других утилит.

В нашем случае не получилось просканировать уязвимый файл с помощью альтернативных средств, таких как semgrep (при использовании различных аргументов команды сканирования происходили одни и те же ошибки "permission denied" или "read time out") или SonarQube (при генерации токена оперативная память была критически перегружена, что повлекло за собой прекращение работы виртуальной машины).
<img width="1109" height="858" alt="image" src="https://github.com/user-attachments/assets/61b3537a-f346-422d-a329-bc4f8b8225dc" />

3) Сравнительный анализ.

Поскольку на установку и использование утилиты bandit ушло ЗНАЧИТЕЛЬНО меньше времени и ресурсов машины чем на semgrep или SonarQube (которые в конечном итоге даже не привели результаты своей работы), очевидный ввод - bandit является самой лучшей программой для SAST-анализа.

## Практическая часть (DAST-анализ)

1) Приложение

<img width="681" height="588" alt="image" src="https://github.com/user-attachments/assets/c77d2c2b-9028-4c5c-8e12-af31aeea991a" /> 
<img width="496" height="230" alt="image" src="https://github.com/user-attachments/assets/3884ab15-3306-4d45-a46e-b1ea35c03b70" />
<img width="556" height="221" alt="image" src="https://github.com/user-attachments/assets/8aae23ee-145a-4bc5-9e58-b0cbc145f2a8" /> 
<img width="524" height="310" alt="image" src="https://github.com/user-attachments/assets/a34573f3-ea2d-4452-a579-8573f3657735" />
<img width="563" height="269" alt="image" src="https://github.com/user-attachments/assets/a7d191fb-5499-4e8b-83e0-a5e8c15c72fa" /> 
<img width="639" height="295" alt="image" src="https://github.com/user-attachments/assets/f49f9865-0321-43e4-8a83-3241961b45c0" />
<img width="903" height="285" alt="image" src="https://github.com/user-attachments/assets/fb34ce3b-a7f0-40d4-9c06-3c85e5190d82" />

2) Анализ уязвимого файла с помощью OWASP ZAP
<img width="808" height="573" alt="image" src="https://github.com/user-attachments/assets/daaea0a4-4a4c-4020-b674-195e6a356799" />
<img width="891" height="790" alt="image" src="https://github.com/user-attachments/assets/f55a0b5d-c18c-42d4-8c04-e7833ad71d5b" />
<img width="813" height="465" alt="image" src="https://github.com/user-attachments/assets/4411aafa-f65f-48e9-bd94-56fbc2b2edb6" />
<img width="620" height="281" alt="image" src="https://github.com/user-attachments/assets/a6ad0edd-641b-4c2f-866e-7da69d57b433" />
<img width="803" height="537" alt="image" src="https://github.com/user-attachments/assets/2387c0ff-d95b-496a-ad8d-09c793b4684f" />

Скан и Фаззинг

<img width="894" height="314" alt="image" src="https://github.com/user-attachments/assets/306f5cb9-974e-403c-ac0c-b5dfc8e86ebd" />
<img width="1137" height="196" alt="image" src="https://github.com/user-attachments/assets/14bb6ac8-0e73-41d0-a631-0894eee2d2ee" />

## Практическая часть (триаж уязвимостей)



