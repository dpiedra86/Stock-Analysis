# Stock-Analysis
Bootcamp 2nd challenge

 ## Overview 

The purpose of this project was to refactor the code we previously did in Module 2. 
Simplify tasks and processing time by reducing the number of steps to get the same result.
A lot of research had to be done in order to complete this challenge. 

 # Results: 

- The array is the backnbone of the challenge. We can even print it to the worksheet without any conditionals. 
- Declaring each variable in the array is a manual task. If the case is that we have to loop over a considerable amount of values, it would be a good idea to loop over the dataset and obtain each variable with code. Even when we have to hard-code them later it would save us some time. 

    '1b) Create three output arrays
    
        Dim tickerVolumes(12) As Long
        Dim tickerStartingPrices(12) As Double
        Dim tickerEndingPrices(12) As Double
    
Once the array is declared, array outputs let us loop throught the array as different objects and store information foreach var in the index array depending on the opreations we assign to each output. 
By adding +1 to the tickerindex at the end of the loop, the code moves fwd one value through the array. 

Execution time was reduced.

![2017](https://github.com/dpiedra86/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png)

![2018](https://github.com/dpiedra86/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)


# Summary

Refactoring the code helps us to make it more efficient and easier to read. The main objective is to use the processing power of the machines
to make repetitive tasks. Then simplify this tasks by reducing the number of steps to get the same result. 

Pros : Refactoring the code has its benefits. we will have a more concise set of isnturctions, this will traduce in a more efficient and easy to read code. 

Cons: Even when the code gets simplier, some insturctiones may imply knowledge of more advanced methods; this may complicate the undersatanding of each lien,  if the code is not clearly quoted for a not so experienced programmer. 







