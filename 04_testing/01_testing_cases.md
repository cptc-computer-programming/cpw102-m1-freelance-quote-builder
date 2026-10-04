# Test Cases

Choose and record your own inputs for each case. Use valid, nonnegative numeric values. **Calculate and record expected labor cost and total estimate before running your program.** Also describe the expected text cleanup, required quote fields, estimate label, and monetary formatting.

Run the program separately for each case. From the repository folder, you can use:

```text
python 03_execution/freelance_quote_builder.py
```

Record the actual output and mark each case Pass or Fail. If a case fails, describe the issue, revise your program, and record the result of running the case again. These are manual tests; automated tests are not required.

## Test Case 1: Ordinary Values

**Input / Action:**

Choose ordinary whole-number hours, a positive hourly rate, and positive direct expenses.

- Client name:
- Project title:
- Estimated work hours:
- Hourly rate:
- Direct expenses:

**Expected Result:**

- Labor cost (show your calculation):
- Total estimate (show your calculation):
- Expected text and display:

**Actual Result:**

_To be completed during testing._

**Result:**

Pass / Fail:

---

## Test Case 2: Partial Hours

**Input / Action:**

Choose hours with a fractional part to check that the program preserves partial hours in the calculation.

- Client name:
- Project title:
- Estimated work hours:
- Hourly rate:
- Direct expenses:

**Expected Result:**

- Labor cost (show your calculation):
- Total estimate (show your calculation):
- Expected text and display:

**Actual Result:**

_To be completed during testing._

**Result:**

Pass / Fail:

---

## Test Case 3: Zero Direct Expenses

**Input / Action:**

Enter zero direct expenses with positive hours and an hourly rate.

- Client name:
- Project title:
- Estimated work hours:
- Hourly rate:
- Direct expenses:

**Expected Result:**

- Labor cost (show your calculation):
- Total estimate (show your calculation):
- Expected text and display:

**Actual Result:**

_To be completed during testing._

**Result:**

Pass / Fail:

---

## Test Case 4: Text Cleanup and Capitalization

**Input / Action:**

Enter both text inputs with surrounding spaces. Use inconsistent capitalization in the client name and deliberate capitalization in the project title. Put quotation marks around your recorded text inputs to make spaces visible; do not type those quotation marks into the program.

- Client name:
- Project title:
- Estimated work hours:
- Hourly rate:
- Direct expenses:

**Expected Result:**

- Labor cost (show your calculation):
- Total estimate (show your calculation):
- Client name after cleanup:
- Project title after cleanup:
- Expected estimate label, fields, and monetary formatting:

**Actual Result:**

_To be completed during testing._

**Result:**

Pass / Fail:

---

## Testing Summary

What problems did you find, and what did you change? Record any retest results here.

What limitations remain? Include invalid numeric input, which is outside this lab's required behavior and may cause a crash. You are not required to test invalid input or prevent that crash.
