npm init -y -> creates a package.json file
npm i -D tailwindcss -> installs Tailwind
npx -> globally
npx tailwindcss init -> creates a tailwindcss config file
npm run build | npm run watch

@layer base {
    h1 {
        font-size: 3rem; | @apply text-3xl
    }
}
@layer components{
    .btn-blue{
        @apply 
    }
}