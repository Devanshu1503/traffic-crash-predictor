This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

### Setup Python Environment (1st time setup only)

1. Create a virtual environment (make sure you are in the FastAPI folder in terminal):

    - On Windows:
        ```windows powershell
        python -m venv venv
        ```
    - On macOS/Linux:
        ```bash
        python3.11 -m venv venv
        ```

2. Activate the virtual environment:

    - On Windows:
        ```bash
        ./venv/Scripts/activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

3. Install the required Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Now run the FastAPI server:
    - uvicorn app:app --reload (It will be running on http://127.0.0.1:8000)

Note that if you have already completed these steps for initial setup, proceed every time with step 2-4,
activating venv, checking that dependencies are up to date, and proceed with starting FastAPI server.

### Dependencies

1. Ensure you install all dependencies with npm install

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!
