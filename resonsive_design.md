## Responsive design ingredients:
1. Fluid layout:
   - to allow the current website to adapt to current viewport (width and height).
   - use %, or vw, wh instead of px for elements that needs to be flexible and adaptable to viewport.
   - Use max-width instead of width.
2. Responsive units:
   - Use rem unit instead of px for most lengths.
   - To make it easy to scale the entire layout down automatically.
   - Helpful trick: setting 1 rem to 10px for easy calculations.
3. Flexible images:
   - By default, images don't scale automatically, so we need to fix that.
   - Always use % for image dimensions, together with the max-width property.
4. Media queries:
   - To change css styles on certain viewport widths (breakpoints)