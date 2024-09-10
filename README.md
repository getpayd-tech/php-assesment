### Technical Assessment: Laravel Payment Link Generator

*Overview:*

This assessment is designed to evaluate your ability to translate simple concepts into functional products while utilizing the Payd Payment API. You will create a Laravel-based application that generates payment links with predefined amounts, allowing customers to pay via Mpesa.

*Requirements:*

- Build a Laravel-based web application that generates payment links.
- The links should allow customers to make payments via Mpesa using the Payd API (https://docs.mypayd.app).
- Each link generated should have a specific amount associated with it, and when the customer accesses the link, they should be able to initiate the payment.

### Assessment Objectives:

1. *Problem Solving*:
   - Conceptualize and implement a solution based on the task description.
   - Ensure that your code is clean, maintainable, and follows best practices.

2. *API Integration*:
   - Utilize Payd Payment API to create payment links that work with Mpesa.
   - You are free to explore the API documentation and implement the endpoints that align with the task.

3. *UI/UX*:
   - Build a user-friendly interface where users can generate payment links.
   - Ensure the UI is clean, minimal, and easy to navigate.

4. *Product Stability*:
   - Handle potential errors from the API and provide meaningful feedback to users.
   - Ensure that the application is stable and secure.

---

### Instructions:

1. *Project Setup*:
   - Create a new Laravel project.
   - Integrate Payd Payment API (https://docs.mypayd.app).
   - You are allowed to use Laravel's inbuilt libraries and packages to aid in faster development.

2. *Feature Implementation*:
   - *Homepage*: A simple form where a user can input the payment amount.
   - *Payment Link Generation*: On form submission, generate a payment link using the Payd API, with the amount provided by the user.
   - *Link Display*: After the link is generated, display it to the user so they can share it.
   - *Payment Status*: After a customer completes the payment via Mpesa, provide a way for the user to check the payment status.

3. *API Interaction*:
   - Use the Payd API to:
     - Generate payment links.
     - Handle payments via Mpesa.
     - Check the status of the payment.
  
4. *Submission*:
   - Once completed, provide:
     - A GitHub repository with clear instructions on how to run the project locally.
     - A brief documentation file explaining your thought process and any assumptions made.

---

### Evaluation Criteria:

- *Code Quality*: Is the code clean, organized, and easy to read?
- *Problem-Solving*: How well did you translate the concept into a working product?
- *API Integration*: Is the Payd API correctly integrated, and do the payment links function as expected?
- *User Interface*: Is the UI intuitive and user-friendly?
- *Error Handling*: Are errors from the API handled gracefully?
- *Documentation*: Is the project well-documented?

### Bonus Points:

- Implement additional features such as payment tracking or email notifications on payment completion.
- Use modern Laravel features (like jobs or queues) to handle background tasks such as checking payment statuses.

Good luck, and we look forward to seeing how you approach the task!
