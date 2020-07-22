# Hello, world!

This is a beginner level task for practicing AutoCode tasks management.


## Get the Project

* [Fork the task project (repository)](https://docs.gitlab.com/ee/user/project/repository/forking_workflow.html#creating-a-fork) in GitLab.
* [Open a project from your remote repository](https://docs.microsoft.com/en-us/visualstudio/get-started/tutorial-open-project-from-repo) or [get your local copy](https://docs.microsoft.com/en-us/azure/devops/repos/git/clone#clone-from-another-git-provider) with Visual Studio.


## Complete the Task

1. [Build the solution](https://docs.microsoft.com/en-us/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio).
    * Click on menu item - _Build\Build Solution_.
    * Or use default keyboard shortcut - _Ctrl+B_.
1. Run all unit tests.
    * Click on menu item - _Test\Run All Tests_.
    * Or use defaul keyboard shortcut - _Ctrl+R, A_.
1. Open the [Test Explorer] view, and find failed unit tests there.
    * Click on menu item - _View\Test Explorer_.
    * Or use default keyboard shortcut - _Ctrl+E, T_.
1. Double-click on a failed unit tests, and you will get to the [unit test source code](HelloWorld.Tests/SimpleClassTests.cs).
1. Open a [Solution Explorer](https://docs.microsoft.com/en-us/visualstudio/ide/solutions-and-projects-in-visual-studio#solution-explorer).
    * Click on menu item - _View\Solution Explorer_.
    * Or use default keyboard shortcut - _Ctrl+W, S_.
1. Double-click on the [SimpleClass.cs](HelloWorld/SimpleClass.cs) file, and you will get to the source editor.
1. Uncomment the commented line in the "ReturnOne" method, and comment "throw new..." line.
    * For commenting selected lines you can use the default shortcut - _Ctrl+K, Ctrl+C_.
    * For uncommenting selected lines you can use the default shortcut - _Ctrl+K, Ctrl+U_.
1. Open the Test Explorer, click on "ReturnOne" unit test with your right mouse button, and click on "Run" menu item.
    * Or use default shortcut - _Ctrl+R, T_.
1. Uncomment the commented line in the "ReturnTrue" method in the [SimpleClass.cs](HelloWorld/SimpleClass.cs) file, and comment "throw new..." line.
1. Run all unit tests, open Test Explorer, find the "ReturnObject" unit test, and do a double-click on the test. You will get to the [unit test source code](HelloWorld.Tests/SimpleClassTests.cs).
1. Click on the "ReturnObject" method name in the "object result = SimpleClass.ReturnObject();" string with your right mouse button. Click on "Go To Implementation" menu item. You will ge to the [SimpleClass.cs](HelloWorld/SimpleClass.cs) file.
1. Uncomment the commented line in the "ReturnObject" method, and comment "throw new..." line.
1. Open [SimpleClassTests.cs](HelloWorld.Tests/SimpleClassTests.cs), click with your right mouse button on "ReturnObject" unit test name in the "public void ReturnObject()" line, and click on "Run Test(s)" menu item.
1. Open Test Explorer, and make sure the test finished successfully.
1. Run all unit tests to make sure there are no more failed unit tests.
1. Remove all commented "throw new..." lines in the [SimpleClass.cs](HelloWorld/SimpleClass.cs) file.
1. Rebuild the solution.
    * Click on menu item - _Build\Rebuild Solution_.
1. Open [Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) view.
    * Click on menu item - _View\Error List_.
    * Or use default shortcut - _Ctrl+W, E_.
1. Double-click on a warning in the Error List view. You will get to the [CodeWithWarning.cs](HelloWorld/CodeWithWarning.cs) file.
1. Open Error List view again, and click on a warning "Code" link. You will get to a documentation web-page for a warning.
1. Go to the [CodeWithWarning.cs](HelloWorld/CodeWithWarning.cs) file, and format the current document.
    * Use default shortcut - _Ctrl+K, Ctrl+D_.
1. Build the solition again, open Error List view, and compare the number of compiler warnings with the previous number.
1. Fix compiler warnings in the [CodeWithWarning.cs](HelloWorld/CodeWithWarning.cs) file.


## Fix Compiler Issues

Additional style and code checks are enabled for the projects in this solution to help you maintaining consistency of the project source code and avoiding silly mistakes. [Review the Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) in Visual Studio to see all compiler warnings and errors.

If a compiler error or warning message is not clear, [review errors details](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-errors-in-detail) or google the error or warning code to get more information about the issue.


## Save Your Work

* [Rebuild your solution](https://docs.microsoft.com/en-us/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio) in Visual Studio.
* Check out the [Error List window](https://docs.microsoft.com/en-us/visualstudio/ide/reference/error-list-window) for compiler errors and warnings. If you have any of those issues, **fix issues** and rebuild the solution again.
* [Run all unit tests with Test Explorer](https://docs.microsoft.com/en-us/visualstudio/test/run-unit-tests-with-test-explorer) and make sure there are **no failed unit tests**. Fix your code to [make all your unit tests GREEN](https://stackoverflow.com/questions/276813/what-is-red-green-testing).
* Review all your changes **before** saving your work.
    * Open "Changes" view in [Team Explorer](https://docs.microsoft.com/en-us/visualstudio/ide/reference/team-explorer-reference).
    * Click with your right mouse button on a modified file.
    * Click on "Compare with Unmodified" menu item to open a comparison window.
* [Stage your changes](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits#stage-your-changes) and [create a commit](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits#create-a-commit).
* Share your changes by [pushing them to remote repository](https://docs.microsoft.com/en-us/azure/devops/repos/git/pushing).


## See also

* Visual Studio
  * [First look at the Visual Studio Debugger](https://docs.microsoft.com/en-us/visualstudio/debugger/debugger-feature-tour)
  * [Quickstart: Debug with C# or Visual Basic using the Visual Studio debugger](https://docs.microsoft.com/en-us/visualstudio/debugger/quickstart-debug-with-managed)
  * [Tutorial: Learn to debug C# code using Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-debugger)
  * [Navigate through code with the Visual Studio debugger](https://docs.microsoft.com/en-us/visualstudio/debugger/navigating-through-code-with-the-debugger)
  * [Default keyboard shortcuts in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/ide/default-keyboard-shortcuts-in-visual-studio)