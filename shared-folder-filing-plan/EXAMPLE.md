# Shared folder filing plan: an invented example

*Illustrative example with invented data.* Fennimore Yard Joinery is an invented 38-person maker of staircases and fitted joinery. Its people, customers, suppliers, files and dates are invented too. Priya, the office manager, is tidying the shared drive's top folder, called Shared. On Tuesday 10 November 2026 she gives the assistant everything below, in full, and gets back the filing plan that follows.

## What Priya supplied

### 1. Settings

```
Folder being tidied: Shared
Today: Tuesday 10 November 2026
Coordinator: Priya (office manager)
Batch size: default
```

### 2. Folder inventory (exported from the drive)

```
path,name,size_kb,modified,owner,shared_with,link_shared
Shared/Misc,2026 insurance schedule.pdf,412,2026-03-14,Priya,Directors; Office,no
Shared/Misc,Supplier terms - Supplier A.pdf,230,2025-06-02,Priya,Office,no
Shared/Misc,Supplier terms - Supplier B.pdf,198,2024-02-20,Priya,Office,no
Shared/Invoices 2025,Invoice 0412 Customer C.pdf,88,2025-04-09,Grace,Finance; Office,no
Shared/Invoices 2025,Invoice 0413 Customer D.pdf,91,2025-04-16,Grace,Finance,no
Shared/Payroll,Payslip run Oct 2026.xlsx,156,2026-10-30,Grace,Finance,no
Shared/Misc,Risk assessment - saw room.docx,74,2026-01-22,Hamid,All staff,no
Shared/Misc,Method statement - roof repair.docx,66,2026-05-30,Hamid,All staff,no
Shared/Projects,Work order 2611 Customer E.xlsx,120,2026-11-02,Wen,Projects; Office,no
Shared/Projects,Work order 2612 Customer F.xlsx,118,2026-11-05,,Projects; Office,yes
Shared/Misc,Supplier terms - Supplier A.pdf,230,2025-06-02,Ola,Office,no
Shared/Old,Staff handbook 2022.pdf,1840,2022-09-01,Priya,All staff,no
Shared/Misc,Away day photos.zip,5200,2026-09-18,Keren,All staff,no
Shared/Misc,,12,2026-08-01,Wen,Office,no
Shared/Misc,Risk assessment - office.docx,45,2026-02-11,Hamid,All staff,no
Shared/Old,Risk assessment - office.docx,52,2025-02-09,Hamid,All staff,no
Shared/02 Finance/Invoices,Invoice 0410 Customer C.pdf,85,2025-03-12,Grace,Finance,no
```

### 3. Filing conventions

```
Filing conventions: Fennimore Yard Joinery, approved by Tobias (finance director), 2 March 2026

Destination folders, each with who may see it:
1. Shared/01 Admin/Insurance. Audience: Directors; Office
2. Shared/01 Admin/Suppliers. Audience: Office
3. Shared/02 Finance/Invoices. Audience: Finance
4. Shared/02 Finance/Payroll. Audience: Finance
5. Shared/03 Projects/Active. Audience: Projects; Office
6. Shared/04 Health and Safety. Audience: All staff
7. Shared/05 Archive. Audience: Office

Filing rules (the first rule that matches decides):
R1. Path begins "Shared/Payroll" or name contains "payslip": Shared/02 Finance/Payroll
R2. Name contains "invoice": Shared/02 Finance/Invoices
R3. Name contains "insurance": Shared/01 Admin/Insurance
R4. Name contains "supplier": Shared/01 Admin/Suppliers
R5. Name contains "risk assessment" or "method statement": Shared/04 Health and Safety
R6. Name starts with "Work order": Shared/03 Projects/Active
R7. Modified more than 24 months before today: Shared/05 Archive

Restricted records:
- Payroll records: anything filed in Shared/02 Finance/Payroll. Holder: Tobias (finance director), who confirms before it moves.
```

## What came back

