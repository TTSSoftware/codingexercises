# UIPath Automation Coding Exercises

Below are three practical coding exercises intended for evaluating a Senior UI Automation Engineer's proficiency with UIPath. Each exercise references publicly accessible real-world applications for demonstration purposes. Candidates should complete each task in about 15 minutes, with all three comfortably achievable within a 45-minute session.

---

## Exercise 1: Automated Web Form Submission

**Objective:**  
Automate the process of filling out and submitting a web form using data from an Excel spreadsheet.

### Real-world Application:
- [W3Schools HTML Form](https://www.w3schools.com/html/html_forms.asp) *(Free, anonymous access)*

### Steps:
1. Read user information (`First Name`, `Last Name`) from an Excel file.
2. Open the [W3Schools HTML Form page](https://www.w3schools.com/html/html_forms.asp).
3. Automatically fill each form field on the first form with the data retrieved from Excel.
4. Submit and confirm successful filling of the form.

---

## Exercise 2: Dynamic Data Extraction and Validation

**Objective:**  
Automate data extraction from a dynamic webpage and validate the extracted data according to given criteria.

### Real-world Application:
- [Books to Scrape](http://books.toscrape.com/) *(Publicly available, no login required)*

### Steps:
1. Navigate to the [Books to Scrape](http://books.toscrape.com/) webpage.
2. Extract book titles and corresponding prices from the homepage.
3. Validate each book price to ensure it does not exceed £50.
4. Log validation results (`Title`, `Price`, `Validation Status`) to an Excel file or structured log file.

---

## Exercise 3: Waiting for animation to complete.

**Objective:**  
Wait for animation to complete before interacting with a screen element.

### Real-world Application:
- [UITesting Playground](http://uitestingplayground.com/animation/) *(Publicly available, no login required)*

### Steps:
1. Navigate to the [UITesting Playground age](http://uitestingplayground.com/animation/) webpage.
2. Click on the Start Animation button.
3. Wait for the animation to complete before clicking on the Moving Target button.
4. Click on the Moving Target button, then validate that its class doesn't contain the word spin.

---

## Exercise 4: Handle Partially Visible UI Element

**Objective:**  
Demonstrate ability to handle a partially visible UI Element by scrolling it into view.

### Real-world Application:
- [UITesting Playground](http://uitestingplayground.com/animation/) *(Free, anonymous, specifically designed for UI testing)*

### Steps:
1. Navigate to the [UITesting Playground](http://uitestingplayground.com/animation/) page.
2. Enter a text value into the Id field.
3. The Name field will be only partially visible and not interactable.
4. Scroll the Name field into view and enter John Doe into it.
5. Validate that text was entered into both fields.

---

