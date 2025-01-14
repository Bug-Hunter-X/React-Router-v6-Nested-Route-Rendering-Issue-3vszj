# React Router v6 Nested Route Bug

This repository demonstrates a common issue encountered when working with nested routes in React Router v6. The `Contact` component unexpectedly fails to render, even though the route appears correctly defined.

## Problem

The main App component uses nested routes. While the Home and About components render correctly, the Contact component fails to display. This happens despite no apparent errors in the console or build process.

## Solution

The provided solution highlights a potential cause of this issue and offers a correction.  Often, this arises from improper structuring of routes or conflicts with other routing logic (e.g., improper use of `useParams`, `useLocation`, etc.).  Review the solution to understand how route organization can impact rendering behavior.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.