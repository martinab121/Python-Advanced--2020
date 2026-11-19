# Python Advanced – SoftUni (2020)

Solutions to the labs and exercises of the [Python Advanced course at SoftUni (January 2020)](https://softuni.bg/trainings/2496/python-advanced-january-2020#lesson-14226).

Each topic is a single plain-text file (no extension) containing the solutions to that lesson's problems, one after another, each headed by its problem number (`1.`, `2.`, ...).

## Topics

| Topic | What it practises | Solutions |
|---|---|---:|
| [Lists as Stacks and Queues - Lab](Lists%20as%20Stacks%20and%20Queues%20-%20Lab) | Using lists as stacks, `collections.deque` as a queue | 5 |
| [Lists as Stacks and Queues - Exercise](Lists%20as%20Stacks%20and%20Queues%20-%20Exercise) | Stack/queue simulations and bracket matching | 9 |
| [Tuples and Sets - Lab](Tuples%20and%20Sets%20-%20Lab) | Tuples, sets, set operations | 5 |
| [Tuples and Sets - Exercise](Tuples%20and%20Sets%20-%20Exercise) | Unique elements, intersections, counting with sets | 6 |
| [Multidimensional Lists - Lab](Multidimensional%20Lists%20-%20Lab) | Matrices: reading, traversing, summing | 5 |
| [Multidimensional Lists - Exercise](Multidimensional%20Lists%20-%20Exercise) | Matrix manipulation and grid-movement problems | 8 |
| [Comprehensions - Lab](Comprehensions%20-%20Lab) | List, set and dict comprehensions | 5 |
| [Comprehensions - Exercise](Comprehensions%20-%20Exercise) | Data transformation with comprehensions | 9 |
| [Lambdas and Buit In Functions - Exercise](Lambdas%20and%20Buit%20In%20Functions%20-%20Exercise) | `lambda`, `map`, `filter`, `sorted`, built-ins | 9 |
| [Functions Advanced - Lab](Functions%20Advanced%20-%20Lab) | `*args`, keyword arguments, recursion (string combinations) | 11 |
| [Functions Advanced - Exercise](Functions%20Advanced%20-%20Exercise) | `map`, `filter`, `lambda`, `sorted`, `min`/`max`/`sum` | 5 |
| [Functions Advanced -practice](Functions%20Advanced%20-practice) | Extra practice: recursive binary search and merge sort | 2 |

**Total: 79 solved problems.**

## How to run

The files are not standalone scripts – the numbered headers (`1.`, `2.`, ...) separate the individual solutions. To try one:

1. Copy a single solution (the code below one number, up to the next) into a file, e.g. `solution.py`.
2. Run it with Python 3 and type the input, or pipe it in:

```bash
python3 solution.py
echo "5" | python3 solution.py
```

Most solutions read their input from stdin with `input()` and print the result, as required by the SoftUni Judge system.

## Tech

Python 3 (standard library: `collections`)
