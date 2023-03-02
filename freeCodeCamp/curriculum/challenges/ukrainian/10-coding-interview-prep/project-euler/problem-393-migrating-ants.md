---
id: 5900f4f61000cf542c510008
title: 'Задача 393: Міграція мурах'
challengeType: 1
forumTopicId: 302058
dashedName: problem-393-migrating-ants
---

# --description--

Сітка квадратів $n×n$ містить $n^2$ мурашок, по одній мурашці на квадрат.

Усі мурахи вирішують одночасно переміститися до сусіднього квадрата (зазвичай є 4 варіанти, за винятком мурашок на краю сітки або по кутах).

Ми визначаємо, що $f(n)$ - це кількість способів, за яких це може статися без того, щоб мурашки опинилися на одному й тому ж квадраті, і без того, щоб дві мурашки перетинали один і той самий край між двома квадратами.

Вам дано, що $f(4) = 88$.

Знайдіть $f(10)$.

# --hints--

`migratingAnts()` повинен повертати `112398351350823100`.

```js
assert.strictEqual(migratingAnts(), 112398351350823100);
```

# --seed--

## --seed-contents--

```js
function migratingAnts() {

  return true;
}

migratingAnts();
```

# --solutions--

```js
// solution required
```