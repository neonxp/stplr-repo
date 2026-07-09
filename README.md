# Stapler репозиторий NeonXP

[![🌱 Organic Code -- Code written by human](https://oc.neonxp.ru/organiccode.svg)](https://oc.neonxp.ru)

В этом репозитории три основных группы софта:

1. GNU софт
2. Софт который я использую в повседневной жизни и он мне нужен
3. Софт который пишу я (на Golang)

При этом, я не вижу проблемы добавлять пакеты нужные другим людям.
Но это должен быть исключительно свободный софт и приоритетно под лицензией
семейства GPL.

Для заказа нужного вам пакета - пишите на почту:
[mailto:i@neonxp.ru](mailto:i@neonxp.ru)

## Важно!

На текущий момент все пакеты собираются из расчёта, что операционная система -
это AltLinux P11. На других AltLinux сборка _скорее всего_ тоже получится, но
на других дистрибутивах сборка _точно_ не получится!

## Установка репозитория

1. Сначала нужно установить пакетный менеджер Stapler —
   [https://stplr.dev/docs/intro](https://stplr.dev/docs/intro)
2. Добавление этого репозитория в Stapler:

    ```
    stplr repo add neonxp.ru git://git.neonxp.ru/repo
    ```

## Установка приложений

После добавления репозитория, установка любого приложения заключается в простой
команде

```
stplr install имя_приложения
```

Например,

```
stplr install recutils
```

## Ссылки

- Пост в блоге про Stapler и этот репозиторий: [https://neonxp.ru/posts/2025-02-08-stplr/](https://neonxp.ru/posts/2025-02-08-stplr/)
- Сайт Stapler: [https://stplr.dev/](https://stplr.dev)
- Репозиторий Aides: [https://aides.space/](https://aides.space/)
