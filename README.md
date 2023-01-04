1) ssh-keygen
2) Добавить ключ private в github -> репозиторий -> secrets-> KEY env
3) на сервере выполнить команду cat id_rsa.pub >> ~/.ssh/authorized_keys
4) добавить публичный ключ в deployments keys