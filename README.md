# Visualize Git, Minimize Mistakes

**GitKraken**

### 🧰 Install on WSL (Ubuntu) using Snap:

```bash
sudo snap install gitkraken --classic
```

### 🚀 Launch GitKraken:

```bash
gitkraken &
```

> 💡 Make sure your WSL supports GUI apps (e.g. WSLg on Windows 11). If not, you'll need to configure an X server (like X410 or VcXsrv).

---

## 📌 Git Workflow Guidelines

Quy trình quản lý và cộng tác trên GitHub để đảm bảo dự án luôn rõ ràng, sạch sẽ và dễ bảo trì.

### 🗂️ Quản lý các nhánh (Branches)

* **`main` / `master`**: Nhánh chính, luôn ở trạng thái deployable (có thể triển khai).
* **`dev`**: Nhánh phát triển chính, nơi tổng hợp các tính năng đã được kiểm thử.
* **`feature/ten-tinh-nang`**: Thêm tính năng mới.
* **`bugfix/ten-loi`**: Sửa lỗi (bug fix).
* **`refactor/ten-thanh-phan`**: Cải tổ lại mã nguồn, không làm thay đổi hành vi.
* **`docs/update-readme`**: Cập nhật tài liệu như README.md.

> 💡 Dùng lệnh `git checkout -b feature/my-feature` để tạo và chuyển sang nhánh mới.

### 🛠️ Commit Convention (Quy ước commit)

Sử dụng cấu trúc commit rõ ràng theo [Conventional Commits](https://www.conventionalcommits.org):

```bash
<type>: <short description>
```

Một số `type` phổ biến:

* `feat`: thêm tính năng
* `fix`: sửa lỗi
* `refactor`: cải tổ code
* `docs`: cập nhật tài liệu
* `chore`: các công việc phụ, không ảnh hưởng logic
* `style`: thay đổi về style (formatting, space, v.v.)
* `test`: thêm hoặc cập nhật test

Ví dụ:

```bash
feat: add dark mode toggle
fix: prevent crash on invalid input
docs: update usage section in README
refactor: simplify user validation logic
```

### 📄 Cập nhật README

Tạo nhánh riêng cho việc cập nhật tài liệu:

```bash
git checkout -b docs/update-readme
```

Thực hiện cập nhật README và commit:

```bash
docs: update installation steps in README
```

### 🚀 Thêm tính năng (Feature)

```bash
git checkout -b feature/new-login-flow
```

Commit code như sau:

```bash
feat: implement new login flow with validation
```

### 🐛 Sửa lỗi (Bug fix)

```bash
git checkout -b bugfix/fix-navbar-overlap
```

```bash
fix: fix navbar overlap issue on mobile
```

### 🧹 Refactor code

```bash
git checkout -b refactor/clean-auth-module
```

```bash
refactor: extract auth logic into separate hook
```


---
## 🧪 Next.js Project

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

### 🔧 Getting Started

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser to view the app.

Start editing by modifying `app/page.tsx`. The page updates automatically as you save changes.

> ✨ Fonts are optimized using [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) with [Geist](https://vercel.com/font), a modern font by Vercel.

---

### 📚 Learn More

* [Next.js Documentation](https://nextjs.org/docs) — Features and API reference.
* [Learn Next.js](https://nextjs.org/learn) — Interactive tutorial for beginners.
* [Next.js GitHub](https://github.com/vercel/next.js) — Feedback and contributions welcome!

---

### 🚀 Deploy on Vercel

The easiest way to deploy your Next.js app is via [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme), the creators of Next.js.

See the [deployment guide](https://nextjs.org/docs/app/building-your-application/deploying) for details.

---

Nếu bạn muốn mình dịch ra tiếng Việt hoặc thêm phần cấu hình Git trong GitKraken, mình cũng có thể giúp.

