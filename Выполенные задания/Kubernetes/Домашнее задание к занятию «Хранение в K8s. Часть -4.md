## Задание 1

Создаю деплой для подов и pv/pvc

![819135ee389a20b934fb582763492ad8.png](../_resources/819135ee389a20b934fb582763492ad8-1.png)

Шара из multitool

![ff05e6b5274eab9d503f49760bcd8434.png](../_resources/ff05e6b5274eab9d503f49760bcd8434-1.png)

Удаляю PVC

![6a1c5276bf2aea35c77334747ca29be8.png](../_resources/6a1c5276bf2aea35c77334747ca29be8-1.png)

PV останется, но он не используется.

![9ba662aaba19ad7f7a5d932a8942e7ba.png](../_resources/9ba662aaba19ad7f7a5d932a8942e7ba-1.png)

Захожу на ноду смотрю файл.

![1712db60c7b7e1ee7a24e41c46f64d70.png](../_resources/1712db60c7b7e1ee7a24e41c46f64d70-1.png)


Удаляю PV

![317fd5295b55de87db2889c5362f5ad4.png](../_resources/317fd5295b55de87db2889c5362f5ad4-1.png)

Проверяю,файл остался на диске ноды, PV представляет доступ до файла но не управляет им.

![16cf791f78c75edd57a574a883112353.png](../_resources/16cf791f78c75edd57a574a883112353-1.png)

## Задание 2

Включил NFS создаю деплой.

![3fdcb79b304709ae827c0f74d22e377e.png](../_resources/3fdcb79b304709ae827c0f74d22e377e-1.png)

PV

![14853d30cc3a59444599fec0f548c513.png](../_resources/14853d30cc3a59444599fec0f548c513-1.png)

Проверяю. Захожу на под, создаю файл, читаю.

![f0b7e5d8d30c7b64d3f138d7b5a0fed6.png](../_resources/f0b7e5d8d30c7b64d3f138d7b5a0fed6-1.png)
