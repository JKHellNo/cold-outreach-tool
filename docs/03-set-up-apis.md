# Step 3: Set Up API Credentials

## OpenAI ChatGPT API
1. Get your API key at: https://platform.openai.com/account/api-keys
2. Go to n8n > Credentials > Add new > HTTP Request
3. Use this header:
   ```
   Authorization: Bearer YOUR_API_KEY
   ```

## Google Sheets
1. Set up OAuth client:
   https://console.cloud.google.com/apis/credentials
2. Add Google Sheets credentials in n8n

(Repeat for PhantomBuster, Apollo, etc.)

![API Keys Example](images/api-keys-example.png)
