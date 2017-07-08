# Bamazon

## bamazonCustomer Instructions

1. Run "node bamazonCustomer.js" on command line

2. You will see the list of products. Listed as ID#) ITEM | PRICE($) 
    - Enter product's id
    - Enter number of units you would like to purchase

3. You will be asked if you want to continue shopping
    - If "yes", you will be returned to step 2
    - If "no", you will be prompted to step 4

    ![customerMainMenu](images/bamazonCustomer1.png)

4. Your total cost for the products purchased will be displayed and application will end
    - For example, we purchased 2 headphones for $15/each and 1 lb of bananas for $0.89/each. Thus, total was $30.89

    ![bamazonTotalCost](images/bamazonCustomer2.png)

## bamazonManager Instructions

1. Run "node bamazonManager.js" on command line

2. Select from the available options:

    ![managerMainMenu](images/bamazonManager1.png)

    * View Products for Sale
        - You will see the list of products

        ![bamazonViewProducts](images/bamazonManager2.png)

        - You will then be prompted to return to the main menu or terminate application

    * View Low Inventory
        - You will see the list of products with stock of less than 5 units

        ![bamazonLowStock](images/bamazonManager3.png)

        - You will then be prompted to return to the main menu or terminate application
    
    * Add to Inventory
        - You will see the list of products for your convenience. Listed as ID#) ITEM | QUANTITY(#)
        - Select a product based on its ID
        - Enter the units you want to add
        
        ![bamazonAddStock](images/bamazonManager4.png)

        - You then have the option to continue adding stock or to return to the main menu

    * Add New Product
        - Enter product's name, department, price, and quantity

        ![bamazonAddProduct](images/bamazonManager5.png)

        - You can continue adding products if you like, return to the main menu, or terminate the application

      
