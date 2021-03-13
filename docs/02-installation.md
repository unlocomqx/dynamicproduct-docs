# Installation

The module installation requires no special steps.  
Simply upload the zip through the Modules Manager page and the module will be installed normally.

<img srcset="./images/install.jpg 2x" class="border">

## Overrides
The module will install the following overrides automatically:
- **Carrier** override  
  Path: **/override/classes/Carrier.php**  
  Methods: 
  - **getAvailableCarrierList**: used to filter carriers based on the product size
  
- **Cart** override  
  Path: **/override/classes/Cart.php**  
  Methods: 
  - **duplicate**: used to detect the reorder feature and to duplicate the module customizations
  
- **Product** override  
  Path: **/override/classes/Product.php**  
  Methods: 
  - **getProductProperties**: used to alter the product displayed price in category page when a display price is configured