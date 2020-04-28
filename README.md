# XUnit Snippets

Snippet support for common XUnit code (facts, theory, test class, theory data,...)

## Features

Supported snippets include
  - `xclass`: Test class 
  - `xfact`: Fact test method
    ```cs
    [Fact]
    public void testName()
    {
        throw new NotImplementedException()
    }
    ```
  - `xtheory`: Theory test method 
  - `xdatafield`: TheoryData as a field
  - `xdatam`: TheoryData from a method 

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.



## Release Notes

### 1.0.0

Initial release with basic snippets (fact, theory, test class, test data)

-----------------------------------------------------------------
