# Front End Development 1 - Rocket Genesis Collaboration

## Project Overview

This module introduces **API integration, dynamic data rendering, and advanced form handling** by extending the Rocket Elevators website with real-time agent data and contact form functionality. You'll learn to fetch data from external APIs, manipulate tables dynamically, handle form submissions, and apply custom styling to enhance user experience.

## Key Concepts to Research

### API Integration & HTTP Methods

- **Fetch API**: Making HTTP requests in JavaScript
- **Async/Await**: Handling asynchronous operations
- **GET Requests**: Fetching data from external APIs (`/api/agents`)
- **POST Requests**: Sending data to servers (`/api/contact`)
- **HTTP Headers**: Setting `Content-Type`, understanding request/response headers
- **JSON**: Parsing and stringifying data (`JSON.parse()`, `JSON.stringify()`)
- **Error Handling**: Try-catch blocks, handling failed requests

### Dynamic Table Rendering

- **Dynamic HTML Generation**: Creating table rows programmatically
- **Template Literals**: Multi-line HTML strings with embedded variables
- **Table Manipulation**: Adding/removing rows, updating content
- **Row Numbering**: Tracking and displaying sequential numbers
- **Conditional Rendering**: Showing/hiding elements based on data
- **Empty State Handling**: Displaying messages when no data matches filters

### Filtering & Sorting

- **Dropdown Filters**: Region-based data filtering
- **Array Methods**: `.filter()`, `.forEach()`, finding matching items
- **Sorting Algorithms**: Comparing values, ascending/descending order
- **Toggle States**: Tracking sort direction with boolean flags
- **Data Comparison**: Handling different data types (strings, numbers)
- **Multiple Sort Keys**: Sorting by different table columns

### Form Handling & Validation

- **Form Elements**: Input fields, textareas, select dropdowns, file uploads
- **Form Data Collection**: Reading values from multiple inputs
- **Event Prevention**: `e.preventDefault()` to stop default form submission
- **Client-Side Validation**: Required fields, email format, data types
- **Form Reset**: Clearing inputs after submission
- **File Attachments**: Handling file input fields

### Modal Dialogs & User Feedback

- **Bootstrap Modals**: `$("#modal-id").modal("show")`
- **Success Messages**: Displaying confirmation after actions
- **Error Messages**: Showing failure notifications
- **Dynamic Modal Content**: Updating modal text based on results
- **Modal Events**: Open, close, button click handlers

### Advanced CSS Styling

- **CSS Variables**: Brand colors (`#0a65a0`, `#A94545`)
- **Custom Themes**: Overriding default Bootstrap styles
- **Gradient Backgrounds**: `linear-gradient()` for visual effects
- **Font Integration**: Google Fonts (Roboto Slab)
- **Selector Specificity**: ID vs. class vs. element selectors
- **Layout Styling**: Margin, padding, alignment, display properties

### Event-Driven Programming

- **Window Events**: `load` event for initialization
- **Form Events**: `submit` event handling
- **Input Events**: `change` event for dropdowns
- **Button Events**: `click` event for sorting
- **Event Listeners**: Adding multiple listeners to elements
- **Event Delegation**: Handling events on dynamic content

### Data Structures & State Management

- **Global Variables**: Storing fetched data in arrays
- **Filtering Logic**: Rating thresholds (`AGENT_RATING_THRESHOLD`)
- **State Tracking**: Boolean flags for sort direction
- **Data Transformation**: Converting API responses to display format
- **Object Destructuring**: Extracting properties from objects

### Code Organization & Best Practices

- **API Endpoints**: Centralized URL constants
- **Separation of Concerns**: Utility functions, business logic, UI updates
- **Function Naming**: Clear, descriptive function names
- **Comments**: Section headers, explaining complex logic
- **Error Logging**: Console logging for debugging
- **Async Operations**: Proper handling of promises

## Learning Resources

Use search engines and AI assistants to explore these concepts:

- "JavaScript Fetch API tutorial"
- "How to make POST requests with fetch"
- "Dynamic table creation with JavaScript"
- "JavaScript array sorting and filtering"
- "Bootstrap modal JavaScript API"
- "CSS gradient backgrounds"
- "JavaScript async/await explained"
- "Form data collection JavaScript"
- "Event listener best practices"

## API Endpoints

- **GET** `http://99.79.77.144:3000/api/agents` - Fetch all agents data
- **POST** `http://99.79.77.144:3000/api/contact` - Submit contact form

## New Features Implemented

### Agent Management System

- **Real-time Data Fetching**: Load agents from external API
- **Rating-Based Filtering**: Show only agents with rating ≥ 85
- **Regional Filtering**: Filter by North, South, East, West regions
- **Dynamic Sorting**: Sort by first name, last name, fee, rating
- **Interactive Table**: Click column headers to sort

### Contact Form Enhancement

- **API Integration**: Send form data to backend server
- **Multi-field Form**: Full name, email, phone, company details
- **File Upload Support**: Attach documents to submissions
- **Success/Failure Modals**: Visual feedback for user actions
- **Data Collection**: Structured JSON payload creation

### Visual Improvements

- **Custom Color Scheme**: Brand-specific colors (#0a65a0 blue, #A94545 red)
- **Dynamic Card Headers**: Background color changes based on building type
- **Gradient Footer**: Eye-catching gradient effect
- **Typography Enhancement**: Roboto Slab font integration
- **Consistent Branding**: Unified design across all pages

## Development Tips

- **Test API Endpoints**: Use browser console or API testing tools
- **Console Logging**: Add `console.log()` to debug data flow
- **Error Handling**: Always implement try-catch blocks for API calls
- **Modular Code**: Keep functions focused on single responsibilities
- **User Experience**: Provide clear feedback for all user actions
- **Data Validation**: Verify data before sending to APIs
- **Responsive Design**: Test on different screen sizes
