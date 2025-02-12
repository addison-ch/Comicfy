## 💭 Comicfy

Comicfy is a web applciation that turns any piece of text into a comic strip!

The front-end of our application was developed using React. Image generation and text analysis were done using Cohere and Wombo's APIs. We utilised multi-threading with Python in the backend to concurrently make API requests. We also built an algorithm to determine to most relevant sentences in a story. Our back-end is built using FastAPI (Python framework) to integrate everything together!

Our team of 4 ended up demo-ing this project at HTV 7, and although we didn't win (😢), we learned a whole lot about APIs, HTTP requests, and general software development!



## 💥 Try it yourself
1.  Clone and move into repository
```
 $ git clone https://github.com/addison-ch/Comicfy.git
 ```
2. Set up client

  ```
  cd client
  npm install
  npm start
  ```
3. Set up API keys (set in .env file in the server folder)
  ```
  WOMBO_KEY=YOURKEY
  COHERE_KEY=YOUROTHERKEY
  ```
4. Run the server
 
 ```
  cd server
  pip install -r requirements.txt
  python -m uvicorn main:app
  ```



## 💫 Screenshot
Example using an excerpt from HBO's House of the Dragon:
![screenshot](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/002/254/743/datas/gallery.jpg)
