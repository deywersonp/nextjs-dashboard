## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## How Data Fetching Works on this Next.js Version

The functions wrote at `lib/data.ts` file are called on server side. It's something like the page that call the function is the "api route", where the first processing occurs at build time, and complementary processing, like when query changes, occurs on client side, but all the code to build the response is cooked on server side.

## Suspense component & Loading.tsx pages

Suspense/Loading.tsx works like an `isLoading` state, where a the fallback component is show when we encapsulate a component with `Suspense` from `react`.
