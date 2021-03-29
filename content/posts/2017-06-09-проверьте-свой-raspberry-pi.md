---
title: Проверьте свой Raspberry Pi
author: Gray
type: posts
date: 2017-06-09T17:51:02+00:00
url: /13268
featured_image: https://blognot.co/wp-content/uploads/2017/06/pi2modb1gb-comp-1.jpg
bluth_post_layout:
  - right_side
essb_cached_image:
  - https://blognot.co/wp-content/uploads/2017/06/pi2modb1gb-comp-1.jpg
essb_cache_expire:
  - 1616488797
esml_socialcount_LAST_UPDATED:
  - 1504953868
essb_c_buffer:
  - 4
essb_c_total:
  - 38
essb_c_twitter:
  - 3
esml_socialcount_facebook:
  - 19
esml_socialcount_TOTAL:
  - 21
esml_socialcount_facebook_shares:
  - 19
essb_c_linkedin:
  - 2
esml_socialcount_linkedin:
  - 2
rop_post_url_twitter:
  - 'https://blognot.co/13268?utm_source=ReviveOldPost&utm_medium=social&utm_campaign=ReviveOldPost'
rop_post_url_facebook:
  - 'https://blognot.co/13268?utm_source=ReviveOldPost&utm_medium=social&utm_campaign=ReviveOldPost'
essb_c_facebook:
  - 35
categories:
  - Без рубрики

---







Оказывается, и для Линукса бывают трояны — [в данном случае сообщается][1] о довольно простом трояне, который стучится через SSH в Raspberry Pi и, если там до сих пор сохранился дефолтный доступ админа с логином &#8216;raspberry&#8217; и паролем &#8216;pi&#8217;, то пароль меняется на другой, скрипт обеспечивает себе дальнейшее размножение, а еще ставит небольшое ПО для майнинга криптовалют. Получить какую-то ощутимую пользу в виде биткойнов такое решение, понятно, не сможет, но подключиться к другим, менее популярным валютам — почему нет?

Патч для Raspbian OS уже выпущен, но вот большой вопрос, конечно, как много владельцев Raspberry Pi их ставит так уж регулярно.

 [1]: http://www.zdnet.com/article/linux-malware-enslaves-raspberry-pi-to-mine-cryptocurrency/