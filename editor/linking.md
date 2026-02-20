# Linking

Linking between pages is very important to group the manual together.

The manual always looks to display an "index.md" at the root of each directory. 

So the first page of the manual will be `/index.md`

If you have sub directories then the first page when visiting that directory will be `/<dir_name>/index.md`

To make a manual link writing markdown use the format:

`[Text of Link](Relative Path to Link)`

So to link to the root homepage you would do:

`[Home page](../index.md)`

resulting in

[Home page](../index.md)
