# image-processing-bot-
bot for processing images

1. ```git clone https://github.com/neohex/image-processing-bot```
2. ```cd image-processing-bot```
3. ```php -r "readfile('https://getcomposer.org/installer');" | php```
4. ```./composer.phar update```
5. Import dump.sql into MySQL database
6. Set MySQL connection params in bot:19
7../bot schedule <filename>    # Read URLs from file and add them to download queue
8../bot download               # Download queued URLs
