## TypeScript Client Example for OpenAI Chat Completions API

Run the example (requires Bun):

```bash
./main.ts
```

Add just the `ChatCompletion` and its dependent DTOs:

```bash
npx get-dtos typescript https://localhost:5001 --include "ChatCompletion.*"
```

Alternatively, add all DTOs:

```bash
npx get-dtos typescript https://localhost:5001
```

Update DTOs:

```bash
npx get-dtos typescript
```