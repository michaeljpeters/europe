a project for testing out multiple top-level workspaces with uv

Example:
```
$ uv pip install .
$ python
>>> from athens.ships import agean
>>> from carthage.hannibal import cross_alps
>>> from rome.conquest import triumph
>>> from sparta.chokepoint import thermopylae
>>>
>>> agean()
defending the Agean from the Persians with our elite triremes
>>> cross_alps()
crossing the alps with 29 elephants... in the winter
>>> triumph()
celebrating great military achievements with my triumph
>>> thermopylae()
defending the chokepoint at thermopylae with 300 men
```
