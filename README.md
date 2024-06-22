```py
from github.profile import ReadMe
class zenith ( ReadMe ) :
    def __init__ ( self ) :
        self.name  = "zenith-arc"
        self.location  = "Indonesia"
    def about ( self ) :
        print( f"{self.name} Fullstack Developer." )
me = zenith()
me.about()
```
