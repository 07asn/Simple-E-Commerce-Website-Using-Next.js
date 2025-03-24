
---

## 📦 Technologies Used

- **Next.js 13+ App Router**
- **Tailwind CSS**
- **Axios**
- **Fakestore API (https://fakestoreapi.com/)**
- **JavaScript (no TypeScript)**

---

## 📡 Data Fetching Strategies

| Page                        | Strategy         | Description                                     |
|----------------------------|------------------|-------------------------------------------------|
| `/` (Home)                 | SSG              | Static content rendered at build time           |
| `/about`                  | SSG              | Static content with Next.js Image               |
| `/products`               | ISR or SSR       | Periodic data update or fresh on every request  |
| `/products/[id]`          | SSG or SSR       | Pre-rendered per product or forced SSR          |

---

## 🔧 Setup Instructions

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/my-ecommerce.git
cd my-ecommerce
npm i
npm run dev