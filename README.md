# node-container
nodejs on a webpage



Active Render site for a nodejs web container


https://student-ai-hub-6cm0.onrender.com/


Main issue in render is to make the site cross origin


```
Scroll down to Headers and click Add Header for these two:

Path: /* | Name: Cross-Origin-Embedder-Policy | Value: require-corp

Path: /* | Name: Cross-Origin-Opener-Policy | Value: same-origin
```

