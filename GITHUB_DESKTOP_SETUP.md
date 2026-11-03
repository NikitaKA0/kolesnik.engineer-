# Публикация портфолио через GitHub Desktop / GitHub Pages

## 1. Перенести сайт в локальный репозиторий

1. Скачайте `nikita_kolesnik_deploy_ready.zip` и распакуйте его.
2. Откройте созданный репозиторий в GitHub Desktop: Repository → Show in Explorer.
3. Скопируйте **содержимое распакованной папки** в корень репозитория. Файл `index.html` должен лежать в той же папке, что и скрытая папка `.git`, а `assets/`, `docs/`, `styles.css` и `script.js` — рядом с ним.
4. Не копируйте сам ZIP и не помещайте всё содержимое в дополнительную вложенную папку.
5. В GitHub Desktop убедитесь, что новые файлы видны как изменения. Сделайте `Commit to main` и нажмите `Publish repository` (или `Push origin`, если репозиторий уже опубликован).
6. Для бесплатной публикации GitHub Pages репозиторий обычно должен быть публичным. Перед публикацией проверьте, что файлы не содержат нежелательных личных сведений.

## 2. Включить GitHub Pages

1. Откройте страницу репозитория на github.com.
2. Перейдите в Settings → Pages.
3. В разделе Build and deployment выберите `Deploy from a branch`.
4. Укажите ветку `main`, папку `/(root)` и сохраните изменения.
5. После успешной публикации адрес обычно имеет вид `https://USERNAME.github.io/REPOSITORY/`.

Официальная инструкция: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 3. Домен kolesnik.engineer — только после его регистрации

Имя репозитория не регистрирует и не подключает домен. Если вы владеете доменом, укажите его в Settings → Pages → Custom domain, выполните предложенную в GitHub процедуру верификации и затем настройте DNS у регистратора.

Для домена верхнего уровня официальная документация GitHub Pages предусматривает четыре A-записи: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. Для `www` можно использовать CNAME на `USERNAME.github.io`.

Не создавайте DNS-записи, если домен ещё не зарегистрирован или если вы ещё не определились между Netlify и GitHub Pages.

Официальная инструкция: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## 4. Проверка

Откройте главную страницу и проверьте разделы «Достижения» и «Образование», увеличивающиеся фотографии дипломов, переключатель RU/EN и ссылки на изображения/PDF в архиве.
