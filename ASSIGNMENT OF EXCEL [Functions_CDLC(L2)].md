What is a function in Excel?

'''
A function in Excel is a pre-built formula with a specific purpose. Excel provides hundreds of functions in various categories like dates and times, text, statistics, lookup, financial, engineering, etc. Most Excel functions require specific inputs, called function arguments.

Once we are familiar with the function we want to use, all we have to do is enter an equal sign (=) in the cell, followed by the name of the function and the cell range it applies to.
For example, the SUM function is used to add the values in cells.
We would use it like this: =SUM(A1:A5), which would add up the values in cells A1 through A5.

'''

How do you start a function in Excel?

'''
To start a function in Excel, follow these steps:

Click on the cell where you want the result of the function to appear.
Type an equals sign (=) to tell Excel that you’re about to enter a function.
Type the name of the function you want to use. For example, if you want to add numbers, you would type SUM.
After the function name, type an opening parenthesis (.
Now, you’ll need to add the arguments for the function. These are the values that the function will use to calculate the result. For example, if you’re using the SUM function to add up numbers in cells A1 through A5, your arguments would be A1:A5.
After typing your arguments, close the parenthesis ).
Press Enter to complete the function.
The completed function will look something like this: =SUM(A1:A5). This tells Excel to add up the values in cells A1 through A5 and display the result in the cell where you entered the function.

'''

What is the purpose of using functions in Excel?

'''
Functions in Excel are used for a variety of purposes, including:

Simplifying complex calculations: Functions can perform complex calculations that would be time-consuming to do manually. For example, the SUM function can add up a series of numbers in a range of cells with a single formula.

Automating repetitive tasks: If you find yourself performing the same calculation on different sets of data, you can use a function to automate this process. For example, you could use the AVERAGE function to find the average of a range of cells.

Improving accuracy: By using functions, you reduce the chance of errors that can occur when entering complex formulas or calculations manually.

Analyzing and interpreting data: Excel provides a wide range of statistical functions that can help you analyze and interpret your data. For example, you could use the COUNTIF function to count the number of cells in a range that meet a certain condition.

Extracting and manipulating data: Some functions are designed to work with text strings, dates, and times, allowing you to extract and manipulate data in useful ways.

In summary, Excel functions are powerful tools that can save you time, improve your efficiency, and help you gain insights from your data.

'''

What is the difference between a function and a formula in Excel?

'''
In Excel, a formula is an expression that you create inside a cell to perform calculations or tasks. It starts with an equal sign (=) and can include cell references, operators, numbers, etc. For example, =1+2 and =A1+D3 are formulas.

A function, on the other hand, is a pre-defined formula already available in Excel. Functions are built into Excel and allow you to perform specific calculations or tasks without needing to know operators or programming languages. For example, SUM, COUNT, AVERAGE, TRUNC, and TRIM are all functions.

The key difference between a function and a formula in Excel is that you can insert a function into a formula that you create. While a cell in Excel can only have one formula, the formula itself can consist of multiple functions. For instance, =SUM(A1:A10) + AVERAGE(A1:A10) is a formula that uses two functions (SUM and AVERAGE)

'''

How can you enter a function manually in a cell?

'''
To manually enter a function in an Excel cell, follow these steps:

Select the cell where you want the result of the function to appear.

Type an equals sign (=) to tell Excel that you’re about to enter a function.

Type the name of the function you want to use. For example, if you want to add numbers, you would type SUM.

After the function name, type an opening parenthesis (.

Now, you’ll need to add the arguments for the function. These are the values that the function will use to calculate the result.
For example, if you’re using the SUM function to add up numbers in cells A1 through A5, your arguments would be A1:A5.

After typing your arguments, close the parenthesis ).

Press Enter to complete the function.

The completed function will look something like this:
=SUM(A1:A5)

This tells Excel to add up the values in cells A1 through A5 and display the result in the cell where you entered the function.

'''

What is the SUM function used for in Excel?

