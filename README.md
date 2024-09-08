# Text Messenger

This project is a simple web-based text messenger interface built using HTML, CSS, and jQuery. It includes a basic input field for typing messages, buttons for sending messages, and interactive icons for adding attachments, images, and more. The user interface changes dynamically based on the input provided.

## Features

- **Responsive Design**: The layout adjusts itself to various screen sizes.
- **Dynamic Icon Visibility**: The "send" button appears only when there is text in the input field, otherwise, the "like" button is shown.
- **Icon-based Actions**: Options to upload images, add attachments, and send messages via icons.
- **jQuery Integration**: The project uses jQuery for dynamic behavior.

## Project Structure

```bash
|-- index.html      # Main HTML file
|-- style.css       # Stylesheet for the layout and design
|-- script.js       # JavaScript file handling dynamic behavior using jQuery
|-- jquery-3.6.1.js # jQuery library for DOM manipulation

Technologies Used

    HTML5: For structuring the page.
    CSS3: For styling and layout.
    jQuery: For dynamic functionality such as toggling the "send" and "like" icons based on input.

How It Works

    Icons: A series of icons representing actions like adding images, files, etc.
    Message Input: A user can type their message in the input field.
    Dynamic Button: The send button (fa-paper-plane) is hidden by default and appears only when text is entered, while the like button (fa-thumbs-up) is shown when the input is empty.
    Form Submission: The form isn't currently wired for backend processing, but the front-end form structure is ready.

How to Run

    Clone the repository.
    Open the index.html file in a web browser.
    The interface will load, and you can interact with the icons and input field.

Future Enhancements

    Add backend support for sending messages.
    Implement file uploads and image attachments.
    Create message display after sending a message.
