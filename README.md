# cake-app-ui


| **Symbol**     | **Meaning**                                                  | **Example**                                                       |
| -------------- | ------------------------------------------------------------ | ----------------------------------------------------------------- |
| **`!`**        | **Non-nullable (required)**                                  | **`name: String!` — must have a value**                           |
| **No `!`**     | **Nullable (optional)**                                      | **`description: String` — can be null**                           |
| **`[]`**       | **List/Array**                                               | **`[String]` — list of strings**                                  |
| **`[Type]!`**  | **Non-null list (list itself can't be null, but items can)** | **`[String]!` — returns `[]` or `["a", null, "b"]`**              |
| **`[Type!]!`** | **Non-null list of non-null items**                          | **`[String!]!` — returns `[]` or `["a", "b"]`, never null items** |
|                |                                                              |                                                                   |