'''
The SUM function in Excel is used to add up a series of numbers. It’s one of the most commonly used functions in Excel and is very helpful for performing financial calculations, statistical analysis, or managing data.

Here’s how you can use it:

Select the cell where you want the result to appear.
Type an equals sign (=) followed by SUM.
Open a parenthesis (.
Enter the range of cells you want to sum up. For example, if you want to add the numbers in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =SUM(A1:A5). This tells Excel to add up the values in cells A1 through A5 and display the result in the cell where you entered the function.

'''

How do you use the SUM function to add a range of numbers?

'''
To use the SUM function to add a range of numbers in Excel, follow these steps:

Select the cell where you want the sum to appear.
Type an equals sign (=) to start the formula.
Type SUM followed by an opening parenthesis (.
Enter the range of cells you want to sum up. For example, if you want to add the numbers in cells A1 through A5, you would type A1:A5.
Type a closing parenthesis ).
Press Enter.
The completed function will look like this: =SUM(A1:A5). This tells Excel to add up the values in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also sum multiple ranges by separating them with commas inside the parentheses. For example, =SUM(A1:A5, C1:C5) would sum the values in both ranges A1 through A5 and C1 through C5.

'''

Explain the function of the AVERAGE function in Excel.

'''
The AVERAGE function in Excel calculates the average (arithmetic mean) of a set of numbers. It’s very useful when you need to find the central tendency of a data set.

Here’s how you can use it:

Select the cell where you want the average to appear.
Type an equals sign (=) followed by AVERAGE.
Open a parenthesis (.
Enter the range of cells you want to average. For example, if you want to find the average of the numbers in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =AVERAGE(A1:A5).
This tells Excel to calculate the average of the values in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also average multiple ranges by separating them with commas inside the parentheses. For example, =AVERAGE(A1:A5, C1:C5) would calculate the average of the values in both ranges A1 through A5 and C1 through C5.

'''

How do you find the highest value in a range of cells using a function?

'''
To find the highest value in a range of cells in Excel, you can use the MAX function. Here’s how:

Select the cell where you want the maximum value to appear.
Type an equals sign (=) followed by MAX.
Open a parenthesis (.
Enter the range of cells you want to find the maximum value of. For example, if you want to find the maximum value in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =MAX(A1:A5). This tells Excel to find the maximum value in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also find the maximum value across multiple ranges by separating them with commas inside the parentheses. For example, =MAX(A1:A5, C1:C5) would find the maximum value across both ranges A1 through A5 and C1 through C5.

'''

What function can you use to find the lowest value in a range of cells?

'''
To find the lowest value in a range of cells in Excel, you can use the MIN function. Here’s how:

Select the cell where you want the minimum value to appear.
Type an equals sign (=) followed by MIN.
Open a parenthesis (.
Enter the range of cells you want to find the minimum value of. For example, if you want to find the minimum value in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =MIN(A1:A5). This tells Excel to find the minimum value in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also find the minimum value across multiple ranges by separating them with commas inside the parentheses. For example, =MIN(A1:A5, C1:C5) would find the minimum value across both ranges A1 through A5 and C1 through C5.

'''

How do you use the COUNT function to count the number of cells in a range that contain numbers?

'''
To use the COUNT function to count the number of cells in a range that contain numbers, follow these steps:

Select the cell where you want the count to appear.
Type an equals sign (=) followed by COUNT.
Open a parenthesis (.
Enter the range of cells you want to count. For example, if you want to count the number of cells that contain numbers in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =COUNT(A1:A5). This tells Excel to count the number of cells in the range A1 through A5 that contain numbers and display the result in the cell where you entered the function.

Remember, you can also count across multiple ranges by separating them with commas inside the parentheses. For example, =COUNT(A1:A5, C1:C5) would count the number of cells that contain numbers across both ranges A1 through A5 and C1 through C5.

'''

What does the MAX function do, and how do you use it?

'''
The MAX function in Excel is used to find the highest (maximum) number in a given set of values or range of cells. It’s very useful when you need to identify the largest number in a dataset.

Here’s how you can use it:

Select the cell where you want the maximum value to appear.
Type an equals sign (=) followed by MAX.
Open a parenthesis (.
Enter the range of cells you want to find the maximum value of. For example, if you want to find the maximum value in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =MAX(A1:A5). This tells Excel to find the maximum value in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also find the maximum value across multiple ranges by separating them with commas inside the parentheses. For example, =MAX(A1:A5, C1:C5) would find the maximum value across both ranges A1 through A5 and C1 through C5.

'''

