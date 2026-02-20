# agent-cost-analyzer-connectors

> Package 5: connectors for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-connectors
```

## Usage

```javascript
import { AgentCostAnalyzerConnectors } from '@agent-cost-analyzer/agent-cost-analyzer-connectors';

const service = new AgentCostAnalyzerConnectors();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
