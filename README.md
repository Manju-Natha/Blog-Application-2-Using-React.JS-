# Routing using react-router Part 3

# Concepts in Focus

API Calls Fetch Route Props Match BlogsList Example

# 1 . API Calls

In General we make API Calls inside componentDidMount(). So that it doesn’t
block render().

# 1.1 Fetch

fetch is a promise-based API which returns a response object. In the backend, we
use snake_case for naming conventions.

# 2. Route Props

When a component is rendered by the Route, some additional props are passed

match location history

# 2.1 Match

The match object contains the information about the path from which the
component is rendered.

- Navigating to Specific Blog
  - using Path Parameters
- Path Params
  - match
