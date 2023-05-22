# SyntheticDataGenerator

SyntheticDataGenerator: A Python library for data analysts to generate synthetic datasets

# Example usage

```
column_specs = [
    ('Column1', 'int'),
    ('Column2', 'float'),
    ('Column3', 'str'),
    ('Column4', 'date')
]
num_rows = 20
include_nulls = True
str_categories = ['apple', 'banana', 'cherry', 'orange', 'dragonfruit', 'eggplant']
start_date = '2022-01-01'
end_date = '2023-05-22'

df = generate_synthetic_data(column_specs, num_rows, include_nulls, str_categories, start_date, end_date)

print(df)
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
