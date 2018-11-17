# Intent, Broadcast Receiver.

## навчальні матеріали:
1) Intent - Intent filter:<br>
https://developer.android.com/reference/android/content/Intent<br>
https://developer.android.com/guide/components/intents-filters.html<br>
2) Start Activity:<br>
https://developer.android.com/training/basics/firstapp/starting-activity.html<br>
http://startandroid.ru/ru/uroki/vse-uroki-spiskom/68-urok-29-vyzyvaem-activity-i-poluchaem-rezultat-metod-startactivityforresult.html<br>
3) Android Broadcast:<br>
https://developer.android.com/guide/components/broadcasts<br>
http://www.vogella.com/tutorials/AndroidBroadcastReceiver/article.html<br>

## Приклад, який розглядаємо на занятті
https://github.com/TeslyukTaras/AndroidTutorial_IntentBroadcastReceiver<br> 

## Домашнє завдання
1) створити новий проект<br> 
2) Реалізувати дизайн екрану для перегляду опису піци з наступними полями: -назва; -фото; -ціна; -статус(замовлено/не замовлено); -опис; -складові; -кнопки замовити та подзвонити.<br> 
3) Реалізувати BroadcastReceiver, який “опрацьовує” замовлення, а саме змінює значення статусу з замовленого на не замовленого і навпаки.<br> 
4) Коли користувач клікає на кнопку “Замовити”, необхідно надіслати broadcast для попередньо створеного Broadcast Receiver-a.<br> 