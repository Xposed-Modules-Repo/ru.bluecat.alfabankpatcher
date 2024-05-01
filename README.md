<div align="center">
<h1>Alfa Bank Patcher</h1>

![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher/total)
[![GitHub release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher)](https://github.com/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher)](https://github.com/Xposed-Modules-Repo/ru.bluecat.alfabankpatcher/releases)
[![Telegram Group](https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram)](https://t.me/lsposed_workshop)
[![4PDA](https://img.shields.io/badge/4PDA-Topic-blue)](https://4pda.to/forum/index.php?showtopic=603033&view=findpost&p=117766501)

<p>Скрытие рекламы различного формата и управление push уведомлениями в приложении <a href="https://apps.rustore.ru/app/ru.alfabank.mobile.android">Альфа Банк</a></p>
</div>

### Общее:
- Контроль проверок на валидность устройства для AlfaPay и сканера отпечатка включены всегда.

### Контролируемый функционал:
- Различные баннеры с предложениями
- Аналитика
- Внутреннее самообновление
- Профиль. Госуслуги
- Скрытие раздела "Выгода"
- Чат. Удерживание фильтра "Сообщения от банка" в чатах
- Чат. Фильтрация видимости доступных чатов
- Push. Загрузка конфигурации фильтрации
- Push. Фильтрация по ключевым словам (белый/чёрный список)
- Push. Логирование отфильтрованных Push сообщений
- Push. Удерживайте лого банка в разделе чатов что бы узнать сколько уже отфильтровано

### Расположения баннеров:
- Главная: "призрачные" предложения в списке счетов, баннер-карусель как один из неубираемых виджетов, реферальный баннер сверху
- Выгода: баннер-карусель в разделе "Всё", реферальные баннеры и раздел, кредитные предложения в бизнес услугах, раздел предложений
- История: предложения кредита сверху над самой историей
- Переводы: предложение кредита после успешного перевода
- После авторизации: истории, предложение биометрии

### Аналитика:
- AppCenter
- AppsFlyer
- Firebase analytics
- Flurry
- MyTracker
- SnowPlow
- GROUP-IB

### Требования:
- Android 8.0+
- Установленное приложение [Альфа-Банк](https://apps.rustore.ru/app/ru.alfabank.mobile.android)

### Обратите внимание:
- Модульная часть использует рут возможности для завершения процесса Альфа Банка и манипуляции с логами push сообщений.
- Для более эффективной работы push фильтра рекомендуется использовать сторонний фильтр sms сообщений т.к. реализация текущего фильтра работает по принципу "не в сети" для искомый push сообщений, сервер может вам присылать тоже сообщение на зарегистрированный номер через смс.

## For non-Russian users:
This is a module for the russian banking application [Alfa-Bank](https://apps.rustore.ru/app/ru.alfabank.mobile.android), you don't need to use it, app working only in Russia. This module has support only for the Russian language.
