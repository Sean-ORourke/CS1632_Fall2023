TEST FIXTURE:
1. Firefox browser version >= 105, or Chrome browser version >= 105 is installed and launched.

TEST CASES:

```
IDENTIFIER: TEST-1-TITLE
TEST CASE: Check that title of the home page is "Department of Computer Science | University of Pittsburgh".
PRECONDITIONS: None.
EXECUTION STEPS: None.
1. Open the URL https://cs.pitt.edu/ on the web browser.
POSTCONDITIONS: The title of the page is "Department of Computer Science | University of Pittsburgh"
   (use **assert title" command).
```

```
IDENTIFIER: TEST-2-GIVE-BUTTON
TEST CASE: Check that the "GIVE" menu item exists.
PRECONDITIONS: None.
EXECUTION STEPS:
1. Open the URL https://cs.pitt.edu/ on the web browser.
POSTCONDITIONS: 
1. A menu item with the text "GIVE" is present on the page
   (use **assert element present** command).
```

```
IDENTIFIER: TEST-3-GIVE-LINK
TEST CASE: Check that the "GIVE" menu contains a link to "https://giveto.pitt.edu/giveSCI".
PRECONDITIONS: None.
EXECUTION STEPS:
1. Open the URL https://cs.pitt.edu/ on the web browser.
POSTCONDITIONS: 
1. The menu item with the text "GIVE" has an href attribute with the value "https://giveto.pitt.edu/giveSCI" 
   (use **store attribute** command followed by a **assert** command).
```

```
IDENTIFIER: TEST-4-RESEARCH-AREA-COMPUTER-VISION
TEST CASE: Check that the fifth item in the research areas page is "Computer Vision".
PRECONDITIONS: None.
EXECUTION STEPS:
1. Open the URL https://cs.pitt.edu/ on the web browser.
2. Click on the "Research" menu.
3. Click on the "Research Areas" link in the next page.
POSTCONDITIONS: 
1. The fifth div element in the research areas list contains the text "Computer Vision"
   (use **assert text** command).
```
