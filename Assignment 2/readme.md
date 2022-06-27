Test on remix IDE-

Modifier isOwner - tested if the sender is the owner, then called the function function Object() { [native code] } - set the Owner to the sender; alternatively, tx might have been used.

origin pow - A convenience function for use with getCompounInterest. It is a pure function since it neither modifies nor examines the state variables. Similarly, getCompoundInterest is a pure function. reqloan is neither pure nor view because it modifies the loan mapping. getOwnerBalance- view function because it displays owner view balance Dues - examines loans, so the view function settleDues - modifies the loan, so neither view nor pure is valid.

I am attempting to create a contract function from the preceding assignment that returns the address to which the Owner owes the most money. There are numerous ways to accomplish this.

When someone uses the reqLoan function, I can change a global variable that stores the maximum address, and when the getMaxAddress method is called, I can simply display the maximum address value.

The other method is to loop through the mapping whenever the getMaxAdress function is invoked.

I have attempted to apply both of these.
