# structure-and-pointer

## 1. Project Description
This project demonstrates the use of **structures** and **pointers** in C++. It defines a `Time` structure to represent hours, minutes, and seconds, and shows how to manipulate its members using both direct access and pointer dereferencing.


## 2. Features
- Defines a `Time` structure with `hour`, `minute`, and `second` fields.  
- Uses a pointer to access and modify structure members.  
- Implements a helper function `printTime()` to display time values.  
- Demonstrates both **direct member access** and **pointer dereferencing**.  

## 3. Code Structure
- **Time struct:** Holds hour, minute, and second values.  
- **printTime function:** Prints a `Time` object in `hour : minute : second` format.  
- **Main function:**  
  - Declares `lunchTime` and `dinnerTime`.  
  - Initializes `dinnerTime` to `18:30:00`.  
  - Uses a pointer `ptrTime` to modify `lunchTime`.  
  - Prints both times.  


## 5. Expected Output

Lunch will be held at 12 : 30 : 20

Dinner will be held at 18 : 30 : 0
