# RML2SHACL

This project is part of my master thesis @ Campus De Nayer (KUL).


It's written in Python and makes the translation of an RML mapping to a SHACL shape.

## Getting started

1. You can run the [RMLtoSHACL.py](RMLtoShacl.py) file and this will go through all the testcases automatically.

or

2. You can run one specific testcase when running my miniMain function. 
See the code below of which lines you need to comment and uncomment in [RMLtoSHACL.py](RMLtoShacl.py):


```Python
if __name__ == "__main__":
    RtoS = RMLtoSHACL()
    #RtoS.main()
    RtoS.miniMain()
```
And you can change the letter, number and filetype in the miniMain function in [RMLtoSHACL.py](RMLtoShacl.py) to create a specific shape for a specific RML testcases.

```Python
def miniMain(self):
        filetype = FilesGitHub.XML
        letter = 'a'                
        number = 8
```

Shapes are created in the [Shapeoutput](outputShape.ttl).
