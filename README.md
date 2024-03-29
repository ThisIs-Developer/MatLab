
# MatLab [![Actions Status](https://github.com/cfgnunes/numerical-methods-python/workflows/build/badge.svg)](https://github.com/ThisIs-Developer/MatLab)

Files are used to keep digital data, whereas directories are used to keep files. Computer files can be considered as the digital counterpart of paper documents. While programming, you keep your source code in text files with different extensions.

![205455851-638ab4f1-b048-4508-8982-c82fd574155b](https://user-images.githubusercontent.com/109382325/215775099-5e0bc064-1ca1-4097-9023-d1d3f9fb9f3b.jpg)


## Author

- [@ThisIs-Developer](https://github.com/ThisIs-Developer)


## Demo
```
x=[0:0.1:20]
y=sin(x)
plot(x,y)
```
## Deployment

Installing MatLab
```bash
https://matlab.mathworks.com/
```
```bash
https://in.mathworks.com/products/matlab/student.html
```
Installation and Licensing
```bash
https://in.mathworks.com/help/install/
```
Manage Products
```bash
https://in.mathworks.com/help/install/manage-products.html
```
Administer Network Licenses
```bash
https://in.mathworks.com/help/install/administer-network-licenses.html
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file
```
res = getenv("SYSTEMROOT")
```
```
setenv("TEMP","C:\TEMP");
getenv("TEMP")
```
```
setenv("PATH", [getenv("PATH") ";D:\mypath"]);
```


## Features

- Signal processing
- Optimization of functions
- Image and Audio processing
- Machine learning and Deep learning



## Running Tests

To run tests, run the following command

```bash
    results = runtests
    results = runtests(tests)
    results = runtests(___,Name,Value)
```
```bash
    results = runtests('runtestsExampleTest.m');
```
```bash
    function tests = runtestsExampleSubFolderTest
    tests = functiontests(localfunctions);  
    function testFunctionTwo(testCase)
```
```
    results = runtests(pwd,'IncludeSubfolders',true);
```
```
    cd 'C:/projects/project1/'
    runtests
```
```
    proj = openProject('C:/projects/project1/');
    runtests
    close(proj)
```
```
    runtests('C:/projects/project1/')
```
