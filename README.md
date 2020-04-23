# BindingListViewCore
Forked from: https://github.com/geomatics-io/BindingListView
Thanks to Christian Junk for his latest work https://github.com/christianjunk

Sort, filter and aggregate lists of business objects without all the boring code! This library provides a powerful "view" approach to data binding .NET objects to user interface controls.
2006 Andrew Davies

I've been using .Net core for a while. I needed to write a utility for a project and I used WinForms. I used to use BindingListView in my WinForms project because of the ease of filtering and sorting capabilities.
When I needed this lovely library I noticed that my Visual Studio was complaining that it is not compatible with .Net Core. So I created a new .Net Core project and just copied the source code there. 
After fixing some little .csproj oddities (mostly due to WinForms reference and base SDK type) I tested the resulting DLL with success. Enjoy.