```
FILING PLAN: Shared, prepared Tuesday 10 November 2026
For: Priya (office manager). The coordinator approves this plan first; each owner approves the moves of their own documents.
Prepared from 17 inventory rows, 7 filing rules and 7 destination folders. Nothing has been moved, renamed, deleted or re-shared.
Rows 17 = to move 10 + stay 1 + in duplicate groups 4 + not planned 2.
Moves: 6 ready for owner approval, 4 held.

Proposed folder structure
Shared/01 Admin/Insurance (1 file: 1 to move, 0 already there)
Shared/01 Admin/Suppliers (1 file: 1 to move, 0 already there)
Shared/02 Finance/Invoices (3 files: 2 to move, 1 already there)
Shared/02 Finance/Payroll (1 file: 1 to move, 0 already there)
Shared/03 Projects/Active (2 files: 2 to move, 0 already there)
Shared/04 Health and Safety (2 files: 2 to move, 0 already there)
Shared/05 Archive (1 file: 1 to move, 0 already there)
Waiting on a duplicate decision: 4 rows in 2 groups, not counted above.
Not planned: 2 rows, not counted above.

Files to move: 10
Row 1: 2026 insurance schedule.pdf, from Shared/Misc to Shared/01 Admin/Insurance (rule R3). Owner: Priya. Approves: Priya. Status: Ready for owner approval.
Row 3: Supplier terms - Supplier B.pdf, from Shared/Misc to Shared/01 Admin/Suppliers (rule R4). Owner: Priya. Approves: Priya. Status: Ready for owner approval.
Row 4: Invoice 0412 Customer C.pdf, from Shared/Invoices 2025 to Shared/02 Finance/Invoices (rule R2). Owner: Grace. Approves: Grace. Status: Held until Question 2 is answered.
Row 5: Invoice 0413 Customer D.pdf, from Shared/Invoices 2025 to Shared/02 Finance/Invoices (rule R2). Owner: Grace. Approves: Grace. Status: Ready for owner approval.
Row 6: Payslip run Oct 2026.xlsx, from Shared/Payroll to Shared/02 Finance/Payroll (rule R1). Owner: Grace. Approves: Grace; also Tobias (finance director) for restricted records. Status: Held until Question 3 is answered.
Row 9: Work order 2611 Customer E.xlsx, from Shared/Projects to Shared/03 Projects/Active (rule R6). Owner: Wen. Approves: Wen. Status: Ready for owner approval.
Row 10: Work order 2612 Customer F.xlsx, from Shared/Projects to Shared/03 Projects/Active (rule R6). Owner: NOT RECORDED. Approves: NOT RECORDED. Status: Held until Questions 4 and 5 are answered.
Row 7: Risk assessment - saw room.docx, from Shared/Misc to Shared/04 Health and Safety (rule R5). Owner: Hamid. Approves: Hamid. Status: Ready for owner approval.
Row 8: Method statement - roof repair.docx, from Shared/Misc to Shared/04 Health and Safety (rule R5). Owner: Hamid. Approves: Hamid. Status: Ready for owner approval.
Row 12: Staff handbook 2022.pdf, from Shared/Old to Shared/05 Archive (rule R7). Owner: Priya. Approves: Priya. Status: Held until Question 6 is answered.

Ready moves by owner: Priya: rows 1, 3; Grace: row 5; Wen: row 9; Hamid: rows 7, 8

Files that stay: 1
Row 17: Invoice 0410 Customer C.pdf is already in Shared/02 Finance/Invoices (rule R2).

Duplicates to resolve: 2 groups
Likely copies: "Supplier terms - Supplier A.pdf", rows 2 and 11.
Row 2: Shared/Misc, 230 KB, modified 2025-06-02, owner Priya.
Row 11: Shared/Misc, 230 KB, modified 2025-06-02, owner Ola.
If kept, rule R4 files it in Shared/01 Admin/Suppliers. See Question 1.
Possible versions: "Risk assessment - office.docx", rows 15 and 16.
Row 15: Shared/Misc, 45 KB, modified 2026-02-11, owner Hamid.
Row 16: Shared/Old, 52 KB, modified 2025-02-09, owner Hamid.
If kept, rule R5 files it in Shared/04 Health and Safety. See Question 9.

Not planned: 2
Row 13: Away day photos.zip, no filing rule matches. See Question 7.
Row 14: NO NAME, incomplete row: name missing. See Question 8.

Questions to settle: 9
Question 1 [duplicate]. Rows 2 and 11. "Supplier terms - Supplier A.pdf" is in Shared/Misc twice, 230 KB and modified 2025-06-02 on both. Row 2 is Priya's and row 11 is Ola's. Priya and Ola, are these the same document, and what should be done with the two rows?
Question 2 [access]. Row 4. Invoice 0412 Customer C.pdf is shared with Finance and Office; Shared/02 Finance/Invoices is for Finance. Only on the file: Office. Only on the folder: none. Grace, should Office keep access to this file?
Question 3 [restricted record]. Row 6. Payslip run Oct 2026.xlsx would be filed in Shared/02 Finance/Payroll, which the conventions list as restricted. Tobias (finance director), do you confirm that this file may move?
Question 4 [owner]. Row 10. Work order 2612 Customer F.xlsx has no owner recorded. Priya, who owns it?
Question 5 [shared link]. Row 10. Work order 2612 Customer F.xlsx is shared by link. Priya, once Question 4 names its owner, please put this to them: should the link keep working after the move?
Question 6 [access]. Row 12. Staff handbook 2022.pdf is shared with All staff; Shared/05 Archive is for Office. Only on the file: All staff. Only on the folder: Office. Priya, should All staff keep access to this file?
Question 7 [no rule]. Row 13. Away day photos.zip, modified 2026-09-18, matches none of rules R1 to R7. Priya, which folder should it go in, or should a rule be added to the conventions?
Question 8 [incomplete row]. Row 14. This row has no file name; it is in Shared/Misc, 12 KB, modified 2026-08-01, owner Wen. Wen, what is this file?
Question 9 [duplicate]. Rows 15 and 16. "Risk assessment - office.docx" is in Shared/Misc (45 KB, modified 2026-02-11) and in Shared/Old (52 KB, modified 2025-02-09), both Hamid's, with different sizes. Hamid, how do these two relate, and what should be done with them?

Nothing has been moved, renamed, deleted or re-shared. Approvals still to come: the coordinator, for this plan; each owner, for their own moves.
```

