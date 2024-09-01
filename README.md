# Mini Calendar Project
This project creates a mini calendar display using HTML, CSS, and JavaScript. The calendar shows the current date, day of the week, month, and year, all formatted in a visually appealing design.

<h2>Key Features</h2>
<h3>Current Date Display</h3>
<h4>Date and Day</h4> 
The left side of the calendar prominently displays the current date in large, bold numbers, accompanied by the day of the week. This layout ensures that the most important information is easy to spot at a glance. 
<h4>Month and Year</h4>
The right side of the calendar shows the current month and year in contrasting colors, creating a clear and organized interface that separates the date details for easy readability. 
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
The HTML structure consists of a main container that houses the calendar, divided into two sections: one for the date and day, and another for the month and year. The calendar is enclosed within a `div` element that provides a structured layout. 
<h3>CSS Styling</h3>
<h4>Container and Calendar Design</h4>
The calendar is centered on the page using flexbox, with a modern design featuring a background gradient, rounded corners, and distinct sections for the date and time information. The left section is wider, highlighting the date, while the right section is styled with a vibrant color to emphasize the month and year. 
<h4>Responsive and Consistent Styling</h4>
The design is fully responsive, adapting to different screen sizes while maintaining consistent font styles and layout. The use of flexbox ensures that the content remains aligned and centered regardless of the viewport size. 
<h3>JavaScript Functionality</h3>
<h4>Dynamic Date Display</h4>
JavaScript is used to dynamically update the calendar with the current date, day, month, and year. The script retrieves the current date using the `Date` object and formats the information before inserting it into the HTML elements.

    const today = new Date();
    date.innerHTML = (today.getDate() < 10 ? "0" : "") + today.getDate();
    day.innerHTML = weekDays[today.getDay()];
    month.innerHTML = allMonths[today.getMonth()];
    year.innerHTML = today.getFullYear();

<h4>Automatic Updates</h4>
The date, day, month, and year are automatically updated each time the page is loaded, ensuring that the displayed information is always accurate without requiring user intervention. 
<h2>In Summary</h2> 
This mini calendar project offers a simple and effective way to display the current date in a visually appealing format. With its clean design and automatic updates, it serves as a practical tool for any webpage or application that requires a quick reference to the current date and time. The implementation combines modern web technologies, making it easy to integrate and expand for more advanced calendar functionalities.
