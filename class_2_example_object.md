**Dessert Class**  

  **Instance: Cheesecake**  

Attributes  

- cold: TRUE  
- calories: 480  
- chocolate: get.userInput {  
    "On a scale from 1-10, how covered in chocolate do you like your cheesecake?"  
    user<int1-10>  
  }  
- size: small  
- prepTime: 2:17pm  
- goes-withFish? FALSE  

Methods  

- whippedCream: get.userInput {boolean}, modify calories+200  
- cook: cold=FALSE returns str"Yikes! Who's gonna clean that up?"   
- makeBetter: chocolate+2 returns str"is that enough?"  
      get.userInput {boolean}  
        if TRUE, endLoop  
        if FALSE, next  
      until chocolate=10  
- smell: "This was prepared at 2:17pm, are you sure you want to eat it?"  
- getDrunk: goes-withFish?=True, "You know what would taste great with this?"
