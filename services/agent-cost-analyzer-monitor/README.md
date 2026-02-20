# agent-cost-analyzer-monitor

> Service: monitor for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-monitor
```

## Usage

```javascript
import { AgentCostAnalyzerMonitor } from '@agent-cost-analyzer/agent-cost-analyzer-monitor';

const service = new AgentCostAnalyzerMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
