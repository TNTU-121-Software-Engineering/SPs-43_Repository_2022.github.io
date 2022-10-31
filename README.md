
# GitHub Pages помилка збірки Jekyll


```bash
  Conversion error: Jekyll::Converters::Scss encountered an error while converting 'assets/css/style.scss':
                    No such file or directory @ dir_chdir - /github/workspace/docs
```
Щоб вирішити помилку на мою думку потрібно.

## Інструкція

Створити або скопіювати вже існуючий репозиторій.

```bash
git clone https://github.com/username/username.github.io

```



## Правила створення репозиторію GitHub Pages

Репозиторій повинен бути `Public` а в назві репозиторію повинно бути `.github.io` 




## Відсутня папка docs


Створіть нову `docs` папку в корені свого сховища в гілці, яку ви вибрали для джерела публікації, і додайте до папки вихідні файли вашого сайту.

Папку можна створити
 - На сайті GitHub в своєму репозиторії.
 - В командному рядку використовуючи коману `mkdir` .



## Для більш детальної інформації

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites#missing-docs-folder
