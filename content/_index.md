+++
title = "CDE"
backgroundImage = 'img/back-soti.png'
outputs = ["Reveal"]
theme = "night"
margin = 0
[logo]
src = "logos/logo.png"
width = "7%"
[params]
backgroundImage = 'img/back-soti.png'
+++

## Развертывание CDE через каталог Алауды

---
{{% section %}}
Для развертывания CDE внутри своего пространства имен в кластере - необходимо войти в каталог Алауды

---

![catalog](img/ph.png)

{{% /section %}}

---

{{% section %}}
Находим нужный Helm Чарт и заполняем форму.

---

![catalog](img/ph2.png)

---

![catalog](img/ph3.png)

{{% /section %}}

---

- Extra Args Flag - включает ввод пароля перед входом в CDE
- Password - устанавливает значение пароля
- Host Name - устанавливает значение домена CDE
- Full Annotation - устанавливает значение сертификатов 
- Role Flag - включает возможность связи kubectl с пространством имен Алауды 

---

{{% section %}}
После чего Вам будет доступна CDE по ссылке, ранее указанной Вами в форме развертывания. 

---

![catalog](img/ph6.png)

{{% /section %}}
