# **WCAG 2.1 Accessibility Evaluation for Wikipedia.org**

This project contains an accessibility evaluation report of the Wikipedia homepage, conducted according to the **Web Content Accessibility Guidelines (WCAG) 2.1**. The report evaluates the compliance of the site with 20 success criteria from the four WCAG 2.1 principles: Perceivable, Operable, Understandable, and Robust.

## **Project Overview**

- **Website Tested**: [https://www.wikipedia.org](https://www.wikipedia.org)
- **Date of Test**: October 2, 2024
- **Tester**: Noah Gerber, Eren Homburg
- **Tool Used**: [W3C WCAG Evaluation Tool](https://www.w3.org/WAI/eval/report-tool/)

## **Evaluation Summary**

This evaluation assesses the accessibility of Wikipedia.org against 20 success criteria across all four WCAG 2.1 principles. The website passed 12 out of 20 criteria.

- **Criteria Passed**: 12
- **Criteria Failed**: 8

## **Tested Criteria**

### **Perceivable**

1. **1.1.1 Non-text Content** - **Passed**

   - **Explanation**: All images on the page have descriptive alternative text that explains the purpose of the image. Icons, such as the search button, also contain accessible text.

2. **1.2.1 Audio-only and Video-only (Prerecorded)** - **Not Applicable**

   - **Explanation**: Wikipedia’s homepage does not contain audio or video content.

3. **1.2.2 Captions (Prerecorded)** - **Not Applicable**

   - **Explanation**: No multimedia elements are used on the homepage.

4. **1.3.1 Info and Relationships** - **Passed**

   - **Explanation**: The HTML structure correctly uses headings, lists, and regions (e.g., `<h1>`, `<h2>`, `<ul>`, `<nav>`) to convey information and relationships, making the page navigable with assistive technologies.

5. **1.3.5 Identify Input Purpose** - **Failed**

   - **Explanation**: Input fields, such as the search bar, do not provide a programmatically determined purpose, which limits accessibility for users with disabilities.

6. **1.4.1 Use of Color** - **Passed**

   - **Explanation**: Color is not the only method used to convey important information. Links are underlined and use a contrasting color to distinguish them from regular text.

7. **1.4.3 Contrast (Minimum)** - **Failed**

   - **Explanation**: Some text does not meet the minimum contrast ratio of 4.5:1 against the background (e.g., grey text on white backgrounds in specific regions of the page).

8. **1.4.4 Resize Text** - **Passed**

   - **Explanation**: The text on the page can be resized up to 200% without loss of content or functionality.

9. **1.4.10 Reflow** - **Passed**

   - **Explanation**: The layout adapts properly when the viewport width is reduced or increased, maintaining readability and functionality.

10. **1.4.11 Non-text Contrast** - **Failed**
    - **Explanation**: Some non-text elements, such as buttons and icons, do not meet the required contrast ratio of 3:1 against their backgrounds.

### **Operable**

11. **2.1.1 Keyboard** - **Passed**

- **Explanation**: The entire Wikipedia homepage can be navigated using only the keyboard, and all functions, including search and links, are operable.

12. **2.1.2 No Keyboard Trap** - **Passed**

- **Explanation**: No keyboard traps are present. Users can navigate to all elements using the keyboard and move away from them easily.

13. **2.2.1 Timing Adjustable** - **Not Applicable**

- **Explanation**: There are no time-based components on the Wikipedia homepage.

14. **2.4.1 Bypass Blocks** - **Passed**

- **Explanation**: There is a "skip to content" link, allowing users to bypass repetitive navigation links.

15. **2.4.2 Page Titled** - **Passed**

- **Explanation**: The page has a meaningful title (`"Wikipedia"`), making it easy to identify when using assistive technologies or when multiple tabs are open.

16. **2.4.3 Focus Order** - **Passed**

- **Explanation**: The focus order is logical when navigating through the keyboard, ensuring that users with disabilities can follow the content in a meaningful sequence.

17. **2.4.4 Link Purpose (In Context)** - **Passed**

- **Explanation**: Links are descriptive and make sense in context. For example, “Read more” links are paired with text that explains what the user will be reading.

18. **2.4.6 Headings and Labels** - **Failed**

- **Explanation**: Some headings and labels are not clear or descriptive enough for assistive technology users to easily understand their purpose.

19. **2.5.3 Label in Name** - **Failed**

- **Explanation**: The label for the search field is not programmatically tied to the field, limiting accessibility for screen readers.

### **Understandable**

20. **3.1.1 Language of Page** - **Passed**

- **Explanation**: The primary language of the page (English) is identified correctly in the HTML (`<html lang="en">`).

21. **3.2.1 On Focus** - **Passed**

- **Explanation**: No unexpected changes occur when elements receive focus, making the page predictable and easier to navigate for users.

22. **3.3.1 Error Identification** - **Not Applicable**

- **Explanation**: There are no forms on the homepage, so error identification is not applicable.

23. **3.3.2 Labels or Instructions** - **Failed**

- **Explanation**: The search input field does not have sufficient labels or instructions for screen reader users to understand its purpose clearly.

### **Robust**

24. **4.1.1 Parsing** - **Passed**

- **Explanation**: The HTML is well-formed, and the page parses correctly across different user agents and assistive technologies.

25. **4.1.2 Name, Role, Value** - **Failed**

- **Explanation**: Some interactive elements, such as the search input field, lack proper labels or roles that would allow assistive technologies to convey the full meaning and purpose of the element to users with disabilities.
