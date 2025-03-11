# הבלוג שלי

בלוג אישי מבוסס Next.js 15 עם תמיכה ב-MDX וקטעי קוד.

## תכונות

- 🚀 מבוסס על Next.js 15
- 📝 תמיכה ב-MDX לכתיבת תוכן
- 💻 הדגשת תחביר לקטעי קוד
- 🎨 עיצוב מודרני עם Tailwind CSS
- 📱 תצוגה רספונסיבית
- ⚡ Static Site Generation (SSG)

## התקנה

```bash
# התקנת תלויות
npm install

# הרצת שרת פיתוח
npm run dev

# בניית גרסת ייצור
npm run build

# הרצת גרסת ייצור
npm run start
```

## כתיבת פוסטים

1. צור קובץ MDX חדש בתיקיית `src/app/blog/[slug]/page.mdx`
2. הוסף frontmatter בראש הקובץ:
   ```yaml
   ---
   title: 'כותרת הפוסט'
   date: 'YYYY-MM-DD'
   description: 'תיאור קצר של הפוסט'
   ---
   ```
3. כתוב את תוכן הפוסט ב-MDX
4. הוסף קטעי קוד עם הדגשת תחביר:
   ````markdown
   ```python
   def example():
       return "Hello, World!"
   ```
   ````

## רישיון

MIT

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
