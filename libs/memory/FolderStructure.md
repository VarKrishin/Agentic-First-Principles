libs/memory/
├── src/
│   ├── vector/
│   │   ├── interfaces.ts
│   │   ├── embedders/
│   │   │   ├── transformer.embedder.ts
│   │   │   └── openai.embedder.ts
│   │   └── stores/
│   │       ├── chroma.store.ts
│   │       └── pinecone.store.ts
│   │
│   ├── chunking/
│   │   ├── interfaces.ts
│   │   └── strategies/
│   │       ├── token.chunker.ts
│   │       ├── sentence.chunker.ts
│   │       └── paragraph.chunker.ts
│   │
│   ├── layers/
│   │   ├── interfaces.ts
│   │   ├── base.memory.ts
│   │   ├── core.memory.ts
│   │   ├── archive.memory.ts
│   │   └── recall.memory.ts
│   │
│   ├── stats/
│   │   ├── interfaces.ts
│   │   ├── memory.stats.ts
│   │   └── stats.collector.ts
│   │
│   ├── schemas/
│   │   ├── memory.schema.ts
│   │   ├── query.schema.ts
│   │   └── stats.schema.ts
│   │
│   └── index.ts
│
├── tests/
│   ├── vector/
│   ├── chunking/
│   ├── layers/
│   └── stats/
│
└── package.json