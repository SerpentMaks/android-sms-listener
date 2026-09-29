# Android SMS Listener

> Android-приложение для получения и обработки входящих SMS через BroadcastReceiver и отдельный сервис.

## Что реализовано

Приложение содержит:

- `SmsReceiver` для обработки события `SMS_RECEIVED`;
- `SmsListenerService` для фоновой логики;
- `MainActivity` как основной экран;
- разрешения на получение и чтение SMS;
- поддержку уведомлений и сетевого состояния;
- `WAKE_LOCK` и foreground-service permission.

В манифесте также включена поддержка устройств без телефонного модуля через `android.hardware.telephony` с `required="false"`.

## Разрешения

Проект использует, в частности:

- `RECEIVE_SMS`
- `READ_SMS`
- `FOREGROUND_SERVICE`
- `WAKE_LOCK`
- `INTERNET`
- `ACCESS_NETWORK_STATE`
- `POST_NOTIFICATIONS`

> Для реального устройства Android может потребоваться вручную выдать runtime-разрешения.

## Запуск

Откройте проект в Android Studio, синхронизируйте Gradle и запустите приложение на совместимом Android-устройстве/эмуляторе.

## Назначение

Проект подходит для изучения Android-компонентов, BroadcastReceiver, сервисов и жизненного цикла фоновых задач.

## Статус

🎓 Учебный Android-проект.
