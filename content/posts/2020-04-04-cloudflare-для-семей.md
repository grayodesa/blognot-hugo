---
title: Cloudflare для семей
author: Gray
type: posts
date: 2020-04-04T11:17:54+00:00
url: /59258
images:
  -  https://blognot.co/wp-content/uploads/2020/04/image4-2.png
essb_cached_image:
  - https://blognot.co/wp-content/uploads/2020/04/image4-2.png
essb_cache_expire:
  - 1615134418
ytrssenabled_meta_value:
  - no
ytremove_meta_value:
  - no
ytad1meta:
  - enabled
ytad2meta:
  - enabled
ytad3meta:
  - enabled
ytad4meta:
  - enabled
ytad5meta:
  - enabled
template_meta:
  - no
bluth_post_layout:
  - right_side
ampforwp-amp-on-off:
  - default
ampforwp-ia-on-off:
  - default
essb_c_total:
  - 33
essb_c_facebook:
  - 33
categories:
  - Без рубрики

---







За всеми новостями про вирус я пропустил прекрасный запуск от Cloudflare — запустив пару лет назад публичный DNS-сервер с поддержкой шифрования 1.1.1.1/1.0.0.1, а год назад — свое VPN решение Warp (которое не совсем VPN, поскольку не скрывает вашего IP, но при этом шифрует и ускоряет трафик через свой CDN и успешно обходит некоторые блокировки), в этом году 1 апреля ребята решили отметить запуском Семейного DNS — [1.1.1.1 for Families][1]{.aioseop-link} — который по сути такой же DNS, только с дополнительными фильтрами. Видов фильтрации два — с блокировкой известных malware-источников и с блокировкой как malware, так и взрослого контента. Для использования их надо настроить в качестве DNS соответственно либо адреса 1.1.1.2/1.0.0.2 либо 1.1.1.3/1.0.0.3 соответственно.

Вообще-то, ничего нового, конечно, ребята не придумали — OpenDNS давно умеет фильтровать запросы, да и Яндекс много лет назад запустил три варианта своего DNS-сервиса. Но Cloudflare стремится конкурировать с Google DNS, да и возможности в плане сетевой инфраструктуры у него выглядят иначе.&nbsp;

Правда, буквально сразу они [по ошибке зафильтровали][2]{.aioseop-link} LGBT+ контент как порно и и в пожарном порядке за два часа его выводили из фильтра, параллельно придумывая схемы мониторинга таких казусов. 

 [1]: https://blog.cloudflare.com/introducing-1-1-1-1-for-families/
 [2]: https://blog.cloudflare.com/the-mistake-that-caused-1-1-1-3-to-block-lgbtqia-sites-today/