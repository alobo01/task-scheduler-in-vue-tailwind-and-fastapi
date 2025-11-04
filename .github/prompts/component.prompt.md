---
description: "Creates a new Vue 3 component with optional functionality and a corresponding Vitest test file."
mode: "agent"
tools: ["@workspace"]
---

Create a new Vue 3 single-file component named `${input:Component Name}` with the following context or functionality:
${input:Functionality (optional)}

Requirements:
- Use the `<script setup>` syntax.
- The component should at least render a `<div>` that includes its name (`${input:Component Name}`) or relevant content if functionality is provided.
- Save the component in `src/components/${input:Component Name}.vue`.

