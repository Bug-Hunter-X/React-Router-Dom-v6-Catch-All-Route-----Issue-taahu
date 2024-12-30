# React Router Dom v6 Catch All Route '*' Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router Dom v6.  The problem is that the catch-all route doesn't always correctly catch unmatched routes, leading to unexpected behavior.

## Problem

The `App.js` file shows a standard React Router v6 setup with a catch-all route for handling 404 errors. However, under certain circumstances (like a direct link to a nonexistent page), the catch-all route might not be triggered, resulting in an error or unexpected rendering.

## Solution

The `AppSolution.js` file provides a solution to this problem.  Instead of relying solely on the catch-all route,  a more robust approach uses nested routes and a component to handle 404 scenarios more reliably.