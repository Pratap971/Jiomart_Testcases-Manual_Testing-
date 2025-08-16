# Jiomart_Testcases-Manual_Testing-

# Jiomart_Test_Case.xlsx:  

- Contains 10 test cases for scenarios including:  

- Valid/invalid product search  
- Adding/removing items from cart  
- Price calculations  
- Special character search  
- Large quantity additions  
- Edge cases (e.g., trailing spaces)  


- Most tests passed, but TC-007 failed:  

- Attempted to add 50 units of oil
Only 5 added silently due to unnotified limit




# BugReport_jiomart.xlsx:

- Lists 5 bugs identified during testing:  

- Invalid search ("@#$") shows wrong results (e.g., watches)  
- Quantity limit exceeded (e.g., 50 units of Fortune Oil) without warning (only 4 added)  
- "Half Price Store" section appears blank  
- "Brand of the Day" section shows no products  
- Dry Fruits category page loads but displays no products  


- All bugs are new with high/medium severity  
- Tested on Chrome v138 (laptop)
- Includes screenshot links for evidence  
