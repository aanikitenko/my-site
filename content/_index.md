---
title: 'Home'
date: 2025-03-20
type: landing
sections:
  - block: resume-biography
    content:
      username: me
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      avatar:
        size: medium
        shape: circle

  - block: features
    content:
      title: "🏆 Мои достижения"
      items:
        - name: "Лыжные гонки"
          description: "Чемпионка области 2022, 2023, 2024<br>Многократный победитель чемпионатов области"
          icon: "skiing"
          icon_pack: "fas"
        - name: "Спортивное ориентирование"
          description: "7 место на Чемпионате России<br>Призер всероссийских соревнований"
          icon: "map"
          icon_pack: "fas"
        - name: "Математика"
          description: "Победитель региональной олимпиады по математике (2024)"
          icon: "calculator"
          icon_pack: "fas"
    design:
      columns: '3'
      spacing:
        padding: ['2rem', 0, '2rem', 0]

  - block: collection
    content:
      title: "📝 Последние записи"
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
