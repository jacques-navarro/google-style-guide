# google-style-guide

## What is a style guide?

A style guide provides conventions that make code look uniform across different code bases. Code linters take conventions defined in a style guide and apply it consistently to files in a project. Style guides are also known as Coding Standards.

    if (n > 0) {
        System.out.println(n);
    }

Without coding standards the same code would look different based on personal preference.

    if(n>0)
    {
        System.out.println(n);
    }

## Why use a style guide?

The lack of consistency requires more effort from the reader to adjust to code written by different programmers.

Groups that agree to use a coding standard spend less time discussing how code should be formatted and more time writing code.

There are also practical reasons. If two programmers work on the same code and submit updates to a version control system, each new version would be cluttered with slight formatting changes that don't affect how the code functions.

## Examples of Style Guides

Companies create their own style guides, which employees are expected to follow, to ensure uniformity across the many projects they have. Communities adopt these guidelines because it takes a lot of effort to come up with and maintain these standards.

  - Google Java Style Guide
  - Python [Black](https://pypi.org/project/black/), follows [PEP8](https://peps.python.org/pep-0008/)
  - Go [fmt](https://go.dev/blog/gofmt)
  - AirBnB [Javascript Style Guide](https://github.com/airbnb/javascript)

## Links
[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)  
[google-java-format IntelliJ plugin](https://plugins.jetbrains.com/plugin/8527-google-java-format)  
[IntelliJ set up instructions](https://github.com/google/google-java-format/blob/master/README.md#intellij-android-studio-and-other-jetbrains-ides)