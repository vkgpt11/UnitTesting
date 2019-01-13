# UnitTesting


## What is the difference xunit Fact vs Theory attributes?

- The [Fact] attribute is used by the xUnit.net test runner to identify a 'normal' unit test: a test method that takes no method arguments.
- The [Theory] attribute, on the other, expects one or more DataAttribute instances to supply the values for a Parameterized Test's method arguments.
- xUnit.net itself supplies various attributes that derive from DataAttribute: [InlineData], [ClassData], [PropertyData].
https://stackoverflow.com/questions/22373258/difference-between-fact-and-theory-xunit-net


https://andrewlock.net/creating-parameterised-tests-in-xunit-with-inlinedata-classdata-and-memberdata/
