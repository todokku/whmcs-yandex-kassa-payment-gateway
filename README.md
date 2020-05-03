# WHMCS Yandex.Kassa payment gateway
Платежный шлюз для оплаты через сервис Яндекс.Касса в системе WHMCS версии от 7.8.3.

Данный модуль основан на примере https://github.com/WHMCS/sample-gateway-module.

## Ограничения
- в сообщениях используется только русский язык;
- не поддерживаются возвраты и отмена подписки;
- не поддерживается налоги (fees) при переводе счета в статус "оплачено".

## Хуки
Если вам нужно после добавления платежа сделать какие-то действия, можете переименовать файл
`modules/gateways/yandexkassa/hooks.example.php` в `modules/gateways/yandexkassa/hooks.php` и
реализовать нужный хук.
