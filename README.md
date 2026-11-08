# Бытовые услуги — мастерская в Королёве

Одностраничный сайт мастерской бытовых услуг по адресу **проспект Королёва, 5Д, Королёв** (ТЦ «Статус»).

## Что на сайте
- Ремонт обуви
- Ремонт одежды
- Металлоремонт (изготовление ключей, заточка, ремонт колясок, зонтов)
- Контакты: +7 (916) 229-90-62
- QR-код на карточку мастерской на Яндекс Картах

## Файлы
- `bytovye-uslugi-korolev.html` — готовый одностраничный сайт (единый файл, работает офлайн)
- `site-src/` — исходники (HTML + CSS + изображения)
- `bytovye-uslugi-qr.png` — QR-код на Яндекс Карты

## Просмотр
Просто откройте `bytovye-uslugi-korolev.html` в браузере.

## Сборка из исходников
Из папки `site-src/` файл собирается утилитой MultiTool:

```
multitool-node --skill websites site.cjs bundle site-src/index.html bytovye-uslugi-korolev.html
```

Live-версия на GitHub Pages: https://abdurahmon-mahkamov.github.io/bytovye-uslugi-korolev/