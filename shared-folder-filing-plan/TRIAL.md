# Shared folder filing plan: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5), an AI model made by Anthropic
- **Date:** 2026-11-10

The inputs were the invented example only: the settings, the 17-row folder inventory and the filing conventions of Fennimore Yard Joinery, in [example.md](example.md). No client data was used. The instructions followed were the fenced block and the output format in the member template, version 0.1.0 as revised after an earlier run of the same version (see below).

## What came out

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

## What was observed

- **Every required part was produced:** the header and count line, the folder structure, moves, ready moves by owner, stays, both duplicate groups, rows not planned, nine numbered questions and the closing line. The counts tie: 17 = 10 + 1 + 4 + 2, and the folder counts total 11 = 10 moves + 1 stay.
- **Nothing was stopped for.** The settings were complete, the headers matched, there were 17 rows against a limit of 200, and the conventions held folders and rules. No request to move, delete or guess arose, so those refusals were not exercised.
- **Tests exercised:** 1 to 11 in the template's acceptance tests, all present in the example's data. Tests 12 to 14 (header mismatch and the two refusals) were not run.
- **Facts not in the inputs:** none. Every name, path, size, date and audience comes from the settings, inventory or conventions.
- **Case, date edges and restricted folders now follow the template's words.** The rules' lower-case words match the capitalised file names because the template says name conditions ignore capital letters. The 24-month cut-off is 2024-11-10; row 12 (2022-09-01) is earlier, row 3 (2024-02-20) is also earlier but R4 wins first, and no row falls on the cut-off date itself, so that edge was not exercised. The payroll restriction is written by destination folder and the template now says that is allowed.
- **Row numbers in the move list run out of sequence** (9, 10, 7, 8) because moves follow the conventions' folder order. This is as specified.

### What this run does not show

This run was made by working through the revised template by hand against the example's inputs, in the same session that edited the template and the example. It was not blind. The earlier trial record and the example's published output were both in view, and the plan above follows the example's wording exactly. It shows that the revised rules reproduce the example's counts, destinations, owners and statuses, and that the revised wording of the format (the plural "Held until Questions 4 and 5 are answered", the named interim addressee for Question 5) can be followed. It does not show that a fresh assistant given the block would phrase the questions the same way. A later run should be made by a fresh session that does not see the example's output.

### The earlier run, and what it led to

An earlier run of this version, before the edits, found these shortcomings, which were then fixed in the template and not re-found here: whether rule conditions ignore capital letters was unstated and the result depended on it; the pasteable block carried an unfilled batch-size placeholder; restricted records could be written by destination folder although the template spoke of files; the edges of the months-before-today test, the handling of files that stay and the date form were undefined; two published questions came close to asking for a keeper; and the header and closing lines used different wording for the same statement. That record is replaced by this one; its outputs differed from the example in the wording of a few questions only.
