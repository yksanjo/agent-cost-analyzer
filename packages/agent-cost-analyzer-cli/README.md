# agent-cost-analyzer-cli

> Package 4: cli for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-cli
```

## Usage

```javascript
import { AgentCostAnalyzerCli } from '@agent-cost-analyzer/agent-cost-analyzer-cli';

const service = new AgentCostAnalyzerCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
