# Example Contract seperation

In commit cfea067971446bb52c79cd366ebe3eebdc560126 I have a working sample contract test. If you check this out you can see it working

In commit 58bf5212867f340ab30a53de43e0cbfb839d524c I have edited the sourceSet to add a new one called contractTest and added a new contracTest test Task. I want to run the normal contract verification, except this should be run as part of contractTest task not the normal test task. You can check the build.gradle for what I thought would be the setup and what I have tried. This will not compile.

I want to completly seperate the contract tests from the tests source sets as I keep just my unit tests in the test source sets and integration tests in an integration source set and I want these contract tests in a contract test source set.

Thanks
