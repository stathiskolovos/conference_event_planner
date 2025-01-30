# Practice project: Conference Expense Planner app

In the Conference Expense Planner app practice project, you will build the front end of an application that allows the user to price out the expenses related to hosting a conference at a convention center. The lab will guide you through the development of the application elements required for this project.

The Conference Expense Planner will have a landing page, a product selection page, and a pop-up summary window. The product selection page allows users to select their rooms, their add-ons, and meals. Based on those selections, it provides pricing. The pop-up window summarizes the expenses in a table based on the user's selections from the product selection page.

<h2>Landing Page</h2>

The landing page will have the same elements as the final project's landing page.

You will create a landing page like the image below that engages your customers with your product line and provides entry into the main application. See the screenshot at the end of this section for a visual of what this page might look like.

Features on this page should include:
1. A paragraph about the company
2. A background image
3. Your company name and
4. A Get Started button linking to the product selection page

<h2>Product selection page</h2>

After selecting Get Started, the application should direct the user to the product selection page. This page allows users to select rooms in the venue, add-ons needed for presentations such as microphones and speakers, and meals they would like catered for the participants. This page will have three sections: room selection, add-ons, and meals. Each section should have its own header and also a page header with navigation to each section.

The suggested layout is displayed in an annotated screenshot for each section and an image of the whole page.
Room selection and navigation bar

Users select from 5 room types:
1. Auditorium hall – capacity 200, $5500 ea
2. Conference room – capacity 15, $3500 ea
3. Presentation room – capacity 50, presentation room, $700 ea
4. Large meeting room – capacity 10, $900 ea
5. Small meeting room – small meeting room, capacity 5, $1100 ea

You will provide an increment and decrement button for each room type so the user can request the number of each room type they need.

The product selection page should also have a header with a navigation bar. The navigation bar should display a Show Details button, which opens a pop-up window displaying data related to the user's selections.

<h2>Add-ons selection</h2>

Users can select their audio/visual equipment in the add-ons section:
1. Speakers – $35 ea
2. Microphones – $45 ea
3. Whiteboards – $80 ea
4. Projectors – $200 ea
5. Signage – $80 ea

You will provide an increment and decrement button for each type of equipment so the user can request the number of each type of AV equipment they need.

<h2>Meals selection</h2>

Users can select the following options for meals in the meals section:
1. Breakfast – $50 per person
2. Lunch – $60 per person
3. High tea – $25 per person
4. Dinner – $70 per person

You will provide a text entry box where the user can enter the number of people for these meals.

<h2>Show details pop-up</h2>

The users will need to see the details of their selections. For this element, they can access this information through a Show Details button in the header. When the user selects the button, a window pops up displaying a four-column table. Each row of the table contains the selection type, its unit cost, the quantity indicated, and the subtotal for the quantity of that item type. It will also display the total cost for all items.
