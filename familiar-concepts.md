# Familiar Concepts

Let us discuss the familair concepts between R and spreadsheets.

I am going to use the VLookup function in MS Excel to complete a cross walk of similiar concepts with R

**Functions: **A function is a pre-built programmed operation to help you do something useful.

Our function set up in a Spreadsheet



```
=vlookup(Arguments...)

```

The start of a similiar function in R

```R
join(Arguments....)
```

**Arguments:** The arguments help the function know more about what you expect to be returned. They are like parameters.

The Vlookup functions has many arguments that can help us cross walk similair concepts with programming.

**Lookup Value:This is the match between the two tabs in the workbook**

```
=vlookup(D2, Table_Array, Col_index_num )
=vlookup("text"....)
```

Understanding Lookup values; is the concept of understanding the common links between the two data sets. Most likely, you need the lookup value to uniquely identify a person or thing.



```
join(df_1, df_2, by="student_code")
```

This 

**Table\_Array:This is your reference sheet from where the data should be pulled.**

Selecting the relevant data that you want to extract and making this a variable object.

**Col\_index\_num:This references the column from which you want to extract data. **

Understanding how to use indexes is useful with understanding coding.

**Range Lookup:This is asking if you want an exact match or an approximate match. It requires “true” or “false”: true provides an approximate match, false provides an exact match. **

The True or FALSE Operator **          
**

**          
**

