# agent-cost-analyzer-webhook

> Integration: webhook for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-webhook
```

## Usage

```javascript
import { AgentCostAnalyzerWebhook } from '@agent-cost-analyzer/agent-cost-analyzer-webhook';

const service = new AgentCostAnalyzerWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
