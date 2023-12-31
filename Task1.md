# Задание 1: Собираем простой платформер

## Требования

В этом задании мы соберем простой платформер. Нашим игровым персонажем будет обычный шар. Создайте небольшой уровень из обычных примитивов, это будут препятствия для нашего персонажа. Шар должен подчиняться законам физики и иметь возможность двигаться под управлением игрока на WASD.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_video1.gif" width="600"/>

## Инструкция

1. Откройте Unity и создайте новый проект.

2. Создайте пол (землю), по которому будет перемещаться наш персонаж. (Используйте Cube, Quad или Plane)

3. Создайте простой объект Sphere (это будет наш персонаж). Добавьте компонент Rigidbody.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image0.png" width="800"/>

4. Настройте камеру так, чтобы она смотрела на мяч сверху и немного под углом.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image1.png" width="800"/>

5. Создайте препятствий на нашем игровом уровне (Используйте базовые объекты, изменяйте их позицию, поворот и масштаб)

6. Добавьте материалы, чтобы лучше различать объекты на экране.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image2.png" width="800"/>

7. Закиньте в проект какую-нибудь картинку (например, кирпичную стену или разметку футбольного мяча) и навесьте картинку на шар в сцене. Это автоматически создаст материал. Натянуть прямоугольную текстуру на круглый базовый шар в Unity это нетривиальная задача, поэтому не страшно, если на полюсах у вас будет искажение рисунка.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image3.png" width="800"/>

8. Создайте скрипт PlayerController

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image4.png" width="800"/>

9. Добавьте компонент с вашим скриптом на шар.

10. Укажите в инспекторе значение скорости и ссылку на Rigidbody шара.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image5.png" width="800"/>

11. По экперементируйте с физическим материалом. Создай его, подбери параметры трения и упругости. 

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image6.png" width="800"/>

12. Не забудьте указать ссылку на свой физический материал в компоненте Sphere Collider нашего шара.

<img src="https://github.com/copetonrob/YP_Unity_M2_W6/blob/main/img/T1_image7.png" width="800"/>

