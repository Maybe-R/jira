# Домашнее задание к занятию 7 «Жизненный цикл ПО»
#№ jira


Настроить её для своей команды разработки.
Создать доски Kanban и Scrum.

<img width="2503" height="1350" alt="image" src="https://github.com/user-attachments/assets/6323914f-436b-4407-9e72-9ea7ed118a9a" />

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.

<img width="2462" height="1226" alt="image" src="https://github.com/user-attachments/assets/feb94bd9-935a-4f92-9113-cb688d0d1692" />

Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.

<img width="2470" height="1206" alt="image" src="https://github.com/user-attachments/assets/58d59831-1943-49c1-9279-a7f6c594f322" />
