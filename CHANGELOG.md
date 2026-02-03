## 0.1.3

Fix overflow issue, improve alignment, and add logo animation

- **Fixed**: RenderFlex overflow error (4.0 pixels on the right) by using `MainAxisSize.max` and `Expanded` widgets
- **Enhanced**: All sidebar items now align to the extreme left with `MainAxisAlignment.start`
- **Added**: Smooth animated logo transition with scale and fade effect when switching between main and small logos
- **Improved**: Better text overflow handling with proper flex constraints

## 0.1.2

Responsiveness

## 0.1.1

Add dual logo support with optional small logo for collapsed sidebar state.

New optional properties:
- `smallLogoImage`: Logo displayed when sidebar is collapsed
- `smallLogoWidth`: Width for small logo
- `smallLogoHeight`: Height for small logo

Fully backwards compatible - existing implementations continue working without changes.

## 0.1.0

Improve scrolling

## 0.0.3

Timer removed to make it one time animation for better performance.