# agent-cost-analyzer-core

> Package 1: core for AI Cost Analyzer and Optimizer

## Installation

```bash
npm install @agent-cost-analyzer/agent-cost-analyzer-core
```

## Usage

```javascript
import { AgentCostAnalyzerCore } from '@agent-cost-analyzer/agent-cost-analyzer-core';

const service = new AgentCostAnalyzerCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
