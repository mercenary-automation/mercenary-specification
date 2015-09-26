#The Mercenary Specification#

![](https://raw.githubusercontent.com/mercenary-automation/mercenary-artifacts/master/mercenary-logo.jpg)
##Welcome to the Mercenary Project!##

The goal of Mercenary is to define a standard, language-agnostic REST specification for task orchestration, distribution and reporting across disparate platforms using a simple and extensible [JSON](http://www.json.org/) payload.

The primary use case for Mercenary is ***distributed test automation*** hooked into a continuous build process where multiple test automation tools are in use and multiple testing environments are needed.

##Motivation and Rationale##
- Distributed testing is a no-brainer.  If you have a single test engineer responsible for all the testing, he/she quickly becomes the bottleneck.  Distribute the effort over multiple testers and things can move much, much faster. 

- Automated testing is a no-brainer.  When test engineers spend all their time doing repetitive tasks, not only does quality inevitably suffer, but imagine all the other important work they could be doing if the tests were automated!

**_Given that, distributed automation testing should be an easy sell._**

- Automation runs faster than manual testing
- Automation is more consistent and the results are more accurate
- Automation can happen any time of the day or night
- Automation can run anywhere in the world
- Integrate into a build process and close the feedback loop between developing and testing

Everyone should be nodding their heads at this and pulling out their wallets.

**_Because distributed test automation tools are expensive._**

Usually licensed separately, these tools require dedicated hardware and people with specialized skills to manage their use and upkeep.

If your company has been doing test automation for a while, you probably have multiple test automation tools laying around, or legacy test suites in some state of migration from the old tool to the new one.  And if each of these require their own licenses, hardware and specialized staff to maintain and manage...? Even with overlapping hardware, this can quickly become _really_ expensive, not to mention a huge pain in the @$$.

**_What if you could orchestrate all of your distributed test automation with a single tool?_** 

One point of entry for all distributed testing of _any_ kind.  Integrate it into your build process or kick it off manually, and output your results in the format of your choosing.  No more dedicated hardware for this tool suite and another set of dedicated hardware for that tool suite.

Without getting too technical, Mercenary allows you write your own custom implementation and plugins, use community developed implementations and plugins, or use any combination thereof to get the job done.  What that job is depends completely on you.

**_What about disparate environments?_**

By adhering to an open specification, it no longer matters what language one implementation is written in or what environment it's running in, it will be able to communicate seamlessly with another implementation.  Cross-platform simply isn't an obstacle anymore.

**_What about execution reporting?_**

The same plugin approach to task execution is used for reporting.  Take the results provided by your implementation, and parse them out any way you want.  Put them on web pages, crunch them in spreadsheets, or push them into your test case repositories - it's entirely up to you. 

##Getting Started##
Here are some links to help you get started using Mercenary:

- [Definitions](https://github.com/mercenary-automation/mercenary-specification/wiki/Definitions) : Having a common vocabulary is important before reading any of the other documentation.  Here is a quick-and-easy guide to the common terms you need to know.

- [Implementations](https://github.com/mercenary-automation/mercenary-specification/wiki/Implementations) : There are existing community driven implementations in the most popular languages.  Here is a list of the ones we know about. [Tell us](mailto:mercenary.automation@gmail.com) if you know about one we don't!

- [Useful Tools](https://github.com/mercenary-automation/mercenary-specification/wiki/Useful-Tools) : Going above and beyond the specification, here are some tools that can help you manage and maintain your Mercenary implementation.

##Support##
As every implementation is community developed, support for each is defined by that community.  If you have an issue with the specification, [check out our wiki](https://github.com/mercenary-automation/mercenary-specification/wiki) to see if we've already addressed it, or [submit an issue](https://github.com/mercenary-automation/mercenary-specification/issues).

##License##
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
