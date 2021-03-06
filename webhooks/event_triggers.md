## Events Triggers

### Products

#### store/product/created

- When a product is created from the control panel
- When a product is created from product import
- When a product is created via the API

#### store/product/updated

- When a product is changed in the control panel
- When a product is updated via the API
- When a product is updated from product import. Explicitly including the following fields:
  * brand
  * product type
  * category
  * inventory
  * number sold
  * availability
  * thumbnail
  * visibility
  * featured
  * name
  * description
  * sort order
  * price
  * dimensions
  * condition
  * tax price
  * url
- When a review is added to a product
- When product inventory is changed via the Stone Edge module
- When product inventory is changed as a result of a purchase

__Note**__ _At this point in time, changes to product options will not trigger a store/product/updated event._


#### store/product/deleted

- When a product is deleted from the control panel
- When a product is deleted via the API

### Customers

#### store/customer/created

- When a customer registers (adhoc or during the purchase process) via the storefront
- When a customer is created in the control panel

#### store/customer/updated

- When a customer updates their details via their account in the storefront
- When a customer is updated in the control panel

#### store/customer/deleted

- When a customer is deleted in the control panel

### Orders

#### store/orders/created

- When an order is created via checkout
- When a manual order is created via the control panel

#### store/orders/updated

- When an order is updated via the control panel
- When the order status is updated via the control panel
- When the order status is updated via the API

#### store/orders/archived

- When the order is archived from the control panel

### Store

#### store/app/uninstalled

- When the store has been removed from the system