What is the purpose of the MIN function in Excel?

'''
The MIN function in Excel is used to find the smallest (minimum) number in a given set of values or range of cells. It’s very useful when you need to identify the smallest number in a dataset.

Here’s how you can use it:

Select the cell where you want the minimum value to appear.
Type an equals sign (=) followed by MIN.
Open a parenthesis (.
Enter the range of cells you want to find the minimum value of. For example, if you want to find the minimum value in cells A1 through A5, you would type A1:A5.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =MIN(A1:A5). This tells Excel to find the minimum value in cells A1 through A5 and display the result in the cell where you entered the function.

Remember, you can also find the minimum value across multiple ranges by separating them with commas inside the parentheses. For example, =MIN(A1:A5, C1:C5) would find the minimum value across both ranges A1 through A5 and C1 through C5.

'''

How can you use the IF function to create a simple logical test?

'''
The IF function in Excel is used to create a logical test and return different values based on whether the test is TRUE or FALSE. The syntax for the IF function is =IF(logical_test, value_if_true, value_if_false).

Here’s how you can use it:

Select the cell where you want the result to appear.
Type an equals sign (=) followed by IF.
Open a parenthesis (.
Enter the logical test. This is a condition that can be either TRUE or FALSE. For example, if you want to check if the value in cell A1 is greater than 10, you would type A1>10.
Type a comma , to separate the arguments.
Enter the value that should be returned if the logical test is true. This could be a number, text, or another formula.
Type another comma , to separate the arguments.
Enter the value that should be returned if the logical test is false.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =IF(A1>10, "Yes", "No"). This tells Excel to check if the value in cell A1 is greater than 10. If it is, Excel will return “Yes”. If it’s not, Excel will return “No”.

'''

What does the CONCATENATE function do, and how is it used?

'''
The CONCATENATE function in Excel is used to join different pieces of text together or combine values from several cells into one cell. It can join up to 30 values together and returns the result as text.

The syntax of the CONCATENATE function is as follows: =CONCATENATE(text1, [text2], …), where text1, text2, etc. are the text strings, numbers, or cell references that you want to join together. Only the first argument is required, and values are concatenated in the order they appear.

For example, to concatenate the value of A1 and B1, separated by a space, you can use CONCATENATE like this: =CONCATENATE(A1," ",B1). The result of this formula is the same as using the concatenation operator (&) manually like this: =A1 & " " & B1.

In Excel 2019 and later, the CONCAT function and TEXTJOIN function are better, more flexible alternatives. The CONCAT function can also join a range of strings. If you don’t need a delimiter (space, comma, dash, etc.), this can be useful.

The TEXTJOIN function in Excel 2016 or later joins a range of strings using a delimiter (first argument). The beauty of the TEXTJOIN function is that it can ignore empty cells (if the second argument is set to TRUE).

'''

Explain the function of the LEFT function in Excel.

'''
The LEFT function in Excel is used to extract a specified number of characters from the beginning (left) of a text string1. The syntax of the LEFT function is =LEFT(text, [num_chars]), where:

text is the text string from which we fetch the characters.
num_chars is an optional argument that indicates the number of characters you want LEFT to extract. If num_chars is omitted, it is assumed to be 1.
For example, if you have the word “Excel” in cell A1 and you want to extract the first two characters, you would use: =LEFT(A1, 2). This would return "Ex".

Please note that the LEFT function in Excel should be used for extracting characters starting from the left side of the text. Also, LEFT in Excel will extract digits from numbers as well. Number formatting (i.e., the currency symbol $) is not part of a number. Therefore these are not counted or extracted by the Excel LEFT Function.

'''

How do you use the RIGHT function to extract characters from a text string?

