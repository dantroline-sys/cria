This is really a very simple application but it works and is super useful. 

You open it in your browser, set it up to point at your llama.cpp instance, 
and start using it the same way as you would use the llama.cpp web interface.

The difference is that long context chats are auto-compacted for you, and if
you want there is also a basic RAG memory recall system that can either be 
keyword based if you are lazy like me, or via an embedding service which just
means you need another llama.cpp instance serving that tiny model. 

All the data is stored in the browser cache, so if you clear that, it's gone. 
You can export and import the chats and the RAG in case you want to save 
your best productions. 

No frills, see if you like it.
