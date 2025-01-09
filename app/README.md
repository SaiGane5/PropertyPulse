# This the main application

## NextJS Reference Sheet

### Key Concepts

- **File-based Routing**: Pages are defined by files in the `pages` directory.
- **API Routes**: Create API endpoints by adding files to the `pages/api` directory.
- **Static Generation**: Pre-render pages at build time using `getStaticProps` and `getStaticPaths`.
- **Server-side Rendering**: Pre-render pages on each request using `getServerSideProps`.
- **Client-side Rendering**: Fetch data on the client side using React hooks like `useEffect`.
- **Dynamic Routing**: Create dynamic routes by using brackets in the file name, e.g., `[id].js`.
- **CSS and Styling**: Style components using CSS modules, styled-jsx, or any CSS-in-JS library.
- **API Integration**: Fetch data from external APIs using `fetch` or libraries like Axios.
- **Image Optimization**: Use the `next/image` component for automatic image optimization.
- **Internationalization (i18n)**: Built-in support for internationalized routing and translations.

### Useful Commands

- `npx create-next-app@latest` - Create a new Next.js application.
- `npm run dev` - Start the development server.
- `npm run build` - Create an optimized production build.
- `npm start` - Start the production server.
- `npm run export` - Export the app as static HTML.

### Useful Links

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js GitHub Repository](https://github.com/vercel/next.js)
- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)
- [Next.js Blog](https://nextjs.org/blog)

### Commonly Used Hooks

- `useRouter` - Access the router object to navigate programmatically.
- `useSWR` - Fetch data with caching and revalidation.

### Deployment

- **Vercel**: The recommended platform for deploying Next.js apps.
- **Other Platforms**: Can also deploy on platforms like Netlify, AWS, and more.

### Best Practices

- Keep components small and focused.
- Use environment variables for sensitive data.
- Optimize images and assets.
- Regularly update dependencies to keep the app secure.
