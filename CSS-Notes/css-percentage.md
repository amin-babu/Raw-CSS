# CSS Percentage Behavior

## 1. Padding & Margin (%)
- Percentages are based on the **parent element’s width**.
- ✅ Even vertical sides (top/bottom) use the **parent's width**.
- Example: Parent width = 400px, `padding: 10%` → all sides = 40px.

## 2. position: relative (%)
- `top` / `bottom` → % is based on the element’s **own height**.
- `left` / `right` → % is based on the element’s **own width**.
- Example: Element height = 300px, `top: 10%` → move down by 30px.

## 3. position: absolute (%)
- % is based on the **parent (or nearest positioned ancestor)**.
- `top` / `bottom` → % of **parent’s height**.
- `left` / `right` → % of **parent’s width**.
- Example: Parent height = 300px, `top: 10%` → move down by 30px.

## 4. width: %
- Always based on the **parent's width**.

## 5. height: %
- Based on the **parent's height**, but only works if the parent has an explicit height.

