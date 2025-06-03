# Ethical_AI
Feedback:

1.  **From Maya Knight:** "In Explore Our Core Topics on the Home page, the whole box moves when you hover, making the user think that the box is a link, whereas only the header is the link."
2.  **From Hana Knight:** "Your links are a bit dark. To those with impaired vision, it might be a bit hard to see. Your pages are full of important information which is amazing, but when you get to the end of the page, you have to scroll all the way back up to the nav bar to navigate to another page. It might be good for maneuverability to add an internal link at the bottom of each page to go back to the nav bar."

**Improvements:**

Based on the feedback, the following changes have been made to the website:

**"Explore Our Core Topics" Hover Effect (Addressing Maya Knight's feedback):**
    The hover effect on the "Explore Our Core Topics" items on index.html has been adjusted. Previously, the entire box would move, suggesting the whole area was clickable. Now, the transform and `box-shadow effects have been removed from      
     .topic-link-item:hover in styles.css. A more subtle text-decoration: underline and a slightly lighter color (#a0dfff) on hover have been applied directly to the <h3> <a> elements within .topic-link-item to clearly indicate that only the heading is the clickable link.

**Improved Link Visibility and Navigation (Addressing Hana Knight's feedback):**
    1.  Link Color: The general link color across the website has been updated in styles.css to a brighter blue (#66ccff) to enhance visibility and contrast for all users, including those with impaired vision. The navigation bar links retain their white color for consistency on the dark background.
    2.Back to Top Links: To improve maneuverability on longer pages, an internal "Back to Top" link has been added to the bottom of the main content area of every HTML page.  This allows users to quickly return to the top of the page (and the navigation bar). This was implemented by adding an id="top" to the <body> tag and then an <a href="#top">Back to Top</a> link before the <footer> on each page.

**Adjusted Navigation Bar Media Query (Addressing Hana Knight's feedback, related to maneuverability):**
    The media query for the navigation bar in styles.css has been refined. The max-width breakpoint was increased from 480px to 600px to ensure the navigation bar transitions to its vertical flexbox layout earlier on smaller screens. Additionally, padding and margin adjustments, along with a border-bottom for list items, were added within this media query to ensure a smoother and cleaner display of the vertical navigation.

**Images on "Unethical Uses" Page (Addressing Maya Knight's feedback):**
    images have been added to pages/unethical.html to break up the text and enhance visual engagement, especially within the list-heavy sections.