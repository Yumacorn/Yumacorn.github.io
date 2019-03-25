---
layout: post
title:      "Protecting Data: Setting vs Adding to an existing Array"
date:       2019-03-25 00:08:05 +0000
permalink:  protecting_data_setting_vs_adding_to_an_existing_array
---


Being mindful of scalability of your project while coding the basics of your program can maintain the outlook and ability for you to keep clean code well into the future. Even if you are only practicing in a lab setting, or working on a pet project in your spare time to refine your programming skills, good habits reinforce a coding mindset of bringing good code to the table.

In this case, lets consider an Array. Arrays are an object class which allows you to store a collection of data which can be referenced through numbered/indexed format. For example:

```
arr = [10, 20, 30]
```

Here we have an array named "arr", containing 3 integers 10, 20, and 30. Each of the integer objects in this given array can be referred to their position, starting with index of 0, which refers to the first object - an integer object of 10. Arrays allow you to manipulate the data, adding, changing, or removing as you see fit.

There are certain pros and cons to Setting vs Adding to Arrays which you should be mindful of when working with Arrays. These can help determine the best option for the job.

Consider:
* Is this a new array? Or an existing array?
* What types of operations will it need to handle?

When **setting an Array**, the data which you set the Array equal to will be the same.  

```
letters = ["a", "b", "c"]
```

If you need to build a new Array, setting the Array equal to data is your best bet. This allows you to build a new Array object with data already determined and ready to be called upon by your program.

When **adding to an Array**, you can add additional data objects to become a part of your Array.

 ```
 letters << ["d"]
 
 #letters =  ["a", "b", "c", "d"]
 ```
 
If you need to work on an existing Array, be sure to add or remove to your Array. This allows you to reference the existing data in the Array and add/remove, without erasing any of the data that is already in place.

## To set or to add?
If you need to create an array, set the data. Once you have an array which is existing, you should begin to add or remove from the array. This is to prevent overwriting any existing data because your program re-"set" the data once it was given a new data set to enter into the system. 

```
savings_acct = [..., 10, 400, 250]
#savings_acct.total = 25,850
```

For example, you have a bank account which has been helping to store an array of all of your life savings deposits for many years. Your parents decide to give you ($65) for a new deposit and you've sent it to be added to your deposit account. 

```
new_deposit = 65
```

A new programmer is working on the banking program. Instead of adding the new_deposit to the the array of savings deposits,  they accidentally "set" the total of your ```savings_acct``` to the ```new_deposit```  as opposed to adding it to the array.

```
#set to the array
savings_acct = new_deposit
savings_acct = [65]
savings_acct.total = 65

#add to the array
savings_acct << new_deposit
savings_acct = [..., 10, 400, 250, 65]
savings_acct.total = 25,915
```

Fortunately, this **loss of $25,850** is just a hypothetical error. 

But this simple lesson is something that we must be conscious and mindful of. Whenever you are operating on existing arrays, remember to be sure to add/remove instead of setting.



