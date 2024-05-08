MasterFlexi Indtype2 = 
    FILTER (
        SUMMARIZECOLUMNS(
            //'Fixed_YYYYMMDD (Fixed_Creator)'[File Created Date],
            'Fixed_YYYYMMDD (Fixed_Creator)'[CustomerId],
            'Fixed_YYYYMMDD (Fixed_Creator)'[CustomerName]
        ),
        NOT CONTAINSSTRING('Fixed_YYYYMMDD (Fixed_Creator)'[CustomerId],"0")
    )
