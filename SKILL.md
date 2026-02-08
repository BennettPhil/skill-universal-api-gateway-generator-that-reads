---
name: universal-api-gateway-generator-that-reads
description: Universal API gateway generator that reads any combination of REST, GraphQL, gRPC, and WebSocket API defini...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: Universal API gateway generator that reads any combination of REST, GraphQL, gRPC, and WebSocket API definitions and produces a unified gateway with rate limiting per endpoint, JWT validation with RBAC, request/response transformation, API versioning, circuit breakers, caching with invalidation strategies, request coalescing, schema stitching for GraphQL, and auto-generated SDKs in TypeScript, Python, Go, Rust, Swift, and Kotlin.

# Context
Must handle 100k+ RPS, support canary deployments, and include built-in A/B testing for API responses.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: script-heavy-builder description: A builder that generates Agent Skills composed of multiple composable shell scripts following Unix philosophy. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.