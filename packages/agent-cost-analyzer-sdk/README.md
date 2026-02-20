# agent-cost-analyzer-sdk

> Package 3: sdk for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-sdk
```

## Usage

```javascript
import { AgentCostAnalyzerSdk } from '@agent-cost-analyzer/agent-cost-analyzer-sdk';

const service = new AgentCostAnalyzerSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
