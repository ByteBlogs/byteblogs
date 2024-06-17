# ByteBlogs

ByteBlogs uses theme from [Hyas](https://gethyas.com/) - [Doks](https://getdoks.org/)

This website is designed by [Pranav Dhawale](https://github.com/pranavdhawale) & [Gajanan More](https://github.com/gajanan-more)

## Live Website 🔗

- [byteblogs.github.io/byteblogs](https://byteblogs.github.io/byteblogs/)

<details>
<summary><h2>Documentation 📖</h2></summary>

```bash
git clone https://github.com/ByteBlogs/byteblogs.git
```

```bash
cd byteblogs/
npm install
```

</details>

<details>
<summary><h2>Project Commands 🧑‍💻</h2></summary>

### To start server

```bash
npm run dev
```

### To create new blog <span style="color: red">\*</span>

```bash
npm run create blog/blog_name/index.md
```

<span style="color:red">_Note:</span> Always stop the server to create new blog and Rebuild the project_

### To add cover image

```bash
byteblogs/
├── content/
│   └── blog/
│       └── blog_name/
│           ├── index.md
│           └── cover.png
```

The width of the cover image should be of the following **[480, 576, 768, 1025, 1200, 1440]**

### To rebuild project

```bash
npx shx rm -rf public resources .hugo_build.lock && npm run dev
```

</details>

