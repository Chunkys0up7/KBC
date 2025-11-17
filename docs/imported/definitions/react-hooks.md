---
title: React Hooks
type: definition
category: react
tags: [react, hooks, react-hooks, functional-components, state-management, react-features, frontend-development, javascript, web-development]
created: 2025-11-17
source: claude-conversation
---

# React Hooks

## Definition

React Hooks are functions that let you use state and other React features without writing a class component. Introduced in React 16.8, Hooks enable functional components to have access to React features that were previously only available in class components.

## Core Concept

Hooks allow you to "hook into" React state and lifecycle features from function components. They provide a more direct API to the React concepts you already know: props, state, context, refs, and lifecycle.

## Built-in Hooks

### State Hooks
- **useState** - Manages local component state
- **useReducer** - Manages complex state logic with a reducer function

### Effect Hooks
- **useEffect** - Performs side effects in function components (data fetching, subscriptions, DOM manipulation)
- **useLayoutEffect** - Similar to useEffect but fires synchronously after DOM mutations

### Context Hook
- **useContext** - Consumes context values without nesting

### Ref Hook
- **useRef** - Creates mutable references that persist across renders

### Performance Hooks
- **useMemo** - Memoizes expensive calculations
- **useCallback** - Memoizes callback functions

### Additional Hooks
- **useImperativeHandle** - Customizes instance value exposed to parent components
- **useDebugValue** - Displays custom labels in React DevTools
- **useDeferredValue** - Defers updating non-urgent parts of UI
- **useTransition** - Marks state updates as non-urgent transitions
- **useId** - Generates unique IDs for accessibility attributes

## Rules of Hooks

1. **Only call Hooks at the top level** - Don't call Hooks inside loops, conditions, or nested functions
2. **Only call Hooks from React functions** - Call them from functional components or custom Hooks, not regular JavaScript functions

## Benefits

- Reuse stateful logic without changing component hierarchy
- Split complex components into smaller functions
- Use React features without classes
- Better code organization and readability
- Easier to test and maintain

## Custom Hooks

You can create custom Hooks to extract component logic into reusable functions. Custom Hooks are JavaScript functions whose names start with "use" and may call other Hooks.

## Related Concepts

- Functional Components
- State Management
- Component Lifecycle
- React Context
- Component Composition