'''
The RIGHT function in Excel is used to extract a specified number of characters from the end (right side) of a given text string. Here’s how you can use it:

Select the cell where you want the result to appear.
Type an equals sign (=) followed by RIGHT.
Open a parenthesis (.
Enter the text string from which you want to extract characters. This could be a string enclosed in quotation marks (like “Hello”) or a cell reference (like A1).
Type a comma , to separate the arguments.
Enter the number of characters you want to extract from the right side of the text string.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =RIGHT(A1, 3). This tells Excel to extract the last three characters from the text in cell A1 and display the result in the cell where you entered the function.

Please note that if you do not specify the number of characters to extract, it will take 1 as default. Also, if the number of characters specified is greater than the length of the text, RIGHT returns all of the text.

'''

What is the purpose of the LEN function, and how do you use it?

'''
The LEN function in Excel is used to calculate the length of a given text string. It counts the number of characters in the text, including alphabets, numbers, special characters, non-printable characters, and all spaces.

Here’s how you can use it:

Select the cell where you want the length to appear.
Type an equals sign (=) followed by LEN.
Open a parenthesis (.
Enter the text string from which you want to calculate the length. This could be a string enclosed in quotation marks (like “Hello”) or a cell reference (like A1).
Close the parenthesis ).
Press Enter.
The completed function will look like this: =LEN(A1). This tells Excel to calculate the length of the text in cell A1 and display the result in the cell where you entered the function.

Please note that if the text is an empty string (“ ”) or a reference to an empty cell, LEN returns zero. Also, LEN will count characters in numbers, but number formatting is not included.

'''

How can you use the VLOOKUP function to search for data in a table?

'''
The VLOOKUP function in Excel is used to find things in a table or a range by row1. It’s very useful when you need to look up a value in a table based on some reference information. Here’s how you can use it:

Select the cell where you want the result to appear.
Type an equals sign (=) followed by VLOOKUP.
Open a parenthesis (.
Enter the lookup value. This is the value you want to find in the first column of your table.
Type a comma , to separate the arguments.
Enter the table array. This is the range of cells that contains the data you want to search.
Type another comma , to separate the arguments.
Enter the column index number. This is the number of the column in your table that contains the return value.
Type another comma , to separate the arguments.
Specify whether you want an approximate or exact match. Enter TRUE for an approximate match or FALSE for an exact match.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup]). This tells Excel to find the lookup_value in the first column of table_array. If it finds it, it returns the value in the same row from the column specified by col_index_num. If not, it returns an error.

Remember, if your lookup value is not in the first column of your table array or if your column index number is less than 1, VLOOKUP will return an error. Also, if range_lookup is TRUE or omitted, your first column should be sorted in ascending order.

'''

What does the HLOOKUP function do, and when is it used?

'''
The HLOOKUP function in Excel performs a horizontal search across a sorted data table to find a match with the lookup value. It searches across the topmost row for the look-up value and then moves down to retrieve data from the specified row. In HLOOKUP, the H stands for Horizontal, which we use when the lookup table is arranged horizontally.

The syntax of the HLOOKUP function is =HLOOKUP (lookup_value, table_array, row_index_num, [range_lookup]), where:

lookup_value is the value to be found in the first row of the table.
table_array is a table of information in which data is looked up.
row_index_num is the row number in table_array from which the matching value will be returned.
range_lookup is a logical value that specifies whether you want HLOOKUP to find an exact match or an approximate match.
You would use HLOOKUP when your comparison values are located in a row across the top of a table of data, and you want to look down a specified number of rows. Use VLOOKUP when your comparison values are located in a column to the left of the data you want to find.

Please note that if your lookup value is not in the first row of your table array or if your row index number is less than 1, HLOOKUP will return an error. Also, if range_lookup is TRUE or omitted, your first row should be sorted in ascending order.

'''

Explain the function of the DATE function in Excel.

