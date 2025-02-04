# redis-playground

A hands-on experimental repository for mastering Redis through real-world implementations and pattern exploration.

## 🎯 Purpose

- Build practical Redis applications
- Test data structures and patterns
- Implement production-ready solutions
- Benchmark and optimize performance
- Document best practices

## 🗂️ Repository Structure

```
redis-playground/
├── projects/                # Real-world implementations
│   ├── analytics/          # Real-time analytics dashboard
│   ├── job-queue/          # Distributed task processing
│   ├── chat/               # Real-time messaging
│   └── cart/               # E-commerce shopping cart
├── patterns/               # Common Redis patterns
│   ├── caching/           # Caching strategies
│   ├── rate-limiting/     # Rate limiters
│   ├── session/           # Session management
│   └── pub-sub/           # Pub/Sub implementations
├── data-structures/        # Data structure examples
│   ├── strings/
│   ├── lists/
│   ├── sets/
│   ├── sorted-sets/
│   └── hashes/
├── docker/                # Environment setup
├── scripts/               # Utility scripts
└── docs/                  # Documentation
```

## 🚀 Real-World Projects

### 1. Real-time Analytics Dashboard
- User activity tracking with HyperLogLog
- Content popularity using Sorted Sets
- Real-time metrics with Pub/Sub
- Dashboard using WebSocket

### 2. Job Queue System
- Priority queues with Lists
- Job status tracking with Hashes
- Failed job handling
- Worker scaling demos

### 3. Chat Application
- Message queuing
- Presence detection
- Read receipts
- History management

### 4. Shopping Cart
- Session management
- Inventory tracking
- Cart operations
- Checkout process

## 🔧 Getting Started

1. Setup environment:
```bash
git clone https://github.com/pesnik/redis-playground.git
cd redis-playground
docker-compose up -d
```

2. Run examples:
```bash
# Start analytics dashboard
cd projects/analytics
python run.py

# Test job queue
cd projects/job-queue
./test-queue.sh
```

## 📊 Implementation Details

Each project includes:
- Source code with comments
- API documentation
- Load testing scripts
- Performance benchmarks
- Scaling guidelines

## 🧪 Testing & Benchmarking

```bash
# Run all tests
./scripts/test-all.sh

# Benchmark specific project
./scripts/benchmark.sh projects/chat

# Load test
./scripts/load-test.sh projects/analytics
```

## 📝 Pattern Examples

1. **Caching**
   - LRU implementation
   - Cache invalidation
   - Cache-aside pattern

2. **Rate Limiting**
   - Fixed window counter
   - Sliding window
   - Token bucket

3. **Session Management**
   - Token storage
   - User presence
   - Session cleanup

## 🔍 Performance Tips

- Memory usage optimization
- Pipelining examples
- Transaction handling
- Connection pooling
- Error handling

## 🛠️ Tools & Utilities

- Redis CLI scripts
- Monitoring tools
- Backup utilities
- Performance analyzers

## 📚 Prerequisites

- Docker & Docker Compose
- Python 3.8+
- Redis CLI
- Optional: Redis Insight

## 📖 Documentation

Each component includes:
- Architecture overview
- Implementation details
- Best practices
- Common pitfalls
- Scaling strategies

## 📜 License

MIT License - See [LICENSE](LICENSE)

---

*This is a practical playground. All implementations are production-ready examples.*
