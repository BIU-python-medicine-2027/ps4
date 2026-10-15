# PS4 — String utilities

Implement two functions in `string_utils.py` for chemical-formula style strings.

## What to change

Edit **only** `string_utils.py`. Keep the function names exactly as below.

### 1. `split_at_first_digit(formula)`

Return `(prefix, number)`:
- `prefix` — characters before the first digit
- `number` — integer from the first digit onward
- if there are no digits, return `(formula, 1)`

```python
split_at_first_digit("H22")   # ("H", 22)
split_at_first_digit("NaCl")  # ("NaCl", 1)
```

### 2. `split_before_each_uppercases(formula)`

Split before every uppercase letter (keep those letters in the pieces).

```python
split_before_each_uppercases("NaCl")     # ["Na", "Cl"]
split_before_each_uppercases("C6H12O6")  # ["C6", "H12", "O6"]
```

## Practice in Colab (optional)

- <a href="https://colab.research.google.com/github/BIU-python-medicine-2027/ps4/blob/main/string_utils_split_at_first_digit.ipynb" target="_blank" rel="noopener noreferrer">split_at_first_digit</a>
- <a href="https://colab.research.google.com/github/BIU-python-medicine-2027/ps4/blob/main/string_utils_split_before_each_uppercases.ipynb" target="_blank" rel="noopener noreferrer">split_before_each_uppercases</a>

Notebooks are not graded — only `string_utils.py` counts.

## Submit

1. Accept the Classroom 50 assignment.
2. Edit `string_utils.py`, then **Commit changes**.
3. Check the latest autograding run for your score.

## Grading — 10 points

| Check | Points |
| --- | ---: |
| `split_at_first_digit` | 5 |
| `split_before_each_uppercases` | 5 |
