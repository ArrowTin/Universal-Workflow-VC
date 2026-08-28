# OPTIMIZATION GUIDELINES ADAPTATION GUIDANCE

**Purpose:** Guide Layer 2 generation for adapting optimization/ guidelines from Layer 1

## Overview

Layer 1 `optimization/` directory contains optimization guidelines that should be adapted to Layer 2 based on project budget, scale, and performance requirements.

## Optimization Guidelines Mapping

### 1. CACHE.md → docs/operating/CACHE.md (or integrated)

**When to adapt:** Projects with performance or cost optimization needs

**What to include:**
- Caching strategy
- Cache invalidation policies
- Cache hierarchy
- Cache monitoring

**Project-specific customization:**
- Define cacheable operations
- Set cache TTL policies
- Define cache hierarchy for project
- Set cache monitoring requirements

### 2. COST.md → docs/operating/COST.md (or integrated)

**When to adapt:** Projects with budget constraints or AI usage

**What to include:**
- Cost tracking requirements
- Cost optimization strategies
- Budget monitoring
- Cost allocation

**Project-specific customization:**
- Define cost categories
- Set budget thresholds
- Define cost optimization priorities
- Set monitoring frequency

### 3. TOKENS.md → docs/operating/TOKENS.md (or integrated)

**When to adapt:** Projects using AI models with token costs

**What to include:**
- Token optimization strategies
- Context compression techniques
- Model selection criteria
- Token monitoring

**Project-specific customization:**
- Define token budgets per operation
- Set compression strategies
- Define model selection criteria
- Set token monitoring requirements

## Adaptation Process

```text
ASSESS OPTIMIZATION NEEDS
→ CONSIDER BUDGET CONSTRAINTS
→ EVALUATE PERFORMANCE REQUIREMENTS
→ SELECT RELEVANT OPTIMIZATION GUIDELINES
→ CUSTOMIZE FOR PROJECT CONTEXT
→ INTEGRATE INTO LAYER 2 DOCUMENTS
```

## Minimal Adaptation

For simple projects, minimal optimization guidelines adaptation:
- COST.md → Only if using paid services (AI, cloud, etc.)
- TOKENS.md → Only if using AI models with token costs
- CACHE.md → Only if performance is critical

## Budget-Based Adaptation

**Low budget projects:**
- Strong cost optimization
- Aggressive token optimization
- Basic caching for cost reduction

**Medium budget projects:**
- Moderate cost monitoring
- Balanced token usage
- Strategic caching

**High budget projects:**
- Cost tracking for visibility
- Token optimization for efficiency
- Performance-focused caching

## Performance-Based Adaptation

**Performance-critical projects:**
- Comprehensive caching strategy
- Token optimization for speed
- Performance monitoring

**Standard performance projects:**
- Strategic caching
- Basic token optimization
- Cost-effective performance

**Performance-flexible projects:**
- On-demand caching
- Token optimization as needed
- Cost-focused over performance

## Best Practices

1. **Budget awareness** - Match optimization to available budget
2. **Performance requirements** - Balance cost vs performance
3. **Measurement first** - Establish baselines before optimization
4. **Incremental optimization** - Optimize incrementally based on data
5. **Automation** - Automate monitoring and alerting where possible

## AI-Specific Optimization

For projects using AI models:

**Token optimization strategies:**
- Context compression
- Prompt engineering
- Model selection (cheaper when sufficient)
- Batch processing
- Caching AI responses

**Cost monitoring:**
- Per-operation token tracking
- Model-specific cost analysis
- Budget alerts
- Cost attribution

## Integration Approaches

**Option 1: Separate optimization documents**
- Create docs/operating/CACHE.md, COST.md, TOKENS.md
- Best for complex optimization needs

**Option 2: Integrated into existing documents**
- Add optimization sections to relevant docs
- Best for simple optimization needs

**Option 3: Combined optimization document**
- Create docs/OPTIMIZATION.md covering all aspects
- Best when multiple optimization aspects are needed