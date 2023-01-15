Висота сходинок опор
====

### **Опис**

Якщо для параметра [Розташування опор](../support/support_type.md) встановлено значення «Будь-де», опора може спиратися на модель. Однак вона не буде точно повторювати контури моделі. Замість цього нижній стороні опори будо надано вигляд сходів. Таким чином підтримки спираються на модель лише в кількох місцях.

Цей параметр визначає висоту цих сходинок.

![Stair steps forming at the bottom of support](../images/support_bottom_stair_step_height.png)

### **Вплив**

Налаштування [Максимальна ширина сходинок опор](support_bottom_stair_step_width.md) обмежує ширину сходинок. Якщо поверхня моделі настільки мілка, що мала висота сходинки призвела б до величезної ширини сходинки, опора слідуватиме за поверхнею моделі протягом решти висоти сходинки.

Зменшення цього параметра зробить нижню частину опори більш гладкою. Це збільшує зчеплення між опорою та моделлю, роблячи опору більш стабільною, але також ускладнюючи її видалення.