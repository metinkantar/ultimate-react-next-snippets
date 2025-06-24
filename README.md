# Ultimate React & Next.js Snippets

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/YOUR_PUBLISHER.YOUR_EXTENSION_NAME?style=for-the-badge&label=VS%20Marketplace)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/YOUR_PUBLISHER.YOUR_EXTENSION_NAME?style=for-the-badge)

The definitive snippet pack for modern React, Next.js App Router, and Pages Router development. This extension provides a comprehensive collection of code snippets to boost your productivity.

## Features

This extension provides snippets for:
-   **React:** Core hooks and component patterns (Functional, Arrow, Class).
-   **Next.js App Router:** Pages, layouts, API routes, middleware, loading/error UIs, and file-based metadata.
-   **Next.js Pages Router:** Classic pages, API routes, `getStaticProps`, `getServerSideProps`, `getStaticPaths`, `_app`, and `_document`.
-   **Helpers:** Common console commands.

## Installation

1.  Open **VS Code**.
2.  Go to **Extensions** (`Ctrl+Shift+X`).
3.  Search for `Ultimate React & Next.js Snippets`.
4.  Click **Install**.

---

## Available Snippets

All prefixes are designed to be intuitive and easy to remember. Most component snippets will automatically use the current filename as the component name.

### React: Core Components & Hooks

| Prefix | Description |
| :--- | :--- |
| `rafce` | Creates a React Arrow Function Component with an export. |
| `rfc` | Creates a React Functional Component. |
| `useStateSnippet` | Creates a React useState hook. |
| `useEffectSnippet` | Creates a React useEffect hook. |
| `useContextSnippet` | Creates a React useContext hook. |
| `useRefSnippet` | Creates a React useRef hook. |

### Next.js: App Router

| Prefix | Description |
| :--- | :--- |
| `nUseClient` | Adds the \"use client\"; directive. |
| `nUseServer` | Adds the \"use server\"; directive. |
| `nPage` | Creates a basic Page Component for the App Router. |
| `nPageDynamic` | Creates a Dynamic Page Component with params. |
| `nLayout` | Creates a Root Layout Component for the App Router. |
| `nLoading` | Creates a Loading UI for a route segment. |
| `nError` | Creates an Error Boundary for a route segment. |
| `nNotFound` | Creates a Not Found UI for a route segment. |
| `nGlobalNotFound` | Creates a root not-found.js file. |
| `nTemplate` | Creates a Template component. |
| `nApiGet` | Creates a GET API Route Handler. |
| `nApiPost` | Creates a POST API Route Handler. |
| `nMetadataStatic` | Creates a static metadata object. |
| `nMetadataDynamic` | Creates a dynamic `generateMetadata` function. |
| `nStaticParams` | Creates `generateStaticParams` to statically generate routes. |
| `nMiddleware` | Creates a middleware function. |
| `nLink` | Creates a Next.js Link component. |
| `nImage` | Creates a Next.js Image component. |
| `nScript` | Creates a Next.js Script component. |

### Next.js: Pages Router

| Prefix | Description |
| :--- | :--- |
| `nPagesPage` | Creates a Pages Router Page Component. |
| `nGetStaticProps` | Creates a `getStaticProps` function. |
| `nGetServerSideProps`| Creates a `getServerSideProps` function. |
| `nGetStaticPaths` | Creates a `getStaticPaths` function. |
| `nPagesApi` | Creates a Pages Router API route. |
| `nApp` | Creates a custom App component (`_app.tsx`). |
| `nDocument` | Creates a custom Document component (`_document.tsx`). |

### Helpers & Console

| Prefix | Description |
| :--- | :--- |
| `clg` | `console.log()` |
| `clo` | Logs a variable with its name as a string. |
| `cer` | `console.error()` |
| `cwa` | `console.warn()` |

## Contributing

Found a bug or have a suggestion? Please [open an issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) on GitHub.

## License

This extension is licensed under the MIT License.