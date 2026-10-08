# Mistvale Tea Co. — Assessment Notes

## Project
Mistvale Tea Co. one-page tea store.

## Functional Testing Completed

The following functionality was tested in the browser:

- Product search
- Category filtering
- Product sorting
- Product quick view
- Add to cart
- Cart quantity controls
- Remove from cart
- Wishlist
- Sold-out product handling
- Coupon application
- Shipping calculation
- Checkout button
- Pincode delivery check
- Newsletter validation
- FAQ interaction

## Business Rules Tested

### Quantity
- Maximum quantity per product is limited to 5 or available stock, whichever is lower.

### Coupon
- Coupon code: WELCOME10
- Case-insensitive coupon entry tested.
- Minimum cart value: ₹399.
- Maximum discount: ₹150.
- Gift products are excluded from the coupon discount.

### Shipping
- Free shipping threshold: ₹599 after discount.
- Shipping charge below the threshold: ₹49.

### Sold Out
- Products with zero stock cannot be added to the cart.
- Sold-out products are shown with a Sold out state.

## Responsive Testing

The page was tested at mobile and desktop viewport sizes.

Tested mobile widths:
- 360px
- 375px
- 390px

No horizontal overflow was observed during testing.

## Accessibility Testing

Keyboard navigation and visible focus states were checked.

The page includes:
- Accessible labels
- Button labels
- Image alt text
- Keyboard-focus styles
- ARIA live regions for dynamic messages
- Reduced-motion support

## SEO / Metadata

The page contains:
- Title
- Meta description
- Canonical URL
- Open Graph metadata
- Twitter metadata
- Schema.org structured data

## Assets

The project contains:
- Hero banner
- SVG logo
- 8 product images

All existing asset filenames and product data references were preserved.

## Final Testing

The existing website was tested after the above checks and the main shopping flow was working correctly.