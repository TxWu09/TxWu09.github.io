---
title: "Translating Large-Scale C Repositories to Idiomatic Safe Rust"
collection: publications
category: conferences
permalink: /publication/2026-05-01-c-to-rust-translation
excerpt: 'A multi-stage pipeline for translating large-scale legacy C repositories into idiomatic, memory-safe Rust, validated with differential fuzzing against original C binaries.'
date: 2026-05-01
venue: 'Submitted to ICSE 2026'
citation: 'Tianran Sun, Saman Dehghan, Tianxiang Wu, Reyhaneh Jabbarvand. (2026). &quot;Translating Large-Scale C Repositories to Idiomatic Safe Rust.&quot; <i>Submitted to ICSE &#39;26</i>.'
---

This work presents an AST-level preprocessing pipeline that extracts control-flow graphs and call dependencies from legacy C repositories, normalizes architecture-specific macros and inline assembly, and feeds the result to a fine-tuned LLM translator. A tree-sitter rewriting engine converts pointer arithmetic into safe Rust iterator patterns using region-based alias analysis, and a differential fuzzing harness (built with cargo-fuzz) validates the translated Rust code against the original C binaries across thousands of randomly generated inputs to confirm behavioral equivalence and memory safety.
