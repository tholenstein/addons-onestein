Often the total discount on a sale order line is the result of multiple cumulative discounts offered
to the customer for different reasons. Sometimes, it's desirable to display a detail of how the total
discount on a SO line was computed.

This module allows to express discounts on SO lines as mathematical expressions rather than a single number.
For example, if I wish to offer to a particular customer a 10% discount for the selected payment method and
an additional 20% discount for the selected payment term, on Odoo I should write a total discount of 28%;
Using this module, instead, I can simply write '10+20' in the discount column.

This module implements this feature also on invoices, and takes care of propagating a discount expression from
a sale order to its destination invoice(s).
