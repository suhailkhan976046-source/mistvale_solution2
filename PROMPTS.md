# AI-Assisted Workflow — Mistvale Tea Co.

## Prompt 1 — Code Review

Review the provided single-page tea store HTML, CSS and JavaScript.

Identify potential issues related to:
- shopping cart
- product quantity limits
- coupon calculation
- shipping calculation
- search
- category filtering
- sorting
- sold-out products
- pincode validation
- accessibility
- responsive design

Do not modify product IDs, names, prices, or the protected API block.

---

## Prompt 2 — Business Rule Verification

Review the shopping cart logic and verify these business rules:

- Maximum quantity is 5 or available stock, whichever is lower.
- WELCOME10 gives 10% discount.
- Maximum coupon discount is ₹150.
- Minimum cart value for coupon is ₹399.
- Gift products are not eligible for the coupon.
- Free shipping applies at ₹599 or above after discount.
- Shipping below the threshold is ₹49.
- Sold-out products cannot be added.

Explain any issue found and suggest a minimal code fix without changing protected product data or API logic.

---

## Prompt 3 — Responsive Review

Review the HTML and CSS for responsive behavior at:
- 360px
- 375px
- 390px
- 768px
- 1200px+

Check for:
- horizontal overflow
- buttons going outside the viewport
- product card layout
- form layout
- modal/dialog behavior
- navigation
- readable typography

Suggest minimal improvements where required.

---

## Prompt 4 — Accessibility Review

Review the page for basic web accessibility.

Check:
- semantic HTML
- image alt text
- button labels
- keyboard navigation
- visible focus states
- ARIA labels
- live regions
- form labels
- reduced-motion support

Suggest improvements without changing the protected API or product data.

---

## AI Usage Note

AI was used as a development and review assistant for code inspection, business-rule verification, responsive checks, accessibility review, and documentation.

Final behavior was manually tested in the browser before submission.