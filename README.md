# encoderLabel Encoder:

Label encoding is a type of encoding where categorical variables are mapped to integer labels.
Each unique category is assigned a unique integer label.
Label encoding is suitable for ordinal variables where the order of categories is important.
Example: Encoding the categories "red", "green", "blue" as 0, 1, 2.
One-Hot Encoder:

One-hot encoding is a technique where categorical variables are transformed into binary vectors.
Each category becomes a separate binary feature, and only one feature is 1 (hot) while the others are 0 (cold).
One-hot encoding is useful for nominal variables without any inherent order.
Example: Encoding the categories "red", "green", "blue" as [1, 0, 0], [0, 1, 0], [0, 0, 1].
Ordinal Encoder:

Ordinal encoding is used for encoding ordinal categorical variables.
It assigns unique integers to each category, considering the order or rank of the categories.
Ordinal encoding preserves the ordinal relationship between categories.
Example: Encoding the categories "low", "medium", "high" as 0, 1, 2.
Binary Encoder:

Binary encoding is similar to one-hot encoding but uses binary digits (0 and 1) instead of full binary vectors.
Each category is mapped to a unique binary code, and the number of binary digits used is log2(N), where N is the number of categories.
Binary encoding is useful when dealing with a large number of categories.
Example: Encoding the categories "red", "green", "blue" as 00, 01, 10.
Hashing Encoder:

Hashing encoding uses a hash function to encode categorical variables into a fixed number of dimensions.
The encoding is typically performed using a hashing trick, where the hash function maps categories to numerical indices.
Hashing encoding is memory-efficient and allows for dimensionality reduction.
Example: Encoding the categories "red", "green", "blue" using a hash function.
Frequency Encoder:

Frequency encoding replaces each category with the frequency (count) of that category in the dataset.
This encoding captures the relationship between categories and their occurrence in the dataset.
Frequency encoding can be useful when the frequency of categories is informative for the target variable.
Example: Encoding the categories "red", "green", "blue" based on their frequency counts.
