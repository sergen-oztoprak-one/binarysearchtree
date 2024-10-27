[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamaları:

1. **Öncelikle `7` root kabul edilir.**
2. `5`, `7`'den küçük olduğu için soluna yerleştirilir.
3. `1`, `7` ve `5`'ten küçük olduğu için ikisinin de soluna yerleştirilir.
4. `8`, `7`'den büyük olduğu için sağına eklenir.
5. `3`, `7` ve `5`'ten küçük, `1`'den büyük olduğu için `1`'in sağına yazılır.
6. `6`, `7`'den küçük, `5`'ten büyük olduğu için `5`'in sağına yazılır.
7. `0`, `7`, `5` ve `1`'den küçük olduğu için `1`'in soluna yazılır.
8. `9`, `7`'den ve `8`'den büyük olduğu için `8`'in sağına yazılır.
9. `4`, `7` ve `5`'ten küçük, `1`'den ve `3`'ten büyük olduğu için `3`'ün sağına yazılır.
10. `2`, `7` ve `5`'ten küçük, `1`'den büyük, `3`'ten küçük olduğu için `3`'ün soluna yazılır.

Oluşan Binary Search Tree yapısı şu şekilde olur:

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
