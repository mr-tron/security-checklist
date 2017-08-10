# security-checklist

## How do I secure my server against a sophisticated adversary?

Goal: to have several combinations of system & application software & admin best practices selected to maximize security. The main scenario is a server (or several servers) running a web application (perhaps via TOR) for interacting with blockchain (typically Bitcoin or Ethereum). A good developer should be able to follow one of these checklists and end up with a reasonably secure system.

Feel free to propose new configs, criticize existing ones and add references and pros/cons

## Configs

1. 

2.

## Notes

### Хостинг

1. Хостинг должен распологаться в цивилизованной стране, где не изымают сервера без ордера, нет беспредела и произвола. Например западная европа - Швейцария, Германия.  
(это не защита от конкретной атаки, а просто здравый смысл)
1. Хостинг должен быть анонимный и оплачиваться биткоинами или анонимными картами.  
(защита от действия спецслужб в случае размещения чего-то что может быть сочтено противоправным)
1. Хостинг должен распологаться только на физических машинах - не vps.  
(частично защищает от возможности снять дамп состояния машины и покопаться в нём)
1. Система должна быть на зашифрованных разделах и требовать ввод ключа для запуска. Либо через ip-kvm (тогда можно зашифровать весь диск), либо после загрузки OS через ssh (тогда шифруется только раздел с данными).  
(защита от действий спецслужб, действий нечистоплотного хостера, действий хакеров получивших доступ к админке хостера или технически или социальной инженерией).