How the inputs became the output, for checking:

- **Seventeen rows** in the inventory. Ten are moves (rows 1, 3, 4, 5, 6, 7, 8, 9, 10, 12), one stays (row 17), four are in duplicate groups (rows 2, 11, 15, 16) and two are not planned (rows 13, 14). 10 + 1 + 4 + 2 = 17.
- **Duplicates.** Rows 2 and 11 share a name and a size (230 KB): likely copies. Rows 15 and 16 share a name but are 45 KB and 52 KB: possible versions. The rules are tested against the first row of each group: row 2 for the first group, which rule R4 (name contains "supplier") files in Suppliers, and row 15 for the second, which rule R5 files in Health and Safety.
- **Capital letters.** Name and path conditions ignore them. The rules are written in lower case ("invoice", "payslip", "risk assessment") and the file names in capitals ("Invoice 0412", "Payslip run"); every one of those matches.
- **Rule order.** Row 3 is from February 2024, more than 24 months before today (R7 would catch it, cut-off 10 November 2024), but R4 comes first and wins. Row 12, the 2022 staff handbook, matches no rule from R1 to R6, so R7 files it in the archive. Row 13 was modified in September 2026, so R7 does not apply, and nothing else matches.
- **Access.** Rows 1, 3, 5, 6, 7, 8 and 9 have exactly the sharing their destination's audience lists. Row 4 has Finance and Office against Finance. Row 12 has All staff against Office. Row 10's sharing matches (Projects; Office), but it has no owner and is shared by link.
- **Held.** Row 4 (Question 2), row 6 (Question 3, restricted record), row 10 (Questions 4 and 5) and row 12 (Question 6): four held. The other six moves (rows 1, 3, 5, 7, 8, 9) are ready: 6 + 4 = 10.
- **Folder counts.** Invoices: rows 4 and 5 to move, row 17 already there, three files. Active: rows 9 and 10. Health and Safety: rows 7 and 8. The rest hold one each. 1 + 1 + 3 + 1 + 2 + 2 + 1 = 11 = 10 moves + 1 stay.
- **Order.** Moves follow the conventions' folder order: Insurance, Suppliers, Invoices, Payroll, Active, Health and Safety, Archive. That is why rows 9 and 10 come before rows 7 and 8. Owners under "Ready moves" appear in the order they first appear in the list: Priya, Grace, Wen, Hamid.

Priya reads the plan, asks the people named in the questions, passes the six ready moves to their owners, and makes any changes in the drive herself or with the owners once they have approved. The assistant moved nothing.
