# Gaadha-Jeevan
This python script shows the flavor choices and allergies of 3 customers in an ice cream shop. The code asks each customer to choose a flavor from given list or allows them to suggest a new flavor if the preferred one is unavailable. It also checks for allergies and updates the list if new ones exist. Finally, the items in the cart is shown.

seasonal_flavors - array containing list of flavors;
ingredient_inventory - array containing list of ingredients used;
Allergies - list of known allergies;
customer_sugg - list to store flavor suggestions from customers;
cart - flavors chosen by customers are stored;

The for loop iterates to represent customers (here 3).
Customer is asked to input and flavor, if it's there in seasonal_flavors it is added to cart. If not present the customer would be asked to suggest  a new flavor.
Customer is also asked to input if they have any allergies. If the entered allergy is present in the array 'Allergies', 'already listed' is printed otherwise it is added to it.
Finally the items in the cart is printed.
