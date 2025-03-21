| Function          | Method          | Attribute       |
|-------------------|-----------------|-----------------|
| `pd.read_csv()`   | `head()`        | `shape`         |
| `pd.read_excel()` | `tail()`        | `columns`       |
| `pd.read_json()`  | `describe()`    | `index`         |
| `pd.DataFrame()`  | `info()`        | `dtypes`        |
| `pd.Series()`     | `drop()`        | `values`        |
|                   | `dropna()`      | `transpose`     |
|                   | `fillna()`      |                 |
|                   | `groupby()`     |                 |
|                   | `merge()`       |                 |
|                   | `concat()`      |                 |
|                   | `copy()`        |                 | 
|                   | `to_numpy()`     |  |
|| `sort_index(axis= ,na_position = , sort_remaining = True/False, inplace = )`     ||
|| `sort_values(by=['column name'],na_position = , sort_remaining = True/False, inplace = )`||
||`iloc[only index no,column no]`||
||`loc[index label , row label]`|| 
||`reset_index(drop = True, inplace=True)`|| 
||`mean()`|| 
||`max()`|| 
||`median()`||
||`count()`|| 
||`drop_duplicates(subset=[],keep = '')`||
