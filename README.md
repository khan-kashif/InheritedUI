# InheritedUI

The repo reproduces windows form designer bug. The bug occurrs when the designer tries to render form controls which are inherited.
Open the project in Visual Studio. You must have the .net core designer enabled in the Tools => Environment => Preview Features

To reproduce the bug, open the form "InheritedForm" and the designer will throw the exception.

This bug applies to Visual Studio 16.7.3 and .Net Core SDK 3.1.402.015278
