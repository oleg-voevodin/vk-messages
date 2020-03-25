# vk-messages
Работа с блоком сообщений (vk_api)

Так как VK запретили работать с блоком messages.. 
  vk_session = vk_api.VkApi(login=login, password=password) #Авторизация
  
Стоит подменить App ID на App ID приложения, которое может работать с сообщениями. Например, Kate Mobile:
  app_id = '2685278'
  vk_session = vk_api.VkApi(login=login, password=password, app_id=app_id)
  
Теперь работа с блоком messages стала возможной.

В этом репозитории будут файлы, в которых реализована работа с сообщениями. Я пишу свой клиент, мне бы такой репозиторий помог, может кому тоже поможет..
