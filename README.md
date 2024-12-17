# React Router v6 404 Not Found Error Handling

This repository demonstrates a common issue encountered when using React Router v6: how to properly handle 404 (Not Found) errors.  The example shows an initial implementation that crashes on an invalid route and then provides a corrected version that gracefully renders a 404 page.

## Problem

In React Router v6, if a user navigates to a route that does not exist, the application may crash or throw an error. This is less than ideal for a user experience. 

## Solution

The solution involves using the `useNavigate` hook and a catch-all route with path `*` to render a custom 404 component.