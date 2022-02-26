# WaitForAnim

A Unity-package for waiting for animations in coroutines.

Check out the wiki [here](https://github.com/ComradeVanti/WaitForAnim/wiki).

Found any issues? Leave
them [here](https://github.com/ComradeVanti/WaitForAnim/issues).

## Features

Adds custom yield-instructions for waiting for animations to start or finish
inside of coroutines. Example:

```
yield return new WaitForAnimationToStart(animator, "MyAnim");
```

## Installation

[Use the package manager](https://docs.unity3d.com/Manual/upm-ui-giturl.html)
with the url `git://github.com/ComradeVanti/WaitForAnim` to add the package to
your project.
