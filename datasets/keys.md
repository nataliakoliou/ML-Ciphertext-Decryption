# Keys: Encryption & Decryption Alphabets

```python
# Modification-1:
117  fig, axs = plt.subplots(nrows=4, ncols=3, figsize=(12, 8))
...
120  for d in (f0, f1, f2, f3, f4, f5, f6, f7, f8, f9, f10, f11):
...
87   training_text = "TRAINING-tolstoy-anna-karenina.txt"  # approx. 99% of the book
88   testing_text = "TESTING-tolstoy-anna-karenina.txt"  # the last 1% of the book
89   decryption_alphabet = "rgbhdtkclvnqjxfspamioyzweu"  # encryption_alphabet = "rcheyobdtmgiskuqlapfzjxnvw"
```
```python
# Modification-2:
117  fig, axs = plt.subplots(nrows=3, ncols=3, figsize=(12, 8))
...
120  for d in (f0, f1, f2, f3, f4, f8, f9, f10, f11):
...
87   training_text = "TRAINING-tolstoy-anna-karenina.txt"
88   testing_text = "TESTING-goethe-werther.txt"
89   decryption_alphabet = "ghbcafmsztwnroevlixupjyqkd"  # encryption_alphabet = "ecdzofabrvyqglnuxmhjtpkswi"
```
```python
# Modification-3:
117  fig, axs = plt.subplots(nrows=3, ncols=3, figsize=(12, 8))
...
120  for d in (f1, f2, f3, f4, f5, f8, f9, f10, f11):
...
87   training_text = "TRAINING-tolstoy-anna-karenina.txt"
88   testing_text = "TESTING-pushkin-eugene-onegin.txt"
89   decryption_alphabet = "rgbhdtkclvnqjxfspamioyzweu"  # encryption_alphabet = "rcheyobdtmgiskuqlapfzjxnvw"
```
```python
# Modification-4:
117  fig, axs = plt.subplots(nrows=4, ncols=3, figsize=(12, 8))
...
120  for d in (f0, f1, f2, f3, f4, f5, f6, f7, f8, f9, f10, f11):
...
87   training_text = "TRAINING-tolstoy-anna-karenina.txt"
88   testing_text = "TESTING-nabokov-pale-fire.txt"
89   decryption_alphabet = "ghbcafmsztwnroevlixupjyqkd"  # encryption_alphabet = "ecdzofabrvyqglnuxmhjtpkswi"
```
> <sub> Choose among these modifications, edit the python code and observe the results!
