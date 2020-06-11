# PHPml (PHP in HTML)

Snippets for PHP Templates + baseURL PHP framework to JS

## How To Use?

### 1. Snippets fo PHP Template

| Prefix     | Method                                                                        | Info                                       |
| ---------- | ----------------------------------------------------------------------------- | ------------------------------------------ |
| phpif      | `<?php if ($sometime): ?> #thisTrue <?php endif ?>`                           | -                                          |
| phpelse    | `<?php else: ?>`                                                              | Add this inside if in last (php templates) |
| phpelseif  | `<?php else if ($more_sometime): ?>`                                          | Add this inside if (php templates)         |
| phpifelse  | `<?php if ($sometime): ?> #thisTrue <?php else: ?> #thisFalse <?php endif ?>` | -                                          |
| phpfor     | `<?php for( i = 0; i < num; i++): ?> loooooop <?php endfor; ?>`               | -                                          |
| phpforeach | `<?php foreach ($array as $a): ?> loooop <?php endforeatch; ?>`               | -                                          |

### 2. Snippets PHP Tags

| Prefix  | Method                         | Info                                               |
| ------- | ------------------------------ | -------------------------------------------------- |
| php     | `<?php`                        | only php script (for class)                        |
| phph    | `<?php #code; ?>`              | -                                                  |
| echo    | `<?= this_echo ?>`             | arternative `<?php echo this_echo; ?>`             |
| echo\$  | `<?= $var ?>`                  | for echo/print variable (\$)                       |
| echo;   | `<?= this_echo; ?>`            | for add semicolon (;)                              |
| echo\$; | `<?= $this_echo; ?>`           | for echo/print variable (\$) and add semicolon (;) |
| echoif  | `<?= ($if) ? true : false ?>`  | echo ternary                                       |
| echoif; | `<?= ($if) ? true : false; ?>` | echo ternary and add semicolon (;)                 |

### 3. BONUS!!! JS Base URL

> Prefix **`jsbaseurl`**
>
> **Result:**
>
> Codeigniter
> `<script> const baseUrl = <?= base_url() ?> </script>`
>
> Laravel
> `<script> const baseUrl = <?= url() ?>` or `{{url()}} </script>`

| Prefix         | Info                                        |
| -------------- | ------------------------------------------- |
| **`'baseurl`** | for normal sring with single quotation mark |
| **`"baseurl`** | for normal sring with double quotation mark |
| **`baseurl`**  | for string literal (ES6)                    |

## Support me!

For help and fix the snippet, visit my [Repository](https://github.com/yansaan/phpml)
For info, click [HERE](http://yansaan.indoweb.xyz/support)

## Release Notes

### 0.5.6

Fix phpforeach

### 0.5.2

Add logo and restaring git

### 0.5

Initial release

---
