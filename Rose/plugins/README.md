## Rose bot example plugin format here :
You can create your own custom plugin useing this format or use any [pyrogram](http://pyrogram.org) method !


```
from Rose import app
from Rose.utils.commands import *

@app.on_message(command("test"))
async def plug(_, message):
    lazydeveloper = await message.reply_text(text="Hello I am rose"
    )
    LazyDeveloper = """
I'm a group management bot with some useful features.
@TheMissLazyRose_bot    
    """
    await lazydeveloper.edit_text(LazyDeveloper)

__MODULE__ = "test"
__HELP__ = """  
/test - test cmd here
"""
```

