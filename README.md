Ini merupakan fork dari https://github.com/prasetyomimboro/restful-crud

Untuk memenuhi Tugas MK Pengujian dan Penjaminan Kualitas Software-GANJIL-2024/2025
MOCHAMMAD LUTHFI RAHMADI / Universitas Siber Muhammadiyah / 20220100106

This is a [Next.js](https://nextjs.org) project bootstrapped with [
`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Installation

1. Clone/Unzip Project files
2. Install Dependencies using npm
    ```bash
   npm ci 
    ```
3. migrate database (SQLite)
    ```bash
   npx prisma migrate deploy 
    ```
4. Generate Database Client
   ```bash
   npx prisma generate
   ```
5. Build Project
    ```bash
    npm run build
    ```
6. Start Project
    ```bash
    npm run start
    ```
7. Open Browser http://localhost:3000. this project is using swagger at entry point/root url
