Start
  |
  v
Initialize LoanManager
  |
  v
Load Data from File (if exists)
  |
  v
Show Menu
  |
  v
+--------------------------+
|     User Selects Action  |
+--------------------------+
  |
  v
+--------------------------+
|   1. Add Item           |
|   2. Add Borrower       |
|   3. Borrow Item        |
|   4. Return Item        |
|   5. Display Items      |
|   6. Display Borrowers   |
|   7. Display Loans       |
|   8. Exit               |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 1       |
|  Add Item               |
|    - Get ID & Name      |
|    - Add to daftar_barang |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 2       |
|  Add Borrower           |
|    - Get ID & Name      |
|    - Add to daftar_peminjam |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 3       |
|  Borrow Item            |
|    - Get Item ID & Borrower ID |
|    - Check Availability  |
|    - Update Status       |
|    - Record Loan         |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 4       |
|  Return Item            |
|    - Get Item ID        |
|    - Update Status       |
|    - Remove Loan Record  |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 5       |
|  Display Items          |
|    - Iterate through daftar_barang |
|    - Print Details       |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 6       |
|  Display Borrowers      |
|    - Iterate through daftar_peminjam |
|    - Print Details       |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 7       |
|  Display Loans          |
|    - Iterate through peminjaman |
|    - Print Loan Details  |
+--------------------------+
  |
  v
+--------------------------+
|     If Action = 8       |
|  Save Data to File      |
|  Exit Program           |
+--------------------------+
  |
  v
End


