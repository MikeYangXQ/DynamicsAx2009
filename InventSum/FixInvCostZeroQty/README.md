This class fix problem if you have 0 qty on InventSum, but cost != 0
Used invent journal Move, received qty then issue qty and closed InventTrans for this batch or another inventDim.

Before mandatory check InventSum in standart function Consistency check in Main module!