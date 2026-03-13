</h1> Algorithm to Swap the ages of two people </h1>
    
    BEGIN
        // Input names and ages
        INPUT name1
        INPUT age1
        INPUT name2
        INPUT age2
        
        // Swap the ages using a temporary variable
        temp = age1
        age1 = age2
        age2 = temp
        
        // Output the names with their (now swapped) ages
        OUTPUT name1 + " is " + age1
        OUTPUT name2 + " is " + age2
    END