# Hotel Management System

This is a simple command-line based Hotel Management System implemented in C++. The program allows the management of various items available in a hotel, such as rooms, pasta, burgers, noodles, shakes, and chicken rolls. It enables users to make selections from a menu to book rooms or order food items, while also providing details of sales and collections.

## Features

- **Room Booking**: Users can book rooms by specifying the number of rooms they want. The program checks the availability of rooms and updates the sold rooms accordingly.
- **Food Ordering**: Users can order different food items like pasta, burgers, noodles, shakes, and chicken rolls. The program ensures that the ordered quantity does not exceed the available quantity for each item.
- **Sales and Collection Details**: The system provides details of sales and collections for each item, including the total quantity sold and the total revenue generated.

## Usage

1. **Compile the Code**: Compile the C++ code using any C++ compiler. For example:
   ```
   g++ main.cpp -o hotel_management
   ```

2. **Run the Program**: Execute the compiled program.
   ```
   ./hotel_management
   ```

3. **Input Quantities**: Input the initial quantities of available items, including rooms, pasta, burgers, noodles, shakes, and chicken rolls.

4. **Menu Selection**: Choose options from the menu to book rooms or order food items.

5. **View Sales and Collections**: Option 7 allows users to view details of sales and collections for each item.

6. **Exit**: Choose option 8 to exit the program.

## Menu Options

1. **Rooms**: Book rooms by specifying the number of rooms required.
2. **Pasta**: Order pasta by specifying the quantity.
3. **Burger**: Order burgers by specifying the quantity.
4. **Noodles**: Order noodles by specifying the quantity.
5. **Shake**: Order shakes by specifying the quantity.
6. **Chicken**: Order chicken rolls by specifying the quantity.
7. **Sales and Collections**: View details of sales and collections for each item.
8. **Exit**: Exit the program.

## Notes

- The prices of items are fixed (e.g., room price is $1200, pasta price is $150, etc.).
- The program ensures that the quantity ordered does not exceed the available quantity for each item.

## Future Enhancements

- Implement user authentication and authorization for better security.
- Add functionality for modifying item quantities and prices dynamically.
- Improve error handling and input validation to enhance user experience.

Feel free to contribute to this project by suggesting enhancements or reporting issues.

---

This README provides comprehensive information about the Hotel Management System, including its features, usage instructions, menu options, and potential future enhancements. It aims to help users understand and utilize the system effectively.
