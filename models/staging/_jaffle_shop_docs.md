{% docs order_status %}
    
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs payment_method %}
    
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| gift_card      | Order has been paid with gift card               |
| credit_card    | Order has been paid with credit card             |
| coupon         | Order has been paid with coupon                  |
| bank transfer  | Order has been paid with bank transfer           |

{% enddocs %}