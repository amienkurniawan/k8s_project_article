jika menggunakan php:7.x-fmp-alpine pastikan project sudah siap untuk didockerize misalkan untuk vendor nya dan env nya sudah siap juga karena fmp-alpine project tidak dapat menggunakan perintah composer install pada saat build containernya sedangkan untuk php:7-x-fmp harus menginstall dependenciesnya sendiri sehingga configurasinya berbeda
<br />
sudah dapat membuat container menggunakan docker-compose dengan settingan ini atau menggunakan settingan dari gitlab lumen 6 version base microservice