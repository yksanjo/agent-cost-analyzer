# agent-cost-analyzer-database

> Integration: database for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-database
```

## Usage

```javascript
import { AgentCostAnalyzerDatabase } from '@agent-cost-analyzer/agent-cost-analyzer-database';

const service = new AgentCostAnalyzerDatabase();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
