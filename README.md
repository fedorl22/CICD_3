# Процессы CI/CD
## Урок 3. Continuous delivery и continuous deployment (непрерывная доставка и развертывание)

1) Добавить 2 окружения "preprod" и "production".

2) Добавить отдельные deploy job для каждой среды.

3) Добавить переменную "$MyLogin" внутри .gitlab-ci.yml, которая будет меняться в зависимости от среды.

3) Добавить переменную "$MyPassword" не используя .gitlab-ci.yml, которая так же будет меняться в зависимости от среды.

4) Добавить скрипт в .gitlab-ci.yml, который найдёт все запущенные pipeline по названии ветки(ref) и остановит их.
