## **Создание тегов**

Git использует два основных типа тегов: [легковесные](ltags.md) и [аннотированные](atags.md).

***Легковесный тег*** — это что-то очень похожее на ветку, которая не изменяется — просто указатель на определённый коммит.

А вот ***аннотированные теги*** хранятся в базе данных Git как полноценные объекты. Они имеют контрольную сумму, содержат имя автора, его e-mail и дату создания, имеют комментарий и могут быть подписаны и проверены с помощью GNU Privacy Guard (GPG). Обычно рекомендуется создавать аннотированные теги, чтобы иметь всю перечисленную информацию; но если вы хотите сделать временную метку или по какой-то причине не хотите сохранять остальную информацию, то для этого годятся и легковесные.

[*К оглавлению*](readme.md)