#E-Commerce Design Assigment
##High Level Design
![hld](photo/highleveldesign.png)
Use sequence diagrams because sequence diagrams can represent high-level interactions between systems or sub-systems at a high level.

## Create Order Details

![Order Detail](photo/classdiagram.png)

### Explanation

Pseudocode :

```
function ProductOrdering(){ do request stock + generate order detail
if productstock is available {
UpdateDetail() + QuantityDecreasing
}
else {
(Print("Out of Stock")
}

Function getPriceForQuantity(){
let totalPrice = 0
for product in ProductOrdering:
totalPrice = OrderQuantity * Price
productStock = 1

return Customer

}
Fuction QuantityDecreasing(){
Void product
}
```

## Complexity Analysis

The complexity of creating a order is $O(n * m)$ with n=quantity and m=price. I got this complexity because Time Complexity of a loop is considered as  $O(n * m)$ if the loop variables are incremented/decremented by a constant amount.
