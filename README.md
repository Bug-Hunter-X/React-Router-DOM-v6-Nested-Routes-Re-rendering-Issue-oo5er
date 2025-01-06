# React Router DOM v6 Nested Routes Re-rendering Issue

This repository demonstrates a subtle re-rendering issue in React Router DOM v6 when dealing with nested routes.  The parent route's component doesn't always re-render when navigating to a child route, leading to stale data or unexpected behavior.

## Problem

The `App` component contains nested routes. However, when navigating to a child route (e.g., `/users/1`), the parent component is not re-rendered, potentially causing issues with data updates or component state.