---
title: Попробовал de:comments. Впечатления
author: Gray
type: posts
date: 2015-05-01T08:42:47+00:00
url: /12381
wp-to-buffer-pro:
  - 'a:4:{s:8:"override";s:1:"0";s:7:"message";s:0:"";s:6:"number";s:1:"1";s:16:"alternateMessage";s:0:"";}'
bluth_post_layout:
  - right_side
dsq_thread_id:
  - 3727520189
esml_socialcount_LAST_UPDATED:
  - 1497225005
esml_socialcount_googleplus:
  - 5
esml_socialcount_linkedin:
  - 3
esml_socialcount_TOTAL:
  - 8
essb_cache_expire:
  - 1616804750
essb_c_twitter:
  - 4
essb_c_google:
  - 5
essb_c_linkedin:
  - 6
essb_c_buffer:
  - 8
essb_c_pocket:
  - 8
essb_c_total:
  - 11
essb_c_facebook:
  - 7
categories:
  - Без рубрики

---







Возможно, постоянные посетители заметили в последние две недели, что в блоге менялась система комментариев. Две недели назад я решил поэкспериментировать и поставил продвигаемый в последнее время плагин <a href="https://decomments.com/" target="_blank">de:comments</a> вместо работавшего ранее Disqus. Во-первых, просто захотелось повозиться, а во-вторых, disqus, как сторонний сервис имеет ряд недостатков, которые при длительном использовании начинают надоедать.

За две недели я навозился достаточно и вернул disqus обратно. И вот почему.

Во-первых, disqus — это не только система комментариев, но и способ авторизовать пользователя. Он как-то удовлетворительно отсекает спам, спаммерские регистрации. Отказываясь от него — а de:comments фактически является модификацией встроенных комментариев WordPress, — вы отказываетесь и от регистраций через disqus. Первым же неочевидным, но встающим в полный рост, следствием является необходимость работать с регистрацией самостоятельно. А WordPress, честно сказать, плохо справляется с регистрациями спаммеров.

Во-вторых, de:comments не предлагает никакого способа работать с регистрациями. Вам надо или смириться со спаммерскими аккаунтами либо ставить еще один плагин, который разрешит пользователям логиниться через facebook или twitter или еще что-то. И авторы de:comments рекомендуют один такой, утверждая, что подойдут и любые другие. Увы — любые другие не подойдут. Они или не заработают вообще, либо будут ужасно выглядеть совершенно чужеродным куском дизайна. А тот, что рекомендуют авторы, не имеет настройки &#171;Логиниться только через аккаунты в соцсетях&#187;, что опять-таки оставляет возможность для спаммеров регистрироваться.

В-третьих, никакой защиты от спама. Вообще никакой. Ставьте еще один плагин, включайте режим премодерации, настраивайте как хотите — ваш блог, вам его и защищать от спама через &#171;most powerful plugin for comments&#187;.

Отдельно отмечу странную логику работы в некоторых частях плагина — например, если вы включили плагин, авторизовали лицензию на него, а потом в ходе отладки выключили его, то просто включить опять не получиться — авторизовывайте лицензию заново, причем сами догадайтесь, что плагин не включился, поскольку никаких сообщений в админке уже не появится.

Впрочем, окончательно заставило принять решение об отказе от плагина странное поведение всей системы — я понимаю, что я тут достаточно навертел с кэшированием и серверными настройками и конфигурация блога у меня причудливая, но почему включение плагина для комментариев заставляет блог периодически сваливаться в 404-ю ошибку в админ-панели (например, при переходе на wp-admin/index.php), я так и не понял.

Так что поживем дальше с disqus. Все-таки, столько лет вместе.