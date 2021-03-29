---
title: Быстрый интернет с Cloudflare
author: Gray
type: posts
date: 2019-09-26T13:50:02+00:00
url: /57946
featured_image: https://blognot.co/wp-content/uploads/2019/09/Warp-@2x.png
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
essb_cached_image:
  - https://blognot.co/wp-content/uploads/2019/09/Warp-@2x.png
essb_cache_expire:
  - 1616538513
essb_c_total:
  - 31
essb_pc_telegram:
  - 1
essb_c_telegram:
  - 1
essb_c_twitter:
  - 1
essb_pc_twitter:
  - 1
essb_c_facebook:
  - 30
categories:
  - Без рубрики

---







Вряд ли надо объяснять, что такое Cloudflare — ребята начинали с сервиса защиты от DDOS, потом развились до CDN, а буквально на днях вышли на биржу с капитализацией больше 5 миллиардов долларов. В процессе развития они постепенно переключились на задачу ускорения интернета — я много лет с удовольствием использовал широкие возможности их сервиса для сайтов, регулярно пробуя новые способы сделать сайты еще немного быстрее.

Теперь у сервиса есть что предложить и массовому пользователю — несколько лет назад они запустили публичный быстрый DNS-сервис 1.1.1.1 (и 1.0.0.1 тоже), который вполне успешно работает и поддерживает очень полезные возможности в части шифрования DNS-трафика. А в этом году они пообещали предоставить пользователям возможность ускорить свой доступ не только за счет DNS-запросов, а и с помощью VPN-сервиса Warp. Правда, с обещанным запуском задержались и он [стал доступен только сейчас][1] — в приложении для iOS и Android добавилась возможность не только включить использование DNS-сервиса, но и включить VPN. Бесплатная неограниченная версия доступна всем, а за 5 долларов в месяцев можно получить доступ к версии [Warp Plus][2], которая использует возможности продвинутого роутинга в сети Cloudlfare. Включение этой фичи для сайтов ускоряло среднее время доступа процентов на 20-25, насколько помню.

Впрочем, я пока попробовать её не смог — приложение выдает сбой при подключении к iTunes Store, сервис в анонсе предупреждал, что стоимость подписки зависит от индекса БигМака в каждом регионе и для iOS процесс подсчета еще не завершен. Поэтому пришлось тестировать обычную.

Для проверки использовался стандартный SpeedTest, но сервер я вручную выбирал в Амстердаме — это уменьшает возможность случайных результатов, понятно, что одесские серверы, до которых у меня через Wi-Fi пара миллисекунд и широченный канал, выдадут идеальный результат напрямую и совсем неидеальный, когда трафик пойдет через стороннюю сеть. 

<div class="wp-block-image">
  <figure class="aligncenter"><img src="https://i2.wp.com/www.speedtest.net/result/i/3466479989.png?w=740&#038;ssl=1" alt="" data-recalc-dims="1" /><figcaption>Результат Speedtest <strong>без</strong> Warp через локальный wi-fi</figcaption></figure>


<div class="wp-block-image">
  <figure class="aligncenter"><img data-attachment-id="57947" data-permalink="https://blognot.co/57946/img_41b1780e8bdc-1" data-orig-file="https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?fit=350%2C200&ssl=1" data-orig-size="350,200" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="IMG_41B1780E8BDC-1" data-image-description="" data-medium-file="https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?fit=300%2C171&ssl=1" data-large-file="https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?fit=350%2C200&ssl=1" width="350" height="200" src="https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?resize=350%2C200&#038;ssl=1" alt="" class="wp-image-57947" srcset="https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?w=350&ssl=1 350w, https://i1.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_41B1780E8BDC-1.jpeg?resize=300%2C171&ssl=1 300w" sizes="(max-width: 350px) 100vw, 350px" data-recalc-dims="1" /><figcaption>Результат Speedtest с <strong>включенным</strong> Warp через локальный wi-fi</figcaption></figure>


<div class="wp-block-image">
  <figure class="aligncenter"><img data-attachment-id="57948" data-permalink="https://blognot.co/57946/img_2eaebe05e6ee-1" data-orig-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?fit=350%2C200&ssl=1" data-orig-size="350,200" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="IMG_2EAEBE05E6EE-1" data-image-description="" data-medium-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?fit=300%2C171&ssl=1" data-large-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?fit=350%2C200&ssl=1" width="350" height="200" src="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?resize=350%2C200&#038;ssl=1" alt="" class="wp-image-57948" srcset="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?w=350&ssl=1 350w, https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_2EAEBE05E6EE-1.jpeg?resize=300%2C171&ssl=1 300w" sizes="(max-width: 350px) 100vw, 350px" data-recalc-dims="1" /><figcaption>Результат Speedtest <strong>без</strong> Warp через LTE</figcaption></figure>


<div class="wp-block-image">
  <figure class="aligncenter"><img data-attachment-id="57949" data-permalink="https://blognot.co/57946/img_27482347c413-1" data-orig-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?fit=350%2C200&ssl=1" data-orig-size="350,200" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;1&quot;}" data-image-title="IMG_27482347C413-1" data-image-description="" data-medium-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?fit=300%2C171&ssl=1" data-large-file="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?fit=350%2C200&ssl=1" width="350" height="200" src="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?resize=350%2C200&#038;ssl=1" alt="" class="wp-image-57949" srcset="https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?w=350&ssl=1 350w, https://i2.wp.com/blognot.co/wp-content/uploads/2019/09/IMG_27482347C413-1.jpeg?resize=300%2C171&ssl=1 300w" sizes="(max-width: 350px) 100vw, 350px" data-recalc-dims="1" /><figcaption>Результат Speedtest с <strong>включенным</strong> Warp через LTE</figcaption></figure>


В общем, надо честно сказать, что чудес не бывает и ждать их не надо. Ускорить существующее быстрое соединение путем включения дополнительного VPN не получится по определению. При этом скорость доступа через Warp остается более чем комфортной и вряд ли кто-то заметит всерьез разницу на мобильном устройстве с такими показателями, а при этом трафик становится гарантированно защищенным.

Вполне возможно, что с включенным Warp Plus **средняя** скорость доступа к ресурсам и сервисам станет выше — за счет того, что сеть будет грамотно перенаправлять запросы, обходя те места, где у существующего провайдера есть сложности или (о ужас!) блокировки. Кстати, да, все возможные блокировки на уровне провайдера это приложение обходит без проблем уже сейчас, в совершенно бесплатной версии.

Будет интересно посмотреть на использование приложения в путешествиях — я постараюсь его включать в поездках и смотреть на результат. Напрашивается идея аналогичного сервиса не только для мобильных, кстати говоря — тоже с удовольствием бы попользовался.

И совершенно честная реферальная ссылка — если вы пройдете по ней и [подпишетесь на Warp Plus][2], то я получу бесплатный гигабайт трафика в этом тарифе. Впрочем, я все равно планирую подписаться, как только это станет возможным.

 [1]: https://blog.cloudflare.com/announcing-warp-plus/
 [2]: https://warp.plus/UKM9x