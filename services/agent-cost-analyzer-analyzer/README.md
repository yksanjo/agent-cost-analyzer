# agent-cost-analyzer-analyzer

> Service: analyzer for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-analyzer
```

## Usage

```javascript
import { AgentCostAnalyzerAnalyzer } from '@agent-cost-analyzer/agent-cost-analyzer-analyzer';

const service = new AgentCostAnalyzerAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
