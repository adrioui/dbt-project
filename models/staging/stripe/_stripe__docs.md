{% docs payments_payment_method %}
    
One of the following values: 

| payment_method | definition                                                                   |
|----------------|------------------------------------------------------------------------------|
| credit_card    | Payment card that allows borrowing funds for purchases with deferred payment |
| coupon         | Discount code or voucher that reduces purchase price                         |
| bank_transfer  | Direct electronic transfer of funds between bank accounts                    |
| gift_card      | Prepaid card with stored value for purchases at specific retailers           |

{% enddocs %}

{% docs payments_status %}

One of the following values:

| status  | definition                                                                          |
|---------|-------------------------------------------------------------------------------------|
| success | Payment transaction completed successfully and funds were transferred               |
| fail    | Payment transaction was unsuccessful due to error, insufficient funds, or rejection |

{% enddocs %}
