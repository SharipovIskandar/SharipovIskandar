# Salom!

Joriy vaqt: **2024-07-21 15:30 UTC**

Men [Ism](https://github.com/SharipovIskandar) (GitHub username) dasturchiman va ... 

from datetime import datetime

# Joriy vaqtni olish
current_time = datetime.now().strftime("%Y-%m-%d %H:%M:%S")

# README.md faylini o'qish va vaqtni qo'shish
with open('README.md', 'a') as file:
    file.write(f'\n## So\'ngi yangilanish: {current_time}\n')

