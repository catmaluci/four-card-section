# Frontend Mentor -  Four card feature section Solution🔗
This is my solution to the [Four card feature section Solution challenge](https://four-card-section-phi.vercel.app/) on Frontend Mentor.

## Overview ✨

### The Challenge

The goal was to build a responsive feature section with four distinct cards that matches the provided design for both desktop and mobile screens. Key requirements included:

- Building a responsive layout that adapts to different device screen sizes.
- Replicating the distinct card styles, including the top-border colors and box shadows.
- Ensuring all content is structured semantically.


### Preview

![Screenshot](./images/preview.jpg) 

## 🛠️ Technologies Used
- **HTML5** - For the semantic structure of the entire page.
- **CSS3** - For styling the layout, cards, and typography.
- **Flexbox** - Used to create the responsive main layout for both desktop and mobile views.
- **CSS Positioning** - Utilized position: relative and position: absolute to precisely place the icons at the bottom-right of each card.

## My Process 🛠️
### 1. HTML Structure 📋
I created a semantic HTML structure with:
- A `<header>` for the main title and description of the section.
- A `<main>` container to wrap all four cards.
- Each card was built as a `<section>`element with a unique class to define its top-border color.
 -A `<div>` was used to group the two middle cards for better layout control.
- Inside each card, I included a `<h3>` for the title, a `<p>` for the description, and an `<img>` for the icon.


### 2. Styling 🎨
- **Mobile-first approach** 📱
- **Typography**  Imported and applied custom fonts from the style guide.
- **Layout**  I used Flexbox on the <main> container to arrange the cards. On desktop, they are arranged in a row, with the two middle cards stacked in a column. For mobile, the entire layout adapts to a single column.
- **Card Styling:** Each card has a border-top to match the design and a box-shadow for the lifted effect.
- **Icon Positioning:** I applied position: relative to the parent section and position: absolute to the img icon. This allowed me to use bottom and right properties to place the icon in the bottom-right corner of each card, regardless of the text length.

## 📚 What I Learned

- **Advanced CSS Positioning:** I reinforced my understanding of position: relative and position: absolute by using them to place the icons precisely within their parent containers.

- **Responsive Design with Flexbox:** I learned how to combine Flexbox with media queries to create a more complex, multi-row layout that works seamlessly across different screen sizes.

- **Attention to Detail:** The biggest takeaway was the importance of adjusting small details like typography, padding, and box-shadow values to make the final component look polished and match the design as closely as possible.



## 🔗 Links
- **🌐 Live Site URL**: [Four card feature section Solution challenge](https://four-card-section-phi.vercel.app/)

### **👥 Solved by M Olaya** 
<a href="https://www.linkedin.com/in/molaya">LinkedIn</a> 
