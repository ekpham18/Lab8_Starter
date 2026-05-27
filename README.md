# Lab8-Starter
Ethan Pham  
https://ekpham18.github.io/Lab8_Starter/  
Graceful degradation and service workers are related in the sense that service workers help implement graceful degradation. Service workers are able to store data/info that's normally fetched from online within a cache, so that when the website asks for it again, we're able to access the cached data with no online connection needed. In the context of graceful degradation, this helps our website maintain limited functionality instead of falling completely apart when something fails (in this case, network connection).