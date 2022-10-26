# PatikaDev_BinarySearchTreeProjesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root=7

5<7 olduğu için 7'nin soluna eklenir.
             
                 7
              5
            
1<7 ve 1<5 dolayısıyla 5'in soluna eklenir.

             
                 7
              5
           1 

8>7 dolayısıyla 7'nin sağına eklenir.

                    7
               5         8
          1        
            

3<7 ve 3<5 ve 3>1 dolayısıyla 1'in sağına eklenir.

                    7
               5         8
          1        
            3

6<7 ve 6>5 dolayısıyla 5'in sağına eklenir.

                    7
              5         8
          1       6
            3

0<7 ve 0<5 ve 0<1 dolayısıyla 1'in soluna eklenir.

                    7
              5         8
          1      6
        0   3

9>7 ve 9>8 dolayısıyla 8'in sağına eklenir.

                    7
               5         8
          1       6         9
        0   3

4<7 ve 4<5 4>1 ve 4>3 dolayısıyla 3'ün sağına eklenir.

                    7
               5         8
          1       6         9
        0   3
              4

2<7 ve 2<5 ve 2>1 ve 2<3 dolayısıyla 3'ün soluna eklenir.

                    7
               5         8
          1       6         9
        0   3
           2  4


http://www.patika.dev/
