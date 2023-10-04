## 🙌 HACKTOBERFEST!!! 🙌

We're excited to announce that **GherKing** is participating in this year's [Hacktoberfest](https://hacktoberfest.com/), a month-long celebration of open-source software contributions. This October, we invite you to join us in making a difference in open-source development!

Here's what you need to know about GherKing's involvement in Hacktoberfest:
 1. **Get Involved**: GherKing is proud to be part of Hacktoberfest. This is a fantastic opportunity for developers, enthusiasts, and anyone interested in open source to collaborate with our project.
 2. **Dive into the Issues**: We have many issues and enhancements ready to tackle, [marked with the hacktoberfest label](https://github.com/gherking/gherking/issues?q=is%3Aopen+is%3Aissue+label%3AHacktoberfest). Whether you're a seasoned developer or just getting started, there's something for everyone. These contributions can help us improve GherKing and make it even better for our users.
 3. **Explore the Possibilities**: Not limited to just our existing issues, we welcome contributions to any of our [repositories marked with the Hacktoberfest topic](https://github.com/search?q=topic%3Ahacktoberfest+org%3Agherking&type=Repositories). Feel free to bring your creativity and ideas to the table!
 4. **Review Our Contribution Guidelines**: Review our contribution guidelines before you start. These guidelines outline the rules and best practices for contributing to GherKing. You can find it [here](https://github.com/gherking/.github/blob/main/CONTRIBUTING.md).

Contribute, learn, and have fun this Hacktoberfest season with GherKing. Together, we can make a real impact on the open-source community while reaping the rewards of your efforts.

Thank you for being a part of the GherKing family and helping us grow and thrive. Let's make this Hacktoberfest a memorable one!

<!--
> ## 🌟 NEWS!!! 🌟
>
> We recently released the following improvements:
> * **gherkin-io/Parsing feature string** (gherkin-io@1.2.0) - to add the possibility to parse feature strings (feature file content) ([gherking#80](https://github.com/gherking/gherking/issues/80))
-->

## What can you do with **GherKing**?

* You can use the [gherkin-ast](https://github.com/gherking/gherkin-ast) package to build and work with feature files in your code using an **AST**.
* You can load and parse feature files to AST and save them back using the [gherkin-io](https://github.com/gherking/gherkin-io) package and the [gherkin-formatter](https://github.com/gherking/gherkin-formatter) to make them pretty.
* You can use the [gherking](https://github.com/gherking/gherking) CLI tool (and the precompilers below) to build a precompiler for your feature files, adding more logic and **magic 🌈** to your feature files.

## Our precompilers

* **Filter** - [gpc-filter](https://github.com/gherking/gpc-filter) - to include or exclude scenario/outlines of feature files based on a cucumber-tag-expression.
* **For Loop** - [gpc-for-loop](https://github.com/gherking/gpc-for-loop) - to loop scenarios and scenario outlines to repeat them.
* **License** - [gpc-license](https://github.com/gherking/gpc-license) - to add a license statement to the feature files.
* **Macro** - [gpc-macro](https://github.com/gherking/gpc-macro) - to create and execute macros.
* **Remove Comments** - [gpc-remove-comments](https://github.com/gherking/gpc-remove-comments) - to remove all or particular types of semantic comments from the feature file.
* **Remove Duplicates** - [gpc-remove-duplicates](https://github.com/gherking/gpc-remove-duplicates) - to remove duplicated tags or example data table rows.
* **Replacer** - [gpc-replacer](https://github.com/gherking/gpc-replacer) - to replace keywords in the feature files.
* **Scenario Numbering** - [gpc-scenario-numbering](https://github.com/gherking/gpc-scenario-numbering) - to add an index to all scenarios and scenario outline's name.
* **Scenario Outline Expander** - [gpc-scenario-outline-expander](https://github.com/gherking/gpc-scenario-outline-expander) - to expand the Scenario Outlines to actual scenarios.
* **Scenario Outline Numbering** - [gpc-scenario-outline-numbering](https://github.com/gherking/gpc-scenario-outline-numbering) - to make all scenarios generated from scenario outlines unique.
* **Step Group** - [gpc-step-groups](https://github.com/gherking/gpc-step-groups) - to correct the gherkin keywords of steps to make the tests more readable.
* **Test Data** - [gpc-test-data](https://github.com/gherking/gpc-test-data) - to load external data (JSON, CSV, or XLS/XLSX) into the examples table.

## Precompilers we plan

* **Copy** - to copy feature files and distribute them based on some logic (e.g., to different folders, based on a tag) ([gherking#39](https://github.com/gherking/gherking/issues/39))
* **Example Sampler** - to chose a given number of random example ([gherking#37](https://github.com/gherking/gherking/issues/37))
* **Sorter** - to sort scenario/outline based on certain conditions ([gherking#52](https://github.com/gherking/gherking/issues/52))
* **Splitter** - to split each scenario/outline to separate feature files to improve parallelization ([gherking#44](https://github.com/gherking/gherking/issues/44))
* **Suite Generator** - to sort feature files and scenarios/outlines in separate files based on suite tags ([gherking#45](https://github.com/gherking/gherking/issues/45))

Do you have an idea for a cool precompiler? [Send your idea to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+The+name+of+the+precompiler)

## Precompilers made by the community

Do you have a precompiler you implemented? [Send it to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+New+OSS+precompiler) And we will list here!

## Upcoming features

* **gherking/jumpstart command** (in progress) - to kick-off usage of GherKing easier ([gherking#66](https://github.com/gherking/gherking/issues/66))
* **gpc-replacer/built-in tokens** - to add the possibility to use UUID much more easily ([gpc-replacer#4](https://github.com/gherking/gpc-replacer/issues/4))
* **gherking/Controlling precompiler application** - to control which precompiler is applied to a given feature file or which is not ([gherking#73](https://github.com/gherking/gherking/issues/73))

Do you have an idea for any new features? [Send your idea to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=feature-request.md&title=%5BIMPR%5D+A+short+description%2Fname+of+the+new+feature)
