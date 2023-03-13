Purpose of this analysis is the find the courier charges as per the company X and then compare it with the charges billed by the courier company. Also, find the number of orders and the amount of the orders where the company X has been correctly charged, overcharged, and undercharged.


Company X is a large ecommerce company and it gets a thousand order via their wesbite on daily basis. For delivering the goods ordered by the customers,X has tied with courier company as delivery partner who charge them some amount per delivery.

Charges depends on 2 factors:
1. Weight of the product
2. Distance between the warehouse(pickup location) and customers delivery address(destination location)

As the amount that X has to pay to the courier company is very high, they want to verify if the charges levied by the delivery partner per order are correct.

  The courier company calculates weight in slabs that is applicable for that delivery zone, so first I figured out the total weight of the shipment and the figure out applicable weight.
For example- total weight is 400gm and zone is A so applicable weight slab is 0.25 and applicable weight will be 0.5kg.


For the first slab of that zone, "fixed" rate as per the table is applicable. For each additional slab, "additional" weight in the same proportion is applicable. Total charge will be "fixed" + "additional" if any. for example- weight = 2.22kg, zone-C, So for zone C the slab length = 0.75kg. So the total applicable weight = 2.25kg. 
For the first 0.75kg the charge is  forward charges, and for each 0.75 kg after the first, charges will be additional charges.
