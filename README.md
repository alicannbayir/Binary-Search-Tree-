**BINARY SEARCH TREE**

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları;

let 6 be root

6<7. bu yüzden 7 rootun sağına yazılır.

6>5. bu yüzden 5 rootun soluna yazılır

       6
     /   \
    5     7
    
6>1. bu yüzden 1 rootun soluna yazılır. Sonra 5>1 olduğu için 1 yine 5'in soluna yazılır
   
6<8. Bu yüzden 8 rootun sağında yer alır. Sonra 7<8 olduğu için 8,7'nin sağına yazılır. 
    
             6
            / \
           5   7
          /     \
         1       8
 6>3, 5>3 ve 1<3 olduğu için 3, 1'in sağına yazılır. Aynı şekilde 6>0, 5>0 ve 1>0 olduğu için 0 da 1'in soluna yazılır.
 
             6
            / \
           5   7
          /     \
         1       8
        / \
       0   3
       
  6<9, 7<9 ve 8<9 olduğu için 9 rootun sağına sonra 7'nin sağına ve en son da 8'in sağına yazılır
  
             6
            / \
           5   7
          /     \
         1       8
        / \       \
       0   3       9
       
   6>4, 5>4. Bu yüzden 4 root ve 5'in soluna yazılır. Daha sonra 1<4 olduğu sağına ve 3<4 oluğundan dolayı da onun sağına yaılır.
   
             6
            / \
           5   7
          /     \
         1       8
        / \       \
       0   3       9
            \
             4
             
   6>2, 5>2. Bu yüzden 6 ve 5'in soluna yazılır. Daha sonra 1<2, 3>2 olduğu için 3'ün soluna yazılır
   
             6
            / \
           5   7
          /     \
         1       8
        / \       \
       0   3       9
          / \
         2   4
