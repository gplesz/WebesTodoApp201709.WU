# WebesTodoApp
A NetAcademia Webes TODO alkalmazás készítése tanfolyam kódtára

### Ha nem megy a Controller/View scaffolding
There was an error running the selected code generator: 'Invalid pointer (Exception from HRESULT: 0x80004003 (E_POINTER))'

```
Try clearing the ComponentModelCache, the cache will rebuild next time VS is launched.

- Close Visual Studio
- Delete everything in this folder C:\Users\\AppData\Local\Microsoft\VisualStudio\14.0\ComponentModelCache
- Restart Visual Studio

14.0 is for visual studio 2015. This will work for other versions also.
```
[StackOverflow](https://stackoverflow.com/a/35815094/208922)
