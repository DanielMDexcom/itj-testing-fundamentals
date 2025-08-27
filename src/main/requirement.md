Bootcamp Project – ShoppingCart 🛒

Objective
Extend the ShoppingCart from Phase 1 by adding business rules, discounts, checkout, and persistence while keeping the code testable with TDD, AAA, and FIRST.

Requirements

Cart Management
- A new cart starts empty
- Add products with name and price
- Remove products from the cart
- Empty the cart
- Return number of items and subtotal

Discounts
- 10% off if subtotal > 200
- 20% off if subtotal > 300
- 30% off all orders in winter
- 50% off orders > 500 in summer
- Discounts can be combined (subtotal + seasonal)

Checkout
- Calculate final total after discounts
- Process payment through a payment service (fake/test double)
- Return the final charged amount

Persistence
- Save the cart for later use
- Reload a previously saved cart
- Use in-memory storage (Fake Repository)

Deliverables
- Updated ShoppingCart with discounts, checkout, persistence
- DiscountCalculator for applying rules
- FakePaymentGateway for checkout
- FakeCartRepository for saving/loading
- Tests that follow AAA, FIRST, and TDD (Red → Green → Refactor)

Evaluation
- Discounts applied correctly according to rules
- Cart can be saved and reloaded
- Tests are fast, independent, and reliable
- Code design follows SOLID and DIP
