The Three Broomsticks (bar)  

Attributes:  

is_open: true  
bar_booze_inventory: {"Butterbeer": 50, "Daisyroot_draught": 15}  
bar_staff = ["Madam Rosemerta", "Severus Snape"]  
num_bartenders_clocked_in: 1  

Methods:  

open: modifies is_open to true  
close: modifies is_open to false  
restock_booze: increases "Butterbeer" and "Daisyroot_draught" stock in bar_booze_inventory  
hire_bartender: adds "Neville" "Longbottom" to bar_staff  
bartender_clock_in: modifies num_bartenders_clocked_in to 2  
