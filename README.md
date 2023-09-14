### LMS Frontend

### Setup instruction

1. Clone the project

```
git clone https://github.com/Raj5488/LMS__PROJECT
```
2. Move into the directory

```
cd lms-fronted```

3. install dependicies

```
npm i
```

4. run the server
```
npm run dev
```

### Setup instructions for tailwind

[Tail wind offical instruction doc (https://tailwindcss.com/docs/installation)]

1. Install tailwindcss

```
npm install -D tailwindcss
```

2. Create Tailwind config file
```
npx tailwindcss init
```

3. Add file extension to tailwind config file
```
"./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directive at the top of the `index.css` file

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Adding plugins and dependencies

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```