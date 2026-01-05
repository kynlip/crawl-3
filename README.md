# ultracrawler
Trước khi chạy lệnh cài đặt, bạn phải mở file composer.json ở dự án chính của bạn (nơi bạn muốn cài cái crawler này vào) và thêm đoạn này vào:

JSON

"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/kynlip/crawl-3"
    }
],
## Cài đặt

2. Chạy lệnh cài đặt
Sau khi đã lưu file composer.json ở bước 1, bạn mới chạy lệnh này trong terminal:

Bash

composer require crawl-3/ultracrawler:dev-master
