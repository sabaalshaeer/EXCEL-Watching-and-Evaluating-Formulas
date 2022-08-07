# EXCEL-Watching-and-Evaluating-Formulas
Add watches to several cells.
    Select Formulas→Watch Window.
    In the Watch Window dialog box, select Add Watch.
    In the Add Watch dialog box, in the Select the cells that you would like to watch the value of field, select cell F9 and select Add.
    Select Add Watch again, select the range C4:C9, and select Add.
    The cells you're watching are listed, along with their current values and underlying formulas.
Observe the changes to the Watch Window after deleting the Employee ID value from cell C3.
    Select cell C3 and press Delete.
    Observe that the Watch Window updates the values of the cells being watched.
    Note: Remember that the Watch Window can be moved, sized, and docked to any side of the screen you wish.
    Select cell C3, if necessary, and enter 1023
    Observe that the Watch Window updates the values of the cells being watched.
    Close the Watch Window.
Evaluate the formula in cell F9.
    Select cell F9 and select Formulas→Evaluate Formula.
    Cell C6 is underlined.
    You might recall that cell C6 contains the department of the employee who is being looked up.
    Select Evaluate to see the value of cell C6.
    Cell C6 is evaluated. In italic text, you can see that it contains the value Customer Service.
    Salary is now underlined. (You might recall that Salary is a range name.)
    Select Evaluate to see the value of Salary.
    The Salary range name is evaluated. In italic text, you can see that it refers to a range in the Pay Data worksheet.
    The entire AVERAGEIF portion of the formula is now underlined.
    Select Evaluate to see the value of the AVERAGEIF portion of the formula.
    In italic text, you can see that the AVERAGEIF portion of the formula produces a result of 50139.7777777778.
    The entire IFERROR formula is now underlined.
    Select Evaluate.
    In italic text, you can see the result produced by the entire formula.
    The Restart button is shown in case you want or need to restart the process of evaluating the formula.
    Select Restart.
    You are returned back to the top of the formula, with the C6 argument underlined.
Evaluate the formula in cell C6.
    In the Evaluate Formula dialog box, select Step In.
    Cell C6 is automatically selected in the worksheet.
    Two boxes are now shown in the Evaluation area. The top box shows the formula you were originally evaluating, with the C6 argument highlighted in blue.
    The bottom box shows the formula you stepped into—the formula for cell C6.
    In italic text, you can see the result produced by the entire formula.
    The Restart button is shown in case you want to restart the process of evaluating the formula.
    Select Evaluate three times, observing how you can proceed through an evaluation of the VLOOKUP function in cell C6.
    When you reach the end of the evaluation for cell C6, the Evaluate button is dimmed since there is nothing left to evaluate.
    Select Step Out.
    The second Evaluation box disappears, and you are returned back to the original formula. The Salary argument is now underlined, so you could step into that argument for deeper evaluation, if you wanted to.
    Select Close.

