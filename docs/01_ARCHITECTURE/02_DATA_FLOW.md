# Data Flow

1. External services synchronize through the Integration Layer.
2. Data is normalized and stored in the local database.
3. Search indexes are updated.
4. The AI Engine consumes indexed data to generate recommendations.
5. The UI presents information and awaits explicit user actions.

## Principles
- Local-first processing
- Incremental synchronization
- Event-driven updates
- No autonomous execution without user approval