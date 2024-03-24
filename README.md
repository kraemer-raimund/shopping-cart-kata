# Shopping Cart Kata

A coding kata that focuses on domain modelling and TDD.

## Domain Model

You're implementing a web shop. Through conversation with the client and domain experts, you discovered the following facts:

- A product can be added to the shopping cart at a certain quantity (1 or more at once).
- A product's quantity can be changed if it is already in the shopping cart.
- Changing a product's quantity to 0 removes it from the shopping cart.
- A product can be removed from the shopping cart; regardless of the quantity it will be removed completely as if the quantity were changed to 0.
- Adding a product that already exists in the shopping cart increases the quantity by the respective amount.
- The shopping cart provides a (read-only) representation of its contents (e.g., for displaying in the UI), in the order in which the items were added.
- The shopping cart has a total price (in Euros), which is the sum of the items in the shopping cart.
- Retrieving the shopping cart (from whichever persistence mechanism is used) fetches the current prices of the items in the shopping cart in the desired currency (let's assume only Euros for now).

## Constraints

- Use TDD to drive the design.
- Focus on the domain model for this exercise. Make reasonable assumptions about persistence and presentation to allow framework-independent modelling of the domain.

## Next Steps

Looking for a challenge? Try these:

- Implement the functionality in reasonable slices. These may not be released to the users yet, but they should be potentially usable and releasable.
- Commit or amend on green tests. Integrate into the main branch after each slice of functionality (or earlier, if possible).<br/>
  Tip: If you can't push to a remote (e.g., you're offline or don't have permissions), create a local branch `origin/main` separate from your `main` branch and pretend like it's a remote branch.
- Support multiple currencies (e.g., USD, CHF, GBP) in addition to Euros.
- Support invoicing with and without VAT.

___

© 2024 Raimund Krämer - Use with attribution.

Links to third party sites are included for convenience only and I am not responsible for their contents.
