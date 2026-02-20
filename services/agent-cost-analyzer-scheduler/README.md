# agent-cost-analyzer-scheduler

> Service: scheduler for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-scheduler
```

## Usage

```javascript
import { AgentCostAnalyzerScheduler } from '@agent-cost-analyzer/agent-cost-analyzer-scheduler';

const service = new AgentCostAnalyzerScheduler();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
