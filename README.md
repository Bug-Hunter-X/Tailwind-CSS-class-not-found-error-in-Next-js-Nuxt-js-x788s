# Tailwind CSS Class Not Found Error in Next.js/Nuxt.js

This repository demonstrates a common error encountered when using Tailwind CSS with Next.js or Nuxt.js: a class not found error.  This error occurs when a Tailwind CSS utility class or a custom class is not included in the final CSS output file.  This is frequently due to a build optimization that removes unused styles.

## Bug

The `bug.js` file shows the code causing the issue. The key is to identify which class is missing, and then review build optimizations and purge configurations to ensure the class gets included in your final CSS.