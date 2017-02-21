# Swift Quick Start

Swift is a powerful and intuitive programming language for macOS, iOS, watchOS and tvOS. Writing Swift code is interactive and fun, the syntax is concise yet expressive, and Swift includes modern features developers love. Swift code is safe by design, yet also produces software that runs lightning-fast.


## Swift History and fundamental Types

Althought it is it's own independent language, Swift provides its own versions of all fundamental C and Objective-C types, including Int for integers, Double and Float for floating-point values, Bool for Boolean values, and String for textual data. Swift also provides powerful versions of the three primary collection types, Array, Set, and Dictionary, as described in [Collection Types.](https://developer.apple.com/library/prerelease/content/documentation/Swift/Conceptual/Swift_Programming_Language/CollectionTypes.html#//apple_ref/doc/uid/TP40014097-CH8-ID105)


### Installing Swift

1. Install the compiler and other required components from the [download] (https://swift.org/download/) page and follow the instructions for your target platform. 


### Installation Instructions

Before you go any further, please make sure you have the latest version of Xcode 6 installed (as of writing this ReadMe, the latest version is Xcode 6 Beta 5). Now, you have two options:

Open a new Swift project:

  1. Launch Xcode
  2. Select File → New → Project
  3. Select "Single View Application" (under iOS → Application)
  4. Fill in the details and make sure that you choose "Swift" under the "Language" field
  5. Run your newly created project

Use Playground: Playgrounds allow you to experiment with Swift code and see results immediately, 
      without the overhead of running a full app.

  1. Launch Xcode
  2. Select File → New → File
  3. Select "Playground" (under iOS → Source)


### Getting Started 

#Syntax

A simple Hello World in Swift, can be achieved using a single line:

```
1| println("Hello World!")

```

Notice that there's no semicolons at the end of the line. In Swift, you don't need to write them at the end of every statement.

#Variables and Constants

In Swift, `var` means `variable`. A variable is an object that can be mutated, or changed.

In Swift, `let` means `constant`. Constant means the the value assigned to the object can never be changed. Once it is set, it’s done. You use a constant when you need to set a value that will never change.

```
var sampleVariable = 1     // This is how you define a new variable
let sampleConstant = "Constant" // This is how you define a new constant

var sampleInteger: Int = 3  // Defining a variable with an explicit type
let sampleString: String = "Another Constant"

// Including values/expressions inside strings ("The sum is: 4")
let sumString = "The sum is: \(sampleVariable + sampleInteger)"

var sampleList = ["item1", "item2", "item3"]      // Defining an array
var sampleDict = ["key1" : "value1", "key2" : "value2"] // Defining a dictionary

sampleList[1] = "Updated Item"  // Setting the value of an element
println(sampleDict["key2"]( // Reading the value of an element

```

### Additional Documentation

Here, you’ll find documentation about the Swift language and the standard library. Apple has additional resources for learning Swift—such as videos, sample code and playgrounds, and additional documentation—at https://developer.apple.com/swift/resources/.


## Authors

* **Kyla Massey** - *Initial work* - [LinkedIn](https://www.linkedin.com/in/kylamassey)
* **Shauan Ferreira Leite** - *Initial work* - [LinkedIn](https://www.linkedin.com/in/shauanleite)



## Resources Used

https://swift.org/about/
https://github.com/apple/swift/blob/master/README.md
https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/
