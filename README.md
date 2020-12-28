# PHPml (PHP in HTML)

Snippets for PHP Templates + baseURL PHP framework to JS

## Donating

For Indonesian, you can donate on [Saweria](https://saweria.co/yansaan) | [Karyakarsa](http://karyakarsa.com/yansaan) | [Trakteer](http://trakteer.id/yansaan)
For other regional, you can donate on [Patreon](https://patreon.com/yansaan_) | [PayPal](https://www.paypal.me/yansaanID)

## How To Use?

### 1. Snippets fo PHP Template

| Prefix     | Method                                                                        | Info                                       |
| ---------- | ----------------------------------------------------------------------------- | ------------------------------------------ |
| phpif      | `<?php if (sometime): ?> #thisTrue <?php endif ?>`                           | -                                           |
| phpelse    | `<?php else: ?>`                                                              | Add this inside if in last (php templates) |
| phpelseif  | `<?php else if (more_sometime): ?>`                                          | Add this inside if (php templates)          |
| phpifelse  | `<?php if (sometime): ?> #thisTrue <?php else: ?> #thisFalse <?php endif ?>` | -                                           |
| phpfor     | `<?php for( i = 0; i < num; i++): ?><?php endfor; ?>`               | -                                                    |
| phpforeach | `<?php foreach (array as $a): ?> loooop <?php endforeach; ?>`                | -                                           |

### 2. Snippets PHP Tags

| Prefix    | Method                                                           | Info                                               |
| --------- | ---------------------------------------------------------------- | -------------------------------------------------- |
| php       | `<?php`                                                          | only php script (for class)                        |
| phph      | `<?php #code; ?>`                                                | -                                                  |
| echo      | `<?= this_echo ?>`                                               | arternative `<?php echo this_echo; ?>`             |
| echoif    | `<?= ($if) ? true : false ?>`                                    | echo ternary                                       |
| echonull  | `<?= $null ?-> $result ?>`                                       | echo null ternary (php 8 only)                     |
| echomatch | `<?= match(someware) {true => "result", default => "result"} ?>` | echo match ternary (php 8 only)                    |

### 3. BONUS!!! JS Base URL

> Prefix **`setbaseurl`**
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
| **`baseurl`**  | for string literal (ES6)                    |
| **`baseurl1`** | for normal sring with single quotation mark |
| **`baseurl2`** | for normal sring with double quotation mark |

## Support

For help and fix the snippet, visit my [Repository](https://github.com/yansaan/phpml)

## Release Notes

### 0.6
- Delete $ and ; snippet
- change base url snippet
- Add null operator for echo snippet
- Add match operator for echo snippet

### 0.5.7

Change Readme

### 0.5.6

Fix phpforeach

### 0.5.2

Add logo and restaring git

### 0.5

Initial release
