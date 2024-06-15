# React Form and State Management Demo

This project demonstrates how to manage form inputs and their corresponding state in a React functional component using hooks like useState.

## Key Concepts Illustrated

### Controlled Components

Each form input in this component is a controlled component. This means that the value of the input fields is controlled by React state, allowing for dynamic updates and synchronization with user input.

### State Management with useState

The component uses the useState hook to define and manage multiple state variables:

- **name**: Stores the name entered by the user.
- **quantity**: Stores the quantity entered by the user (numeric input).
- **comment**: Stores any delivery instructions or comments entered by the user.
- **payment**: Stores the selected payment option from a dropdown menu.
- **shipping**: Stores the selected shipping method (either "Pick up" or "Delivery") via radio buttons.

### Event Handling

Event handler functions (`handleNameChange`, `handleQuantityChange`, `handleCommentChange`, `handlePaymentChange`, `handleShippingChange`) update the respective state variables whenever the user interacts with the input fields or selects different options.

### Form Inputs Used

- **Input Field**: Used for entering the user's name.
- **Number Input**: Used for specifying the quantity.
- **Textarea**: Used for entering delivery instructions or comments.
- **Select Dropdown**: Used for selecting a payment method (Visa, MasterCard, GiftCard).
- **Radio Buttons**: Used for selecting a shipping method (Pick up or Delivery).


