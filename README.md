# Karaoke Player / Караоке-плеер

Небольшой браузерный караоке-плеер с русским и английским интерфейсом. Работает локально: аудио и текст песни не отправляются на сервер.

A lightweight bilingual karaoke player that runs entirely in the browser. Audio and lyrics stay on your device.

## Возможности / Features

- загрузка аудиофайлов, поддерживаемых браузером;
- загрузка текста песни в формате TXT или LRC;
- автоматическое распределение строк TXT по длительности аудио;
- поддержка нескольких временных меток в строке LRC и тега `offset`;
- плавная подсветка и центрирование текущей строки;
- переход к нужному моменту по клику, Enter или Space;
- адаптивное отображение длинных строк без скачка разметки;
- переключение русского и английского языка с сохранением выбора.

## Запуск / Run

Откройте `index.html` в современном браузере, затем выберите аудиофайл и TXT- или LRC-файл с текстом песни.

Open `index.html` in a modern browser, then choose an audio file and a TXT or LRC lyrics file.

Для более точной синхронизации используйте LRC. У обычного TXT временные метки вычисляются равномерно по длительности аудио.

Use LRC for accurate synchronization. Plain TXT lines are distributed evenly across the audio duration.
