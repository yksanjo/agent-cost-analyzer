# agent-cost-analyzer-api

> Package 2: api for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-api
```

## Usage

```javascript
import { AgentCostAnalyzerApi } from '@agent-cost-analyzer/agent-cost-analyzer-api';

const service = new AgentCostAnalyzerApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
