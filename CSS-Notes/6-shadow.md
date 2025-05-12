# 2 Types of Shadows

1. Text Shadow
2. Box Shadow

# Text Shadow

h1{
  text-shadow: horizontol-value, vartical-value, blur-value, color;
}

h1{
  text-shadow: 3px 3px 5px #000; 
}

# Box Shadow

div{
  box-shadow: horizontol-value, vartical-value, blur-value, shadow-size, color, inset/outset;
}

div{
  box-shadow: 10px 10px 10px 10px red inset;
}

# Key Notes:
- `text-shadow` supports max **4 values**: x-offset, y-offset, blur-radius, color (no spread or inset).
- `box-shadow` supports up to **6 values**: [inset] x-offset, y-offset, blur-radius, spread-radius, color.
