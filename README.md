# Ordino Playwright

Playwright-based test automation framework for Ordino.ai application.

## Prerequisites

- Node.js (v18 or higher recommended)
- npm

## Installation

```bash
npm install
```

## Project Structure

```
ordino/
├── e2e/
│   ├── api/           # API tests
│   └── ui/            # UI tests
├── fixtures/          # Test fixtures
├── pages/             # Page Object Models
│   └── panels/        # Panel components
├── service/           # API service layer
│   ├── payloads/      # Request payloads
│   └── requests/      # API requests
└── test-data/         # Test data files
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run initialize` | Initialize the test framework |
| `npm run oi:run:test` | Run tests |
| `npm run oi:open:test` | Open tests in UI mode |
| `npm run oi:debug:test` | Debug tests |
| `npm run oi:open:report` | Open test report |

## Configuration

Test configuration is located in `ordino.config.ts`.

## License

MIT

