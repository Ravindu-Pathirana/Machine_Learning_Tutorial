One-Hot Encoding (Data Preprocessing)

One-Hot Encoding is a technique used in data preprocessing to convert categorical data (text labels) into a numerical format that machine learning models can understand.

Why it is needed

Most machine learning algorithms work only with numbers. Since categories like "Male", "Female" or "Red", "Blue" are text values, they must be converted into numeric form without creating false order or priority.

How it works

Each category is converted into a separate binary column:
• 1 → category is present
• 0 → category is absent

Example

Original data:

Color
Red
Blue
Green

After One-Hot Encoding:

Red Blue Green
1 0 0
0 1 0
0 0 1

Advantages
• Prevents incorrect ranking between categories
• Works well with linear and distance-based models
• Simple and widely used in real-world ML projects

When to use
• For nominal categorical data (no natural order)
• Commonly used before training models like Linear Regression, Logistic Regression, and Neural Networks
