# Swift

## August 18, 2018

### 4:20 PM

Got to kick off Swift with the book Learning Swift, 3rd Edition from O'Reilly. Got to read up about the core language itself and it resembles Kotlin quite a bit. If there's one thing I especially found useful, it was the fact that you could make mutable or immutable collection simply by using `var` or `let`.

### 9:49 PM

Couldn't help but have another go at the language and learned about OOP in Swift. Something I found amazing was the fact that you could extend a class to conform to a protocol. That kinda blew my mind. It was also amusing to see that you could also declare your own operations on classes.

### 11:11 PM

Had a go all the way to the Swift Package Manager. I'll read up the rest of the chapter tomorrow since this looks rather long.

## August 19, 2018

### 10:42 AM

Finished up the third chapter and read about the Swift Package Manager. I did stumble on a few problems on my machine though. It might be that there have been some breaking changes made between the publication of the book.

### 11:01 AM

Got to setup the basic project and followed some of the modifications for Selfiegram. Time to build a very original app.

## August 21, 2018

### 1:56 PM

So today, I got to build up the model component of the Selfiegram app. In this I've pretty much created an image, saved it to disk, encoded and decoded JSON from local storage and had unit tests to boot.

## August 22, 2018

### 9:31 PM

Got to add the ability to view available selfies in a list. It displays how long ago a selfie has been taken and a preview. As of now, it's only showing the selfies that have been left out by running my tests.

## August 29, 2018

### 9:45 PM

After all the setbacks and traveling and settling down here in Sweden, I got back up again and started coding. This time, I added the ability to delete items in the list and add new selfies using the camera.

## August 30, 2018

### 7:28 AM

Added the ability to view individual selfies in Selfiegram. I'll work on editing a bit later.

### 11:09 AM

Finished up the basic functionality of the app. So I could now add new selfies, edit their titles, and then delete them. Up next will be adding metadata for location.

## August 31, 2018

### 9:41 AM

Today I got to work on the location library of iOS. This allowed me to add location data to Selfiegram's images and show a map. The map could be tapped and will open the Maps app to show you the general area where a selfie has been taken.

## September 1, 2018

### 10:33 PM

This time added a simple settings page to the Selfiegram app and added the ability to toggle on and off the ability to add location to selfies.

At this point, I think I've learned enough Swift to take on "Classic Computer Science Problems in Swift". And so with that, it time to close Learning Swift.

## September 2, 2018

### 9:13 PM

Today I shift my attention to "Classic Computer Science Problems in Swift". This book is the reason I started out Swift actually. So today I did the fibonacci sequence in a couple of ways. One that was absolutely broken (infinite recursion), one that worked through recursion, one with memoization, and one iteratively. Of course, this lead to some extra reading.

I also got to do compression for the first time. The example in the book takes a sequence of nucleotides that represent DNA in a String format and converted into a smaller binary form.

## September 3, 2018

### 9:50 AM

Today I got to work on creating encryption, solving pi, and solving the Towers of Hanoi. Though admittedly, I'm still confused by the Towers of Hanoi and will require some extra searching around.

## September 4, 2018

### 2:07 PM

Finally got to understand the Towers of Hanoi and it's actually quite amazing once you get it. I've also done the exercises listed for the first chapter including a version of fibonacci that does it iteratively and with memoization, a wrapper for the BitVector class, a Tower of Hanoi solver, and encrypting an image.

## September 6, 2018

### 2:24 PM

Did the DNA search section of Chapter 2, which is all about searching. I've known about linear search and binary search for a while now but writing them out makes for a good exercise.

## September 7, 2018

### 9:08 PM

Got to finally do some maze solving algorithms. I've always watched about them but never really got to learn how they work. I was able to implement and understand how depth-first search works. It took me a bit to get it but I did. Tomorrow, I'll do breadth-first search.

## September 8, 2018

### 11:20 AM

Got to do breadth-first search and the A* algorithm! I was amazed at how just changing one data structure was all it took to go from depth-first to breadth-first. A* was something I've always heard about (again) but never got to do. I have a good idea of how it works, but I'll definitely give it a better look to fully understand it.

## September 9, 2018

### 12:04 PM

So today I did the Missionaries and Cannibals problem. To my surprises, I didn't think you could solve this problem using search algorithms. In the book, breadth-first search is used to discover the fastest way to move all parties from one side to another. What I also found surprising was trying out the problem with a different number of missionaries and cannibals. The search algorithm found a solution for two but four up to nine yielded nothing (if I were doing things right).

### 2:42 PM

Went a little further today and started on the chapter about constraint-satisfaction problems. I got to the part for the Australian Map Coloring Problem and I found it interesting because I've seen the solution to this in Prolog. Now I've seen what it looks like implemented in Swift and it's given me a bit of a new perspective as well.

## September 11, 2018

### 12:15 PM

Got to finish the entire chapter on constraint-satisfaction problems and I was impressed with the fact that you could solve multiple problems simply by defining new constraints for the problem. Next up, graph problems.

## September 12, 2018

Started reading up on Chapter 4. Graph problems. Got to code in the protocols for an edge and a graph and it's extension. I'm a little busy today so this is all for today. I'll read more tomorrow maybe (hopefully).