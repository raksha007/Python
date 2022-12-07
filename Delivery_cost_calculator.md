```bash
international_shipping = True

total = 150

shipping_cost = 0
```
```bash
if international_shipping: 
  shipping_cost += 15
  print("International base cost applied")
  ```
```bash
if total <= 50:
  shipping_cost += 20
  ```
  ```bash
elif total <= 100:
  shipping_cost += 15
  ```
  ```bash
else:
  shipping_cost += 5


print(f"Shipping cost: {shipping_cost}")
```
