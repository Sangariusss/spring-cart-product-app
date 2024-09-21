# Spring Cart Product App

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributions](#contributions)
- [License](#license)

## Overview
This project is a Java application that demonstrates basic operations for managing products and a shopping cart using the Spring framework (without Spring Boot). It showcases how to implement services, repositories, and data management in a structured way, focusing on product handling and cart functionality.

### Features
- **Product Management**: Create, retrieve, update, and delete products.
- **Cart Functionality**: Add and remove products from the shopping cart, track quantities, and calculate totals.
- **Data Management**: Utilizes Spring's dependency injection for service and repository management.

## Usage
1. **Setup and Deployment**:
    - Clone the repository to your local machine.
    - Build the application using your preferred build tool (e.g., Maven or Gradle).

2. **Running the Application**:
    - Create a `main` method in your application to run the context and invoke the desired services.

3. **Interacting with the Application**:
    - Use the provided services to manage products and cart operations programmatically.

## File Structure
- `src/main/java/com/sangarius/springcartproductapp/`: Java source files for services and models.
    - `ProductService.java`: Interface for managing products.
    - `ProductServiceImpl.java`: Implementation of the product service.
    - `CartService.java`: Interface for cart functionality.
    - `CartServiceImpl.java`: Implementation of the cart service.
    - `Product.java`: Model class representing product data.
    - `Cart.java`: Model class representing the shopping cart.

- `src/test/java/com/sangarius/springcartproductapp/`: Test files for services and functionality.

## Contributions
Contributions, feedback, and suggestions are welcome. If you have any improvements or find issues, please submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.