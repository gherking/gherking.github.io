# Hi there 👋

**GherKing** is a tool to make Gherkin smarter! It allows you to handle Cucumber/Gherkin feature files programmatically, in your JavaScript/TypeScript code.

## What can you do with **GherKing**?

* You can use the [gherkin-ast](https://github.com/gherking/gherkin-ast) package to build and work with feature files in your code, using an **AST**.
* You can load feature files to AST and save them back using the [gherkin-io](https://github.com/gherking/gherkin-io) package; and the [gherkin-formatter](https://github.com/gherking/gherkin-formatter) to make them pretty.
* You can use the [gherking](https://github.com/gherking/gherking) CLI tool (and the precompilers below) to build a precompiler for your feature files, adding more logic and **magic 🌈** to your feature files.

## Our precompilers

* **Filter** - [gpc-filter](https://github.com/gherking/gpc-filter) - to include or exclude scenario/outline of a resulting feature file based on a cucumber-tag-expression.
* **For Loop** - [gpc-for-loop](https://github.com/gherking/gpc-for-loop) - to loop scenarios and scenario outlines in order to repeat them.
* **Macro** - [gpc-macro](https://github.com/gherking/gpc-macro) - to create and execute macros.
* **Remove Duplicates** - [gpc-remove-duplicates](https://github.com/gherking/gpc-remove-duplicates) - to remove duplicated tags or example data table rows.
* **Replacer** - [gpc-replacer](https://github.com/gherking/gpc-replacer) - to replace keywords in the feature files.
* **Scenario Numbering** - [gpc-scenario-numbering](https://github.com/gherking/gpc-scenario-numbering) - to add an index to all scenario and scenario outline's name.
* **Scenario Outline Expander** - [gpc-scenario-outline-expander](https://github.com/gherking/gpc-scenario-outline-expander) - to expand the Scenario Outlines to actual scenarios.
* **Scenario Outline Numbering** - [gpc-scenario-outline-numbering](https://github.com/gherking/gpc-scenario-outline-numbering) - to make all scenario, generated from scenario outlines unique.
* **Step Group** - [gpc-step-groups](https://github.com/gherking/gpc-step-groups) - to correct the gherkin keywords of steps to make the tests more readable.

## Precompilers we plan

* **Copy** - to copy feature files and distribute them based on some logic (e.g. to different folders, based on a tag) ([#39](https://github.com/gherking/gherking/issues/39))
* **Example Sampler** - to chose a given number of random example ([#37](https://github.com/gherking/gherking/issues/37))
* **Remove Comments** - to remove all or particular type of semantic comments from the feature file ([#58](https://github.com/gherking/gherking/issues/58))
* **Sorter** - to sort scenario/outline based on certain conditions ([#52](https://github.com/gherking/gherking/issues/52))
* **Splitter** - to split each scenario/outline to separate feature files, to improve parallelization ([#44](https://github.com/gherking/gherking/issues/44))
* **Suite Generator** - to sort feature files and scenarios/outlines in separate files, based on suite-tags ([#45](https://github.com/gherking/gherking/issues/45))
* **Test Data** - to insert test data to feature files ([#21](https://github.com/gherking/gherking/issues/21))

Do you have an idea for a cool precompiler? [Send your idea to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+The+name+of+the+precompiler)

## Precompilers made by the community

Do you have a precompiler you implemented? [Send it to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+New+OSS+precompiler) And we will list here!

## Upcoming features

* Adding support for **comments** ([#58](https://github.com/gherking/gherking/issues/58))

Do you have an idea for any new feature? [Send your idea to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=feature-request.md&title=%5BIMPR%5D+A+short+description%2Fname+of+the+new+feature)