'''
The DATE function in Excel is used to create a valid date from individual year, month, and day components. The syntax of the DATE function is =DATE(year, month, day), where:

year is the number for the year.
month is the number for the month.
day is the number for the day.
The DATE function is useful for assembling dates that need to change dynamically based on other values in a worksheet. For example, with 2018 in cell A1, the formula below returns the date April 15, 2018: =DATE(A1,4,15). If A1 is then changed to 2019, the DATE function will return a date for April 15, 2019.

Please note that the DATE function actually returns a serial number and not a formatted date. In Excel’s date system, dates are serial numbers. January 1, 1900 is number 1 and later dates are larger numbers. To display date values in a human-readable date format, apply the number format of your choice.

'''

How do you use the NOW function to display the current date and time?

'''
The NOW function in Excel is used to display the current system date and time. It’s a volatile function, which means it updates every time when a recalculation is done. Here’s how you can use it:

Select the cell where you want the current date and time to appear.
Type an equals sign (=) followed by NOW.
Open and close a parenthesis (). The NOW function does not take any arguments.
Press Enter.
The completed function will look like this: =NOW(). This tells Excel to display the current system date and time in the cell where you entered the function.

Please note that when you enter the NOW function in a cell, it will convert the format of the cell into a custom format (m/d/yyyy h:mm). The date and time will be updated whenever the worksheet is recalculated or opened. If you want to enter a static current date & time, you can use keyboard shortcut key CTRL + SHIFT + : (Current Time) & CTRL + : (Current Date) to enter current.

'''

What is the purpose of the TEXT function in Excel?

'''
The TEXT function in Excel is used to convert numbers to text within a spreadsheet. Essentially, the function will convert a numeric value into a text string. The syntax of the TEXT function is =TEXT(value, format_text), where:

value is the numeric value or cell reference to the numeric value we require to convert into a text string.
format_text is the format we want to apply.
The TEXT function is useful in situations where you want to display numbers in a more readable format, or you want to combine numbers with text or symbols. It’s also useful when concatenating a formatted number to a text string. For example, “Sales last year increased by over $43,500”, where the number 43500 has been formatted with a currency symbol and thousands separator.

Please note that although you can use the TEXT function to change formatting, it’s not the only way. You can change the format without a formula by pressing CTRL+1 (or +1 on the Mac), then pick the format you want from the Format Cells > Number dialog.

'''

How do you use the SUMIF function to sum values based on a condition?

'''
The SUMIF function in Excel is used to sum the values in a range that meet criteria that you specify. The syntax of the SUMIF function is =SUMIF(range, criteria, [sum_range]), where:

range is the range of cells that you want evaluated by criteria.
criteria is the criteria in the form of a number, expression, a cell reference, text, or a function that defines which cells will be added.
sum_range is optional. It’s the actual cells to add, if you want to add cells other than those specified in the range argument.
For example, suppose that in a column that contains numbers, you want to sum only the values that are larger than 5. You can use the following formula: =SUMIF(B2:B25, ">5").

If you want to apply the criteria to one range and sum the corresponding values in a different range. For example, the formula =SUMIF(B2:B5, "John", C2:C5) sums only the values in the range C2:C5, where the corresponding cells in the range B2:B5 equal "John".

To sum cells based on multiple criteria, see SUMIFS function.

'''

What is the COUNTIF function, and when is it used?

'''
The COUNTIF function in Excel is used to count the number of cells in a range that meet a specific criterion. The syntax of the COUNTIF function is =COUNTIF(range, criteria), where:

range is the range of cells that you want evaluated by the criterion.
criteria is the condition that defines which cells will be counted.
For example, to count the number of cells with “apples” in cells A2 through A5, you would use: =COUNTIF(A2:A5,"apples"). This would return the number of cells in the range A2:A5 that contain the word "apples".

The COUNTIF function is used when you need to count cells that meet a certain condition. It can be used to count cells that contain specific text, dates, numbers, and more. For example, you can use COUNTIF to count the number of cells that contain a specific city name in a customer list.

'''

Explain the function of the AVERAGEIF function in Excel.

