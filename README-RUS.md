----

<p align="center">
<a href="https://github.com/HorizonEmuTeam/Horizon-Emu/blob/main/README.md">English</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
Русский
&nbsp;&nbsp;
</p>

<div align="center">


![Latest Release](https://img.shields.io/github/v/release/HorizonEmuTeam/Horizon-Emu?style=flat-square&label=Последняя%20версия)
![Total Downloads](https://img.shields.io/github/downloads/HorizonEmuTeam/Horizon-Emu/total?style=flat-square&color=blue&logo=&label=Количество%20загрузок)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&color=white&logo=telegram&logoColor=blue)](https://t.me/HorizonEmuOfficial)

<p align="center">
	<img src="ProjectLogo.png" width="256" height="246" />  
</p>

<h1 align="center">Horizon Emu</h1>

<p align="center">
<strong>Horizon Emu - это приложение, которое позволяет вам запускать программы созданные для Windows x86_64 на вашем Android устройстве</strong>
</p>

<strong>Важно: Недавно в Google Play Store появилось [фейковое приложение Horizon Emu](https://play.google.com/store/apps/details?id=com.chahal.horiz). Мы просим вас отправить жалобу на это приложение, т.к. оно фейковое, платное, и возможно содержит вирусы. Спасибо</strong>

----

</div>

# Установка 

1. Перейдите во вкладку [Releases](https://github.com/HorizonEmuTeam/Horizon-Emu/releases/), откройте последний релиз, скачайте оттуда .apk и установите его, или скачайте приложение из [RuStore](https://apps.rustore.ru/app/com.antutu.ABenchMark)
2. Откройте приложение `Horizon Emu`, предоставьте все требуемые разрешения, перейдите во вкладку `Загрузки` и нажмите на `Обновить все`, и если Вам понадобится, то установите Scripts CPU Topology за место обычной версии Scripts, в этой же вкладке скачайте желаемую версию Wine
3. Откройте вкладку `Контейнеры`, нажмите на `Создать новый контейнер`, выберите имя для своего контейнера нажмите `Подтвердить`

Чтобы запустить контейнер, нажмите на ярлык `FileManager`

Для экранного управления используйте приложение под названием InputBridge. Чтобы использовать его, загрузите и установите [InputBridge_v0.1.9.9.apk](https://raw.githubusercontent.com/HorizonEmuTeam/Horizon-Emu/main/InputBridge_v0.1.9.9.apk), откройте приложение `InputBridge` и предоставьте все требуемые разрешения, затем нажмите `Импорт` и выберите файл вашего профиля управления (в формате .ibp).
В контейнере InputBridge запустится автоматически

# Конфигурация
* Конфигурация X11 

Во вкладке настроек X11 вас встретят настройки, перенесенные из настроек Termux-X11, там Вы можете настроить разрешение, скорость указателя мыши и т.д

* Настройки Dynarec

Они были перенесены в конфигурацию среды (Настройки - Параметры среды), всё настраивается вручную
(Пресет default подойдёт для большинства программ)

# Системные требования

```
Операционная система: Android 9
ЦПУ: Любой ЦПУ с aarch64
ГПУ: Любой ГПУ, который поддерживает Turnip
Root: Root права не требуются
```

# Наши главные цели

- [ ] Добавить поддержку VirGL
- [x] Исправить опцию удаления контейнера
- [ ] Добавить встроенное управление

## Помощь в развитии 
Если вы знаете как изменять ресурсы Apk и хотите помочь в развитии, то, пожалуйста, напишите на Telegram: @jotaros884. Заранее спасибо

# Благодарности и сторонние приложения

[Wine](https://wiki.winehq.org/Licensing)

[Box86](https://github.com/ptitSeb/box86)

[Box64](https://github.com/ptitSeb/box64)

[glibc-packages](https://github.com/termux-pacman/glibc-packages)

[Mobox](https://github.com/olegos2/mobox)

[DXVK](https://github.com/doitsujin/dxvk)

[DXVK-ASYNC](https://github.com/Sporif/dxvk-async)

[DXVK-GPLASYNC](https://gitlab.com/Ph42oN/dxvk-gplasync)

[D8VK](https://github.com/AlpyneDreams/d8vk)

[vkd3d-proton](https://github.com/HansKristian-Work/vkd3d-proton)

[VKD3D (lutris)](https://github.com/lutris/vkd3d)

[MangoHud](https://github.com/flightlessmango/MangoHud)

[Termux](https://github.com/termux/termux-app)

[Termux-X11](https://github.com/termux/termux-x11)

[Mesa](https://docs.mesa3d.org/license.html)

[mesa-zink-11.06.22](https://github.com/alexvorxx/mesa-zink-11.06.22)

Также от всего сердца благодарим всех тех людей, которые участвовали в разработке этого проекта, и которые внесли множество изменений (<b>Jotaros</b>, <b>DragoPayras</b>, <b>Alexoqool</b>, <b>Snap</b>, <b>Deleted Account</b>, <b>Darum</b>)
