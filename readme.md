# WP-Jalali Support PHP 8.*

The only onc changed file is `lib/date.php`

The below errors are fixed.

```
PHP Fatal error:  Array and string offset access syntax with curly braces is no longer supported in /wp-content/plugins/wp-jalali/lib/date.php on line 96
PHP Fatal error:  Array and string offset access syntax with curly braces is no longer supported in /wp-content/plugins/wp-jalali/lib/date.php on line 96
PHP Fatal error:  Unparenthesized a ? b : c ? d : e is not supported. Use either (a ? b : c) ? d : e or a ? b : (c ? d : e) in /wp-content/plugins/wp-jalali/lib/date.php on line 283
PHP Fatal error:  Unparenthesized a ? b : c ? d : e is not supported. Use either (a ? b : c) ? d : e or a ? b : (c ? d : e) in /wp-content/plugins/wp-jalali/lib/date.php on line 283
```
