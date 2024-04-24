1. numpy.array is significant faster than built-in list.
2. finding item in SEt is very fast. tuple/list don't recommend in this case.
3. NamedTuples, dataclass, dictionary
4. cached: @lru_cache()
5. List comprehension if total item is small. Otherwise, use for loop
6. Generator expression vs list comprehension
7. Fast concating string: use join and f-strings instead of +. + create new variable everytime
8. try/catch (forgiveness) will create additional perfomance cost.
9. asyncio module.

