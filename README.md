# Интеграция с HD VideoBox

Открыть фильм по id kinopoisk hdvb://hd.vb/film/kinopoisk/931677
Открыть вкладку видео hdvb://hd.vb/film/kinopoisk/931677?tab=video

Открыть фильм по id filmix  hdvb://hd.vb/film/filmix/111245

Открыть фильм по id hdrezka hdvb://hd.vb/film/hdrezka/18286

Открыть сериал по id thetvdb hdvb://hd.vb/film/thetvdb/259972

Поиск фильма по запросу hdvb://hd.vb/search/?q=Dunkirk

Поиск торрентов по запросу hdvb://hd.vb/tsearch/?q=Dunkirk

История hdvb://hd.vb/browse/9
Избранное hdvb://hd.vb/browse/10
Новинки hdvb://hd.vb/browse/7
Сейчас смотрят hdvb://hd.vb/browse/8
Фильмы hdvb://hd.vb/browse/1
Сериалы hdvb://hd.vb/browse/2
Мультфильмы hdvb://hd.vb/browse/3
Мультсериалы hdvb://hd.vb/browse/4


Тестирование через abd
adb shell am start -W -a android.intent.action.VIEW -d "hdvb://hd.vb/film/kinopoisk/?id=931677" dkc.video.hdbox
