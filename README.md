# Computer Parts Inventory Management System

## Assignment Requirements Implementation

### C. Customized User Interface
- **Files**: All HTML templates in `/templates/`
- **Changes**: Customized for computer parts store with proper navigation

### D. About Page
- **File**: `about.html` (line 1)
- **Changes**: Added About page with company description and navigation

### E. Sample Inventory
- **File**: `PartController.java` (line 35-95)
- **Changes**: Added 5 parts and 5 products when database is empty

### F. Buy Now Button
- **File**: `products.html` (line 32-34)
- **Changes**: Added Buy Now button that decrements product inventory

### G. Max/Min Inventory Tracking
- **File**: `Part.java` (lines 12-13)
- **Changes**: Added minInventory and maxInventory fields with validation

### H. Inventory Validation
- **File**: `PartController.java` (lines 108-118)
- **Changes**: Added validation for inventory range with error messages

### I. Unit Tests
- **File**: `PartTest.java` (all tests)
- **Changes**: Added 5 unit tests for inventory validation

### J. Clean Code
- **Note**: No unused validators were created in this implementation

## How to Run
1. Clone the repository
2. Run `mvn spring-boot:run`
3. Access at `http://localhost:8080`
4. H2 Console: `http://localhost:8080/h2-console`

## Default Sample Data
The application automatically loads 5 computer parts and 5 products on first run.
