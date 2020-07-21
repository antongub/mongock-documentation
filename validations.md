# Validations



{% hint style="info" %}
**Feature under development.** Will be delivered in next releases.
{% endhint %}

With validation after a changeSet has been executed, you can check if it fulfilled your expectations. If that's not the case, it will throw an Exception, be treated as `FAILED` changeSet and will activate the required mechanism to counter the effects\(transaction rollback, recovery, etc\)       
