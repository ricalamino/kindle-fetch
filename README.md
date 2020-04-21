# Get your kindle books back to you 

- Download the project and run `npm i`

- Enter https://ler.amazon.com.br (in English https://read.amazon.com/) and click to read your books. They will be downloaded.

- The books usually are in: C:\Users\<user>\AppData\Local\Google\Chrome\User Data\Default\databases\https_ler.amazon.com.br_0
so before running change in line 215 the location where the downloaded books are: 
`var KINDLE_DB = 'C:/Users/<user>/AppData/Local/Google/Chrome/User Data/Default/databases/https_ler.amazon.com.br_0/12';`

- Run the extractor: `node fetch_kindle.js`

- The generated books will be in TEMP folder: C:\Users\<user>\AppData\Local\Temp
