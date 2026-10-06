# Треки Enso

Положите сюда три файла, скачанные с Suno (MP3 или MP4), с такими именами — расширение `.mp3`, `.mp4` или `.m4a`:

| Файл | Трек на Suno |
|---|---|
| `track-1.mp3` | https://suno.com/s/FlUHU56FcRSXQtcj |
| `track-2.mp3` | https://suno.com/s/Rkw3YUjjzWxiJ3Lj |
| `track-3.mp3` | https://suno.com/s/Gcx2V4lbPDyMZvUh |

Скачать: открыть трек на Suno → «⋯» → Download → MP3 Audio (или Video).
MP3 лучше: файл меньше, и из него сайт сам берёт название песни. У MP4 названия впишите в поле `title` в CONFIG в `index.html`.

Сайт сначала играет файл отсюда. Если файла нет, он пробует поток с CDN Suno.
Название трека сайт берёт из тегов MP3 (если нужно другое — поле `title` в CONFIG в `index.html`).
