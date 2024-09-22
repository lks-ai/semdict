# SemDict
A minimalistic semantic dictionary that acts as a fast temporary in-memory throw-away vector store for those hard to reach places in data.

Only one script. Uses a small Language Model for embedding your "keys". Script is properly commented and includes a unit test example.

Main benefit is that since it works like a dict, it directly points to all data stored there, no copies. So it's like mapping semantic embedding directly to your data with no steps in between.

It is not an alternative to ChromaDB, rather something that complements it for specific use cases.
