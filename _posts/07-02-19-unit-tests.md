---
title: Unit Testing
isChild: true
anchor:  unit-testing
---

##  Unit Testing {#unit-testing}


### Methods in test classes MUST start with "test" then a camelCased name of the test


Good
```
class ExampleTest extends TestCase
{
    public function testBasicTest()
    {

```

Bad

```
class ExampleTest extends TestCase
{
    public function test_basic_test()
    {

```