User should...

- [ ] be able to see his notes
- [ ] be able to create a new note
- [ ] be able to delete a note
- [ ] be able to edit a note

1. Create dockerfile and docker-compose
2. Add github workflow
3. Install deps

```bash
npm install --save-dev @testing-library/react @testing-library/jest-dom vitest @testing-library/dom @types/react @types/react-dom cypress
```

4. Set up vitest.config

```js
import { defineConfig } from "vitest/config";

export default defineConfig({
  test: {
    globals: true,
    environment: "jsdom",
  },
});
```

5. Set up cypress
