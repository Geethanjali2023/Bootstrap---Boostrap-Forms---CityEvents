# CityEvents Web Application Development

## Scenario
**Business Problem:** Develop an interactive and responsive web application for "CityEvents", a company that organizes local events. The application should include an event listing, a registration form, and user feedback section.

## Objectives
1. **Responsive Layout:** Utilize Bootstrap's grid system for layout design.
2. **HTML Forms:** Implement registration and feedback forms.
3. **Semantic HTML:** Use semantic tags for content structure.
4. **CSS Styling:** Apply CSS for custom styles.
5. **Bootstrap Typography:** Use typography classes for text styling.
6. **Bootstrap Form Classes:** Implement form classes for enhanced user experience.

## Expected Outcomes
- A multi-page responsive web application.
- User-friendly registration and feedback forms.
- Aesthetically pleasing design using CSS and Bootstrap typography.

## Exercise Steps

### Step 1: Responsive Layout with Bootstrap Grid
- **Task:** Create the main layout with header, footer, and two main content columns.
- **Hints:** 
  - Use `container`, `row`, and `col-md-*` classes for responsive columns. 
  - Structure: Header, Main Content (2 columns), Footer.

### Step 2: HTML Registration Form
- **Task:** Develop a registration form for event sign-up.
- **Hints:** 
  - Use `<form>` with `form-control`, `form-group`, and input types like text, email, and submit. 
  - Include fields for name, email, and event selection.

### Step 3: Semantic HTML for Content
- **Task:** Structure the content using semantic HTML tags.
- **Hints:** 
  - Use tags like `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`. 
  - Ensure accessibility and SEO optimization.

### Step 4: CSS Styling
- **Task:** Customize the look and feel using CSS.
- **Hints:** 
  - Apply CSS for custom colors, margins, padding, and borders. 
  - Enhance readability and aesthetic appeal.

### Step 5: Bootstrap Typography
- **Task:** Apply Bootstrap typography classes to style text content.
- **Hints:** 
  - Use classes like `text-primary`, `font-weight-bold`, `lead`. 
  - Ensure text is readable and visually appealing.

### Step 6: Implementing Bootstrap Form Classes
- **Task:** Enhance the forms using Bootstrap's form classes.
- **Hints:** 
  - Use `form-check`, `form-control`, `form-group` for structured and appealing forms. 
  - Ensure the forms are user-friendly and responsive.


## Fill in the Blanks

1.  `___1___`:  Use "custom-header bg-primary text-white" for a styled header.
2.  `___2___`:  Apply "form" to create a structured form element.
3.  `___3___`:  Use "btn-primary" for a primary styled submit button.
4.  `___4___`:  Use "custom-footer bg-dark text-white" for a styled footer.

## Explanation

This exercise provides a practical application of Bootstrap 4, HTML, and CSS through the development of a responsive web application for "CityEvents". Candidates will gain hands-on experience in creating responsive layouts, formulating forms, applying semantic HTML for content structuring, customizing styles with CSS, and utilizing Bootstrap typography and form classes. The fill-in-the-blanks approach reinforces learning by encouraging candidates to apply concepts directly in code, with hints and structure provided for guidance. This comprehensive task not only tests their knowledge but also enhances their practical skills in web development.



## 📸 Screenshots
![image](https://github.com/Geethanjali2023/Bootstrap---Boostrap-Forms---CityEvents/blob/main/image_20231225_185945ae26e831-93e5-48a0-bca2-e97581028431.jpg)

## Detailed Code Snippets with Fill in the Blanks
```html
<!DOCTYPE html>
<html>
<head>
    <title>CityEvents</title>
    <link rel="stylesheet" href="path/to/bootstrap.css">
    <style>
        .custom-header { /* CSS styles */ }
        .custom-footer { /* CSS styles */ }
        /* Additional custom CSS */
    </style>
</head>
<body>
    <header class="___1___">
        <h1>CityEvents - Your Local Event Guide</h1>
    </header>
    <main class="container">
        <section class="row">
            <article class="col-md-8">
                <!-- Event listing -->
            </article>
            <aside class="col-md-4">
                <form class="___2___">
                    <div class="form-group">
                        <label for="nameInput">Name</label>
                        <input type="text" class="form-control" id="nameInput" placeholder="Enter name">
                    </div>
                    <div class="form-group">
                        <label for="emailInput">Email</label>
                        <input type="email" class="form-control" id="emailInput" placeholder="Enter email">
                    </div>
                    <!-- Additional form elements -->
                    <button type="submit" class="btn ___3___">Register</button>
                </form>
            </aside>
        </section>
    </main>
    <footer class="___4___">
        <p>Contact us at info@cityevents.com</p>
    </footer>
</body>
</html>

<!-- End of the code block for your HTML code -->
