DONEVO — как выложить бесплатно (GitHub Pages)
1. Зарегистрируйтесь на github.com (бесплатно) -> New repository, имя например donevo, Public.
2. Add file -> Upload files: перетащите ВСЕ файлы из этой папки (index.html, sw.js, manifest.webmanifest, 3 иконки) -> Commit.
3. Settings -> Pages -> Source: Deploy from a branch, ветка main, папка /root -> Save.
4. Через минуту сайт будет по адресу https://ВАШЛОГИН.github.io/donevo/
5. На iPhone: откройте адрес в Safari -> Поделиться -> На экран «Домой».

Вход через Google (один раз, бесплатно):
1. console.cloud.google.com -> создайте проект.
2. APIs & Services -> Library -> включите Google Drive API.
3. OAuth consent screen: тип External, название Donevo, ваш email. Scopes: добавьте .../auth/drive.appdata. Нажмите Publish app (иначе войти смогут только тестовые пользователи).
4. Credentials -> Create credentials -> OAuth client ID -> Web application.
   Authorized JavaScript origins: https://ВАШЛОГИН.github.io
   Authorized redirect URIs: https://ВАШЛОГИН.github.io/donevo/index.html
   (точный адрес показан в приложении в окне синхронизации)
5. В приложении нажмите значок облака сверху -> вставьте Client ID -> Войти через Google.
