# Oja Platform

> Building the future of AI-powered DeFi on Scroll

Oja is a comprehensive DeFi platform that combines AI-driven predictions, automated vault strategies, and autonomous NFT agents to create a next-generation financial ecosystem on Scroll.

## 🌟 Features

- **AI-Powered Prediction Markets**: Data-driven forecasting for market trends and events
- **Smart Vaults**: Automated yield optimization using AI for concentrated LP positions
- **Autonomous NFT Agents**: Starknet-native ERC-6551 implementation for self-managing digital assets
- **One-Click Deployments**: Permissionless deployment of DeFi primitives
- **Global Remittance Service**: Low-fee international transfers using stablecoins and MPC wallets with direct bank account integration

## 🏗 Architecture

The platform is built on a modular architecture with the following key components:

- **Frontend Layer**: Next.js 14 application with Typescript
- **Backend Services**: Node.js 
- **Smart Contracts**: smart contracts on Scroll
- **AI Layer**: Python-based prediction and optimization engines
- **Data Layer**: Distributed data storage and processing

## 🚀 Getting Started

### Prerequisites

- Node.js v18+
- Python 3.9+
- Docker and Docker Compose
- Starknet CLI
- Cairo v2.0.0

### Installation

1. Clone the repository:
```bash
git clone https://github.com/dayo-adewuyi/oja.git
cd oja
```

2. Install dependencies:
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install

# Install AI service dependencies
cd ../ai-service
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Start development environment:
```bash
docker-compose up -d
```

## 🔧 Development


### Running Tests

```bash
# Run frontend tests
cd frontend
npm test

# Run backend tests
cd backend
npm test

# Run contract tests
cd contracts
scarb test

# Run AI service tests
cd ai-service
pytest
```

### Development Workflow

1. Create a new branch for your feature
2. Make your changes
3. Write tests
4. Create a pull request
5. Wait for review and CI checks

## 📚 Documentation

- [API Documentation](./docs/api.md)
- [Smart Contract Documentation](./docs/contracts.md)
- [Architecture Overview](./docs/architecture.md)
- [Deployment Guide](./docs/deployment.md)

## 🛣 Roadmap

### Phase 1 - MVP (Current)
- Basic vault functionality
- Simple AI prediction models
- Core smart contracts
- Basic user interface

### Phase 2
- Advanced AI strategies
- Multiple vault types
- Enhanced risk management
- Extended analytics

### Phase 3
- Autonomous NFT agents
- Cross-chain integration
- Advanced governance
- Platform optimization

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

### Development Guidelines

- Follow TypeScript best practices
- Write comprehensive tests
- Document your code
- Follow our git commit conventions

## 🔐 Security


### Reporting Security Issues

Please report security vulnerabilities to security@oja.com




## 🌐 Links

- [Website](https://oja.com)
- [Documentation](https://docs.oja.com)
- [Discord](https://discord.gg/oja)
- [Twitter](https://twitter.com/oja)

## ⚠️ Disclaimer

This project is in active development. Use at your own risk.
