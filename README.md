# Interview Task

Build a function which will return a minimum number of banknotes and coins
according to product/service price and provided banknote to pay with it.

Available banknotes:

- 100 eur
- 50 eur
- 20 eur
- 10 eur
- 5 eur
- 1 eur
- 50 cent
- 20 cent
- 10 cent
- 5 cent
- 1 cent

### Example:

**If product price is 80.03 and if customer pays with 100 eur the cashier
will return:** 

- 1 x 10 eur, 
- 1 x 5 eur, 
- 4 x 1 eur,
- 1 x 50 cent,
- 4 x 10 cents,
- 1 x 5 cent,
- 2 x 1 cent


#### Note: 

1 Eur has 100 cents.

## Run Tests

```vendor/bin/phpunit```