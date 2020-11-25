# Fancy words that developers might need to knows

1. **Idempotent** - Produces same result  
Taking REST API as example, Idempotency is demonstrated in ```GET```, ```PUT```, ```DELETE```, ```HEAD```, ```OPTIONS```, ```TRACE```. However, ```POST``` is not idempotent.  
For more info, read [this](https://restfulapi.net/idempotent-rest-apis/#:~:text=In%20the%20context%20of%20REST,REST%20API%20is%20called%20idempotent.&text=An%20idempotent%20HTTP%20method%20is,many%20times%20without%20different%20outcomes.).
2. **Ephemeral** - may not persist, opposite of immutable