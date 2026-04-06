#### [Tusinski Dev] Color Names

# td-colors-names

A TypeScript library providing type-safe constant color names for CSS/X11 colors.

## Installation

```bash
npm install td-colors-names
```

## Usage

Import color constants and use them in your code:

```typescript
import { RED, BLUE, ALL_COLORS, Color } from 'td-colors-names';

// Use individual color constants
console.log(RED); // 'Red'
console.log(BLUE); // 'Blue'

// Check if a color is in the list
console.log(ALL_COLORS.includes('Green')); // true

// Use the Color type for type safety
const myColor: Color = 'Yellow';
```

## API

- **Color constants**: Each color is exported as a constant string, e.g., `RED = 'Red'`
- **ALL_COLORS**: An array containing all available color names
- **Color**: A TypeScript union type of all color names for type safety

## License

MIT