1) ssh-keygen
2) Добавить ключ private в github -> репозиторий -> settings/secrets->actions->new-> name=KEY and content with BEGIN-END. Key id_rsa must be without passphrase
3) на сервере выполнить команду cat id_rsa.pub >> ~/.ssh/authorized_keys
4) добавить публичный ключ в deployments keys