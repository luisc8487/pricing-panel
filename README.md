# Project Pricing Panel

## Overview
This project demonstrates the use of **HTML and CSS** to create a responsive pricing panel with three columns: **Personal, Small Team, and Enterprise**. The goal is to practice various Flexbox properties and ensure the panel adapts to different screen sizes for an optimal viewing experience on all devices.

## Pricing Panel Structure
The panel consists of three pricing tiers:

1. **Personal**: Displays the cost and a button for individual users.

2. **Small Team**: Contains pricing details and a button for small teams.

3. **Enterprise**: Features pricing information and a button for enterprise-level users.

Each column is structured using Flexbox to maintain alignment and spacing across different screen sizes.

## Flexbox Properties Used
### Alignment & Flex Sizing
- **align-content**: Controls how flex lines align when there is extra space in the cross axis.
- **align-items**: Aligns flex items along the cross axis.

### Flexbox Layout
- **justify-content**: Aligns items along the main axis.
- **flex-direction**: Determines the direction of items (row, column, etc.).
- **display**: flex: Establishes a flex container to manage the layout.

## Responsive Design with Media Queries
To ensure the pricing panel is viewable across all devices, **media queries** are used to:
- Adjust the flex properties based on screen width.
- Stack columns vertically on smaller screens for better readability.
- Modify font sizes, spacing, and other CSS properties for an optimized user experience.