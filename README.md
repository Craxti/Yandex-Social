# Yandex.Alisa + Social networks = <3

A skill for Yandex.Alisa with the ability to interact with social networks to find the most interesting information.
You can format all your ideas as tasks or write to our social networks, as well as send us your improvements. This way we can make the Yandex.Alice skill useful for our community!

#### Launching a skill
1. Create a skill in [Yandex.Dialogues](https://dialogs.yandex.ru/developer/skills/)
2. Specify the Backend in the ***Webhook URL*** settings to your server, for example: https://you.site:5000/
3. Running the code on the server:
    ```bash
    export FLASK_APP=app.py
    export VK_LOGIN=<your login from VK>
    export VK_PASS=<your pass from VK>
    python3 -m flask run --host=0.0.0.0 --cert=adhoc
    ```
4. You can test through the developer console or generate a link through the Access menu.



#### Полезные ссылки
- [Documentation VK Api](https://vk.com/dev)
- [Yandex.Dialogs documentation](https://yandex.ru/dev/dialogs/)
- [Your skills for Yandex.Alisa](https://dialogs.yandex.ru/developer/skills/)
- [VK_api for Python](https://github.com/python273/vk_api)

