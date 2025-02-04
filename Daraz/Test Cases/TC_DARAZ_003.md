# Test Case: Add to Cart Functionality  

## Test Case ID: TC_DARAZ_003  

### **Precondition:**  
1. User should have a user account and be logged in.  
2. User should be on a product detail page.  

### **Test Steps:**  
1. Navigate to [daraz.com.bd](https://www.daraz.com.bd).  
2. Search for a product named **M19 TWS**.  
3. Click on the product with the **most sold value**.  
4. Click the **"Add to Cart"** button.  
5. Close the **"Added to Cart"** confirmation message.  
6. Verify the cart icon updates and shows the correct number of items.  
7. Click on the cart icon.  
8. Verify the selected product is listed in the cart with the correct details (**name, price, quantity**).  

### **Expected Result:**  
1. The product should be successfully added to the cart.  
2. The cart should display the correct product and updated quantity.  

### **Postcondition:**  
1. The cart is updated and ready for checkout.  

### **Test Data:**  
- **Product Name:** M19 TWS Wireless Bluetooth 5.1 Earbuds - Featuring Touch Control  
- **Qty:** 1  
- **Expected Price:** 315  

### **Test Result:** ✅ Pass  
