## FreeDict (.tei)

### General Information

| Attribute       | Value                                                                              |
| --------------- | ---------------------------------------------------------------------------------- |
| Name            | FreeDict                                                                           |
| snake_case_name | freedict                                                                           |
| Description     | FreeDict (.tei)                                                                    |
| Extensions      | `.tei`                                                                             |
| Read support    | Yes                                                                                |
| Write support   | No                                                                                 |
| Single-file     | Yes                                                                                |
| Kind            | 📝 text                                                                             |
| Sort-on-write   | default_no                                                                         |
| Wiki            | [@freedict/fd-dictionaries/wiki](https://github.com/freedict/fd-dictionaries/wiki) |
| Website         | [FreeDict.org](https://freedict.org/)                                              |

### Read options

| Name            | Default | Type | Comment                                       |
| --------------- | ------- | ---- | --------------------------------------------- |
| discover        | `False` | bool | Find and show unsupported tags                |
| auto_rtl        | `None`  | bool | Auto-detect and mark Right-to-Left text       |
| word_title      | `False` | bool | Add headwords title to begining of definition |
| pron_color      | `gray`  | str  | Pronunciation color                           |
| gram_color      | `green` | str  | Grammar color                                 |
| example_padding | `10`    | int  | Padding for examples (in px)                  |

### Dependencies for reading

PyPI Links: [lxml](https://pypi.org/project/lxml)

To install, run:

```
pip3 install lxml
```



