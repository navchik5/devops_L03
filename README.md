## Отчёт по практическому заданию П03: «Практика Git»

### 1. Цель работы

Изучение базовых приёмов работы с системой контроля версий Git: настройка окружения, работа с локальным и удалённым репозиторием, ветвление, разрешение конфликтов слияния.

### 2. Ход выполнения

##### 2.1. Установка и настройка Git

Проверена установка Git в системе и заданы глобальные параметры пользователя (user.name, user.email).

<img width="875" height="311" alt="Снимок экрана 2026-09-30 182554" src="https://github.com/user-attachments/assets/f8639f7e-066f-44f2-b552-1b0831967bcb" />

<img width="752" height="104" alt="Снимок экрана 2026-09-30 182930" src="https://github.com/user-attachments/assets/5fc0a01f-66c1-4cbd-81e9-f587116ee55b" />

##### 2.2. Генерация SSH-ключа

Сгенерирован ключ ed25519, запущен ssh-agent, ключ добавлен в агент, публичный ключ скопирован для добавления в профиль GitHub.

<img width="949" height="649" alt="Снимок экрана 2026-09-30 183320" src="https://github.com/user-attachments/assets/ea568b89-21ef-467f-b990-29a0963fd30f" />

<img width="1184" height="177" alt="Снимок экрана 2026-09-30 183340" src="https://github.com/user-attachments/assets/b5266db8-e061-4056-9a36-aadd85d6ab4c" />

<img width="1439" height="496" alt="Снимок экрана 2026-10-08 161336" src="https://github.com/user-attachments/assets/33a69841-bbc2-497c-a809-176877c266a8" />

##### 2.3. Создание локального репозитория

Создан каталог devops_lab3, инициализирован репозиторий, добавлен файл README.md, выполнен первый коммит.

<img width="484" height="210" alt="Снимок экрана 2026-09-30 184018" src="https://github.com/user-attachments/assets/ada5de5d-892c-4f3c-8f7f-c88178edc550" />

<img width="382" height="118" alt="Снимок экрана 2026-09-30 184134" src="https://github.com/user-attachments/assets/93e236d3-f8b0-4252-a570-112d64bcd584" />

##### 2.4. Привязка удалённого репозитория и push

Создан пустой репозиторий на GitHub, выполнена привязка origin, переименование ветки в main и первый push.

<img width="551" height="158" alt="Снимок экрана 2026-09-30 184406" src="https://github.com/user-attachments/assets/0ca9c24b-058d-4317-a0f8-5112254162cb" />

##### 2.5. Создание и разрешение конфликта слияния

Внесены изменения в локальную версию файла и в версию на GitHub. При попытке push получен отказ. Выполнен git pull, возник конфликт слияния в README.md. Конфликт разрешён вручную, изменения зафиксированы и отправлены на сервер.

<img width="460" height="142" alt="Снимок экрана 2026-09-30 184603" src="https://github.com/user-attachments/assets/2165096b-a4a1-4a6e-9c41-88143ce3aabe" />

<img width="458" height="158" alt="Снимок экрана 2026-09-30 184726" src="https://github.com/user-attachments/assets/dc05f552-81e8-4ec4-9b3a-97d8ac0a5cf8" />

<img width="499" height="176" alt="Снимок экрана 2026-09-30 185123" src="https://github.com/user-attachments/assets/647986b4-f330-4d95-8196-875abac57f58" />

##### 2.6. Работа с ветками

Создана ветка FEAT-123, внесены изменения, коммит отправлен на сервер с включением отслеживания. Затем ветка слита в main и изменения отправлены на сервер.

<img width="455" height="192" alt="Снимок экрана 2026-09-30 185624" src="https://github.com/user-attachments/assets/57416c43-7576-40fd-a8f0-bd592606d99a" />

<img width="1441" height="752" alt="Снимок экрана 2026-10-08 161434" src="https://github.com/user-attachments/assets/7c391f0e-381b-4520-a3d2-da24af5d481c" />

### 3. Итог

В ходе работы были освоены: настройка Git, генерация и подключение SSH-ключа, создание и привязка репозиториев, работа с ветками, разрешение конфликтов слияния. Все изменения успешно синхронизированы с удалённым репозиторием на GitHub.








