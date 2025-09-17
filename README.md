# 🔗 Excel Logical Functions: AND & OR

The **AND** and **OR** functions in Excel are logical functions used to test multiple conditions at once.  
They are widely used in **decision-making, conditional formatting, and dynamic formulas**.

---

## 📌 AND Function & OR Function

=AND(condition1, condition2, …)
Returns TRUE if all conditions are TRUE

Returns FALSE if any condition is FALSE

`` 
**Example**

`` 
**AND**

=AND(5>3, 10<20)  → TRUE
=AND(5>3, 25<20)  → FALSE


`` 
**📌 OR Function**


=OR(condition1, condition2, …)
Returns TRUE if any condition is TRUE

Returns FALSE only if all conditions are FALSE

`` 
**Example**

`` 
**OR**

=OR(5>10, 15<20) → TRUE
=OR(5>10, 25<20) → FALSE

`` 
**🚀 Combining AND & OR with IF**

=IF(AND(A1>10, B1<20), "Pass", "Fail")
// Returns "Pass" if both conditions are TRUE
// Returns "Fail" if any condition is FALSE

=IF(OR(A1>10, B1<20), "Yes", "No")
// Returns "Yes" if any condition is TRUE
// Returns "No" if all conditions are FALSE