'''
The AVERAGEIF function in Excel calculates the average (arithmetic mean) of all the cells in a range that meet a given criteria. The syntax of the AVERAGEIF function is =AVERAGEIF(range, criteria, [average_range]), where:

range is one or more cells to average, including numbers or names, arrays, or references that contain numbers.
criteria is the criteria in the form of a number, expression, cell reference, or text that defines which cells are averaged. For example, criteria can be expressed as 32, “32”, “>32”, “apples”, or B4.
average_range is optional. It’s the actual set of cells to average. If omitted, range is used.
For example, if you have a range of numbers in cells A1 through A5 and you want to calculate the average of numbers that are greater than 5, you would use: =AVERAGEIF(A1:A5, ">5").

Please note that if no cells in the range meet the criteria, AVERAGEIF returns the #DIV/0! error value. You can use the wildcard characters, question mark (?) and asterisk (*), in criteria. A question mark matches any single character; an asterisk matches any sequence of characters. If you want to find an actual question mark or asterisk, type a tilde (~) before the character.

'''

How can you use the IFERROR function to handle errors in Excel?

'''
The IFERROR function in Excel is used to handle errors that might arise when a formula is evaluated. It returns a specified value if a formula evaluates to an error; otherwise, it returns the result of the formula.

The syntax of the IFERROR function is =IFERROR(value, value_if_error), where:

value is the argument that is checked for an error. It can be a value, expression, formula, or cell reference.
value_if_error is the value to return if the formula evaluates to an error. This could be a number, text, or another formula.
For example, if you have a formula that divides two numbers in cells A2 and B2 (like =A2/B2), but there’s a possibility that B2 could be zero (which would cause a divide by zero error), you can use IFERROR to handle this. The formula would look like this: =IFERROR(A2/B2, "Error in calculation"). If B2 is not zero, this formula will return the result of the division. If B2 is zero, it will return “Error in calculation” instead.

The IFERROR function can handle many types of errors like #NUM!, #VALUE!, #REF!, #DIV/0!, #NAME?, and #NULL.

'''

What is the purpose of the ROUND function, and how do you use it?

'''
The ROUND function in Excel is used to round a number to a specified number of digits. The syntax of the ROUND function is =ROUND(number, num_digits), where:

number is the number that you want to round.
num_digits is the number of digits to which you want to round the number argument.
For example, if cell A1 contains 23.7825, and you want to round that value to two decimal places, you can use the following formula: =ROUND(A1, 2). The result of this function is 23.78.

Please note that if num_digits is greater than 0 (zero), then the number is rounded to the specified number of decimal places. If num_digits is 0, the number is rounded to the nearest integer. If num_digits is less than 0, the number is rounded to the left of the decimal point.

'''

How do you use the CONCATENATE function to join text from multiple cells?

'''
The CONCATENATE function in Excel is used to join two or more text strings into one text string. Here’s how you can use it:

Select the cell where you want the combined text to appear.
Type an equals sign (=) followed by CONCATENATE.
Open a parenthesis (.
Enter the references to the cells that contain the text you want to combine. You can also type the text directly into the formula, enclosed in quotation marks.
Separate each cell reference or piece of text with a comma ,.
Close the parenthesis ).
Press Enter.
The completed function will look like this: =CONCATENATE(A1, " ", B1). This tells Excel to combine the text in cells A1 and B1, with a space (" ") in between.

Please note that as of Excel 2016, the CONCATENATE function has been replaced with the CONCAT function. Although CONCATENATE is still available for backward compatibility, it’s recommended to use CONCAT instead.

'''

What is the difference between the AND and OR functions in Excel?

'''
The AND and OR functions in Excel are both logical functions that return TRUE or FALSE based on the conditions you specify.

The AND function returns TRUE if all its arguments evaluate to TRUE, and returns FALSE if one or more arguments evaluate to FALSE. For example, if you have a formula like =AND(A1>10, B1<5), it will return TRUE only if both conditions (A1 is greater than 10 and B1 is less than 5) are true.

On the other hand, the OR function returns TRUE if any of its arguments evaluate to TRUE, and returns FALSE only if all supplied arguments evaluate to FALSE. For example, if you have a formula like =OR(A1>10, B1<5), it will return TRUE if either condition (A1 is greater than 10 or B1 is less than 5) is true.

In summary, use the AND function when you want all conditions to be true, and use the OR function when you want at least one condition to be true.

'''