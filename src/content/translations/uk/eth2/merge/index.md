---
title: Об’єднання
description: Дізнайтеся більше про об’єднання — коли основна мережа Ethereum приєднається до координованої системи доказу частки володіння Beacon Chain.
lang: uk
template: eth2
sidebar: true
image: ../../../../../assets/eth2/merge.png
summaryPoint1: Врешті-решт поточна основна мережа Ethereum об’єднається із системою доказу частки володіння Beacon Chain.
summaryPoint2: Це стане кінцем моделі доказу виконаної роботи для Ethereum і моментом повного переходу на систему доказу частки володіння.
summaryPoint3: Це планується до розгортання ланцюгів сегментів даних.
summaryPoint4: Раніше ми називали це злиттям.
---

<UpgradeStatus date="~Q2 2022">
  Це оновлення являє собою офіційне досягнення консенсусу щодо доказу частки володіння. Це усуває потребу в енергоємному майнінгу та натомість захищає мережу завдяки використанню криптовалюти ether, що залучена до стейкінгу. Насправді цікавий крок у реалізації <a href="/eth2/vision/">бачення Eth2</a> — крок до більшої масштабованості, безпеки та стабільності.
</UpgradeStatus>

## Що таке об’єднання? {#what-is-the-docking}

Важливо пам’ятати, що спочатку [Beacon Chain](/eth2/beacon-chain/) запускається окремо від [основної мережі](/glossary/#mainnet) — ланцюга, яким ми користуємося сьогодні. Безпека основної мережі Ethereum і надалі реалізується за моделлю [доказу виконаної роботи](/developers/docs/consensus-mechanisms/pow/), навіть якщо запущено Beacon Chain, де паралельно використовується система [доказу частки володіння](/developers/docs/consensus-mechanisms/pos/). Об’єднання відбувається, коли ці дві системи зрештою об’єднуються.

Уявіть, що мережа Ethereum – це космічний корабель, який не зовсім готовий до польоту в космос. За допомогою Beacon Chain спільноті вдалося побудувати новий двигун і міцніший корпус. Коли прийде час, наявний корабель виконає стикування з цією новою системою, об’єднавшись в один корабель, готовий до польоту тривалістю у кілька світлових років, і зможе підкорити всесвіт.

## Об’єднання з основною мережею {#docking-mainnet}

Коли прийде час, основна мережа Ethereum об’єднається з Beacon Chain і стане окремим сегментом даних, що використовує принцип доказу частки володіння замість [доказу виконаної роботи](/developers/docs/consensus-mechanisms/pow/).

Основна мережа дасть змогу запускати розумні контракти в системі доказу частки, а також керувати всією історією та поточним станом мережі Ethereum. Так перехід на нову версію буде плавним для всіх власників криптовалюти й користувачів мережі Ethereum.

## Після об’єднання {#after-the-merge}

Цим завершиться застосування в Ethereum доказу виконаної роботи, після чого почнеться ера сталішої та екологічнішої технології Ethereum. На цьому етапі Ethereum стане на крок ближче до досягнення повної масштабованості, безпеки та сталості відповідно до [бачення Eth2](/eth2/vision/).

Важливо зауважити, що метою реалізації об’єднання є спрощення, яке дасть змогу прискорити перехід від принципу доказу виконаної роботи до моделі доказу частки володіння. Розробники зосереджують свої зусилля на цьому переході та мінімізують додаткові функції, які можуть затримати досягнення цієї мети.

**Це означає, що реалізації деяких функцій, як-от можливість виводити ETH, які залучені до стейкінгу, доведеться зачекати, доки не буде завершено об’єднання.** У планах здійснити після об’єднання «чистове» оновлення, що стосуватиметься цих функцій. Як очікується, воно відбудеться дуже скоро після об’єднання.

## Зв’язок між оновленнями {#relationship-between-upgrades}

Усі оновлення Eth2 певним чином пов’язані. Тому підсумуємо, як об’єднання пов’язане з іншими оновленнями.

### Об’єднання та Beacon Chain {#docking-and-beacon-chain}

Одразу після завершення об’єднання, стейкери будуть призначені для валідації основної мережі Ethereum. [Майнінг](/developers/docs/consensus-mechanisms/pow/mining/) більше не використовуватиметься, тому майнери, найімовірніше, інвестуватимуть свої кошти в стейкінг у новій системі доказу частки володіння.

<ButtonLink to="/eth2/beacon-chain/">Beacon Chain</ButtonLink>

### Об’єднання та очищення після об’єднання {#merge-and-post-merge-cleanup}

Відразу після об’єднання деякі функції, як-от виведення ETH, які залучені до стейкінгу, ще не підтримуватимуться. Планується, що це виправить окреме оновлення, яке відбудеться незабаром після об’єднання.

Залишайтеся в курсі подій завдяки [блоку EF про дослідження та розробку](https://blog.ethereum.org/category/research-and-development/). Крім того, можна дізнатися більше про те, [що відбудеться після об’єднання](https://youtu.be/7ggwLccuN5s?t=101) з презентації Віталіка на заході ETHGlobal у квітні 2021 року.

### Об’єднання та ланцюги сегментів даних {#docking-and-shard-chains}

Спочатку план полягав у роботі над ланцюгами сегментів даних до об’єднання, щоб вирішити проблему масштабованості. Однак унаслідок буму на [рішення для масштабування 2-го рівня](/developers/docs/scaling/#layer-2-scaling) пріоритетом став перехід із моделі доказу виконаної роботи на систему доказу частки володіння шляхом об’єднання.

Спільнотою постійно оцінюватиметься необхідність потенційного проведення кількох раундів ланцюгів сегментів даних, щоб забезпечити нескінченну масштабованість.

<ButtonLink to="/eth2/shard-chains/">Ланцюги сегментів даних</ButtonLink>
