# HW 2
By Xu Zhang.

## Regular Expressions

#####A BIDS-style file name (set 1)

- sub-*1000*\_task-*nback*\_acq-*singleband*\_run-*03*\_*bold*
- sub-*EXP23*\_task-*rest*\_acq-*multiband*\_run-*01*\_*bold*

Regex:

```
-\w*_[bold]*
```

#####A 10 digit US phone number (set 2):
You should capture 3 groups, containing the area code, exchange and number, but not any separators or country code.

- +1 *123*\-*456*\-*7891*
- (*123*) *555*-*5555*
- *860*.*865*.*9805*
- 1-*800*-*865*-*9805*

Regex:

```
[0-9]{3,4}
```
