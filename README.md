# Singular-Approximation
IPython notebook, that demonstates how singular value decomposition may approximate images
### What it is
Изображение является 3-мерным тензором элементы которого лежат в диапазоне [0, 255]. Тензор можно представить как три матрицы, соответсвующие синему, зеленому и красному цветам. 

Каждая матрица, как известно из линейной алгебры, имеет сингулярное разложение. Если взять часть сингулярного разложения, соотвутсвующую k самым большим числам, то получится малоранговое приближение матрицы - приближение матрицей ранга k. Беря малое k можно получить искаженную и размытую версию исходной матрицы и добиться живописного глитч-эффекта.

Соответсвенно, программа производит описанную процедуру приближения изображения малоранговыми матрицами. Вот так выглядит результат:
![image](https://user-images.githubusercontent.com/43682987/133940409-f6c0c8ec-c463-41f8-a6a1-681c74f03f73.png)


