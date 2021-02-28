# Machine-Learning-from-Scratch

## Representing Points

Three different ways to define distance between two points
1. Euclidean Distance
2. Manhattan Distance
3. Hamming Distance

Euclidean Distance is the most commonly used distance formula. To find the Euclidean distance between two points, we first calculate the squared distance between each dimension. If we add up all of these squared differences and take the square root, we’ve computed the Euclidean distance. 

Manhattan Distance is extremely similar to Euclidean distance. Rather than summing the squared difference between each dimension, we instead sum the absolute value of the difference between each dimension. It’s called Manhattan distance because it’s similar to how you might navigate when walking city blocks. If you’ve ever wondered “how many blocks will it take me to get from point A to point B”, you’ve computed the Manhattan distance. 

Hamming Distance is another slightly different variation on the distance formula. Instead of finding the difference of each dimension, Hamming distance only cares about whether the dimensions are exactly equal. When finding the Hamming distance between two points, add one for every dimension that has different values. Hamming distance is used in spell checking algorithms. For example, the Hamming distance between the word “there” and the typo “thete” is one. Each letter is a dimension, and each dimension has the same value except for one.
