**Condiment Class**  

  **Instance: Syrup**  

Attributes  

    - flavor: "sweet"
    - bottleSize: 16fl.oz.  
    - expireDate: Jan. 2008  
    - currentContents: 12.28fl.oz.  
    - goes-withFish?: FALSE  

Methods  

- squeeze: currentContents - squeezeMagnitude<int 1-10> (  
      get.userInput {"How hard do you want to squeeze, from 1-10?"})  
- cut: bottleSize*.5 {returns str "This sticky cup can only hold 8fl.oz"}  
- waterDown: flavorType=bland  
- tamper: expireDate="Jan. 2088"  
- getDrunk: goes-withFish?=TRUE  
