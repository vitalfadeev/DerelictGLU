# DerelictGLU

Thsi is beta.

dub.json
```JSON
    "dependencies":
    {
        "derelict-glu" : { "path" : "deps/DerelictGLU" }
    },
```

app.d
```D
import derelict.opengl.glu;

void main()
{
    DerelictGLU.load();

    ... using glu*
}
```

