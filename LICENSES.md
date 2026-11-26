# Лицензии компонентов LesVideo 0.1.0

Это уведомления о сторонних компонентах Windows x64-установщика. У каждого
компонента собственные условия. Этот файл не задаёт лицензию на саму LesVideo.

| Компонент | Версия | Лицензия или условия |
|---|---|---|
| FFmpeg и FFprobe | `2026-10-15-git-afead44165-full_build-www.gyan.dev` | GPL 3 или новее. Бинарники собраны с `--enable-gpl --enable-version3`. [Условия FFmpeg](https://ffmpeg.org/legal.html) · [Сборщик Gyan](https://www.gyan.dev/ffmpeg/builds/) |
| Python | 3.14.4 | [PSF License и уведомления](https://docs.python.org/3.14/license.html) |
| Node.js | 26.13.1 | [Лицензия Node.js и уведомления библиотек](https://github.com/nodejs/node/blob/v26.13.1/LICENSE) · [Копия из комплекта](licenses/Node.js.txt) |
| Ollama | 0.40.18, CPU и Vulkan | [MIT](https://github.com/ollama/ollama/blob/main/LICENSE) и уведомления включённых библиотек |
| Whisper base | Systran/faster-whisper-base | [MIT](https://huggingface.co/Systran/faster-whisper-base) |
| Qwen3 4B | `qwen3:4b-instruct-2507-q4_K_M` | [Apache 2.0](https://ollama.com/library/qwen3:4b-instruct-2507-q4_K_M) |
| Microsoft Edge WebView2 | Evergreen Standalone Runtime, x64 | Условия Microsoft для распространяемого WebView2 Runtime. [Документация Microsoft](https://learn.microsoft.com/en-us/microsoft-edge/webview2/concepts/distribution) |

## FFmpeg и FFprobe

Ревизия FFmpeg в установщике — [`afead44165`](https://github.com/FFmpeg/FFmpeg/tree/afead44165).
Ссылку на эту ревизию следует отличать от полного соответствующего набора
исходников использованной сборки. Его состав и ссылку на размещённый архив
ещё нужно подтвердить перед распространением установщика.

## Пакеты Python

Перечень прочитан из метаданных пакетов в комплекте. Когда в пакете нет поля
лицензии, ниже приведена ссылка на поставленные лицензионные файлы, если они есть.

| Пакет | Версия | Лицензия или уведомления |
|---|---|---|
| annotated-types | 0.8.0 | MIT · [LICENSE](licenses/python/annotated-types/licenses/LICENSE) |
| anyio | 4.15.1 | MIT · [LICENSE](licenses/python/anyio/licenses/LICENSE) |
| av | 18.1.0 | BSD-3-Clause · [AUTHORS.py](licenses/python/av/licenses/AUTHORS.py), [AUTHORS.rst](licenses/python/av/licenses/AUTHORS.rst), [LICENSE.txt](licenses/python/av/licenses/LICENSE.txt) |
| brotli | 1.2.1 | [LICENSE](licenses/python/brotli/licenses/LICENSE) |
| certifi | 2026.10.23 | Mozilla Public License 2.0 (MPL 2.0) · [LICENSE](licenses/python/certifi/licenses/LICENSE) |
| charset-normalizer | 3.5.2 | [LICENSE](licenses/python/charset-normalizer/licenses/LICENSE) |
| click | 8.5.0 | BSD-3-Clause · [LICENSE.txt](licenses/python/click/licenses/LICENSE.txt) |
| colorama | 0.4.6 | BSD License · [LICENSE.txt](licenses/python/colorama/licenses/LICENSE.txt) |
| ctranslate2 | 4.8.3 | См. условия у издателя пакета |
| faster-whisper | 1.2.1 | MIT License · [LICENSE](licenses/python/faster-whisper/LICENSE) |
| filelock | 4.2.2 | MIT · [LICENSE](licenses/python/filelock/licenses/LICENSE) |
| flatbuffers | 25.12.19 | Apache Software License |
| fsspec | 2026.9.0 | BSD-3-Clause · [LICENSE](licenses/python/fsspec/licenses/LICENSE) |
| h11 | 0.16.0 | MIT License · [LICENSE.txt](licenses/python/h11/licenses/LICENSE.txt) |
| hf-xet | 1.7.0 | Apache-2.0 · [LICENSE](licenses/python/hf-xet/licenses/LICENSE) |
| httpcore2 | 2.13.1 | BSD-3-Clause · [LICENSE.md](licenses/python/httpcore2/licenses/LICENSE.md) |
| httpx2 | 2.13.1 | BSD-3-Clause · [LICENSE.md](licenses/python/httpx2/licenses/LICENSE.md) |
| huggingface_hub | 2.2.0 | Apache Software License · [LICENSE](licenses/python/huggingface_hub/licenses/LICENSE) |
| idna | 3.20 | BSD-3-Clause · [LICENSE.md](licenses/python/idna/licenses/LICENSE.md) |
| mutagen | 1.48.1 | GPL-2.0-or-later · [COPYING](licenses/python/mutagen/licenses/COPYING) |
| numpy | 2.5.4 | BSD-3-Clause AND 0BSD AND MIT AND Zlib AND CC0-1.0 · [LICENSE.txt](licenses/python/numpy/licenses/LICENSE.txt), [LICENSE.txt](licenses/python/numpy/licenses/numpy/_core/include/numpy/libdivide/LICENSE.txt), [COPYING](licenses/python/numpy/licenses/numpy/_core/src/common/pythoncapi-compat/COPYING), [LICENSE](licenses/python/numpy/licenses/numpy/_core/src/highway/LICENSE), [dragon4_LICENSE.txt](licenses/python/numpy/licenses/numpy/_core/src/multiarray/dragon4_LICENSE.txt), [LICENSE.md](licenses/python/numpy/licenses/numpy/_core/src/npysort/x86-simd-sort/LICENSE.md), [LICENSE](licenses/python/numpy/licenses/numpy/_core/src/umath/svml/LICENSE), [LICENSE.md](licenses/python/numpy/licenses/numpy/fft/pocketfft/LICENSE.md), [LICENSE.txt](licenses/python/numpy/licenses/numpy/linalg/lapack_lite/LICENSE.txt), [LICENSE](licenses/python/numpy/licenses/numpy/ma/LICENSE), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/distributions/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/mt19937/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/pcg64/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/philox/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/sfc64/LICENSE.md), [LICENSE.md](licenses/python/numpy/licenses/numpy/random/src/splitmix64/LICENSE.md) |
| onnxruntime | 1.31.0 | MIT License |
| opencv-python-headless | 4.14.0.94 | Apache Software License · [LICENSE-3RD-PARTY.txt](licenses/python/opencv-python-headless/LICENSE-3RD-PARTY.txt), [LICENSE.txt](licenses/python/opencv-python-headless/LICENSE.txt) |
| packaging | 26.3 | Apache-2.0 OR BSD-2-Clause · [LICENSE](licenses/python/packaging/licenses/LICENSE), [LICENSE.APACHE](licenses/python/packaging/licenses/LICENSE.APACHE), [LICENSE.BSD](licenses/python/packaging/licenses/LICENSE.BSD) |
| protobuf | 7.36.2 | [LICENSE](licenses/python/protobuf/LICENSE) |
| pycryptodomex | 3.24.2 | BSD License, Public Domain · [LICENSE.rst](licenses/python/pycryptodomex/LICENSE.rst) |
| pydantic | 2.14.1 | MIT · [LICENSE](licenses/python/pydantic/licenses/LICENSE) |
| pydantic_core | 2.50.1 | MIT · [LICENSE](licenses/python/pydantic_core/licenses/LICENSE) |
| python-dotenv | 1.2.4 | [LICENSE](licenses/python/python-dotenv/licenses/LICENSE) |
| PyYAML | 6.0.3 | MIT License · [LICENSE](licenses/python/PyYAML/licenses/LICENSE) |
| requests | 2.34.2 | Apache Software License · [LICENSE](licenses/python/requests/licenses/LICENSE), [NOTICE](licenses/python/requests/licenses/NOTICE) |
| tokenizers | 0.23.3 | Apache Software License |
| tqdm | 4.70.1 | [LICENCE](licenses/python/tqdm/licenses/LICENCE) |
| truststore | 0.10.5 | MIT · [LICENSE](licenses/python/truststore/licenses/LICENSE) |
| typing_extensions | 4.16.0 | PSF-2.0 · [LICENSE](licenses/python/typing_extensions/licenses/LICENSE) |
| typing-inspection | 0.4.4 | MIT · [LICENSE](licenses/python/typing-inspection/licenses/LICENSE) |
| urllib3 | 2.8.0 | MIT · [LICENSE.txt](licenses/python/urllib3/licenses/LICENSE.txt) |
| websockets | 17.2 | BSD-3-Clause · [LICENSE](licenses/python/websockets/licenses/LICENSE) |
| yt-dlp | 2026.11.24.232653dev | Unlicense · [LICENSE](licenses/python/yt-dlp/licenses/LICENSE) |
| yt-dlp-ejs | 0.8.0 | Unlicense AND MIT AND ISC · [LICENSE](licenses/python/yt-dlp-ejs/licenses/LICENSE) |
