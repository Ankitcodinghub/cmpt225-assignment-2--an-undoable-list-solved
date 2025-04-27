# cmpt225-assignment-2--an-undoable-list-solved
**TO GET THIS SOLUTION VISIT:** [CMPT225 Assignment 2- An Undoable List Solved](https://www.ankitcodinghub.com/product/cmpt225-assignment-2-an-undoable-list-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120191&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT225 Assignment 2- An Undoable List Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In software, ‘undo’ erases our mistakes; in life, mistakes craft our story. Imagine the tales we’d lose with a real-life Ctrl+Z. —

ChatGPT

In this assignment, your task is to add an undo feature to a string list.

To start, here’s a working class called Stringlist that implements a string list as a dynamic array. Stringlist_test.cpp has tests for all the methods in Stringlist.

Stringlist has one unimplemented method:

cpp // // Undoes the last operation that modified the list. Returns true if a // change was undone. // // If there is nothing to undo, does nothing and returns false. // bool undo() { cout &lt;&lt; “Stringlist::undo: not yet implemented “; return false; }

Your job is to implement undo, thus making Stringlist an undoable list.

Your implementation must follow these rules:

Do not delete any methods, or change the signatures of any methods, in Stringlist. You can change the implementation of existing methods if necessary. But they should still work the same way: your finished version of Stringlist with undo implemented must still pass all the tests in Stringlist_test.cpp.

You can add other helper methods or variables (public or private), functions, and classes/structs to Stringlist.h if you need them.

You must implement undo() using a private stack that is accessible only inside the Stringlist class. Implement the stack yourself as a singly-linked or doubly-linked list. Do not use arrays, vectors, or any other data structure for your stack.

Do not use any other #includes or #pragmas in Stringlist.h beyond the ones already there.

When it’s done, you’ll be able to write code like this:

“`cpp

include “Stringlist.h” include

using namespace std; int main() { Stringlist lst; cout &lt;&lt; lst &lt;&lt; endl; // {}

lst.insert_back(“one”); lst.insert_back(“two”); lst.insert_back(“three”); cout &lt;&lt; lst &lt;&lt; endl; // {“one”, “two”, “three”}

lst.undo(); cout &lt;&lt; lst &lt;&lt; endl; // {“one”, “two”}

lst.undo(); cout &lt;&lt; lst &lt;&lt; endl; // {“one”}

lst.undo(); cout &lt;&lt; lst &lt;&lt; endl; // {}

} “`

Getting Started with StringList

To start, download all the files for this assignment to your computer, and then compile and run Stringlist_test.cpp to make sure it runs without error:

“`bash

make Stringlist_test g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g Stringlist_test.cpp -o Stringlist_test valgrind ./Stringlist_test … test output … “`

Running your program with valgrind is important, since it will help you find memory leaks, and other memory-related errors.

Note There should be no errors when you run this test program! If you have any, double-check that you are running exactly the correct file, and using the correct compiler version, correct options, and correct makefile.

Designing the Undo Stack

As mentioned above, you must implement undo() using at least one private stack implemented as a linked list inside the Stringlist class. You can modify Stringlist only as described above.

The main idea for how undo works is that every time Stringlist is modified by a method that can be undone, it pushes the inverse operation on the top of an undo stack. When undo() is called, it pops the top of the stack and applies that operation to the list, thus undoing the most recent operation.

Important All the methods in Stringlist marked “undoable” should work with undo(). Note that undo() itself cannot be undone.

Here are some examples of how specific methods should work.

Undoing insert_before

Suppose lst is {“dog”, “cat”, “tree”}, and you call lst.insert_before(3, “hat”), making it {“dog”, “cat”, “tree”, “hat”}. It should push the operation remove string at index 3 on the undo stack. You could store it as a short string command, e.g. REMOVE 3. If you now call lst.undo(), the REMOVE 3 command on top of the stack is popped and applied to the list, e.g. the string at index 3 is removed, leaving the list in the state it was in before calling insert_before: {“dog”, “cat”, “tree”}.

In code:

“`cpp // lst == {“dog”, “cat”, “tree”} lst.insert_before(3, “hat”); // lst == {“dog”, “cat”, “tree”, “hat”} lst.undo(); // lst == {“dog”, “cat”, “tree”} lst.insert_before(1, “shoe”); // lst == {“dog”, “shoe”, “cat”, “tree”} lst.undo(); // lst == {“dog”, “cat”, “tree”} “`

Undoing set

For set, suppose that lst is {“yellow”, “green”, ” red cat “, “orange”}, and so lst.get(2) returns ” red cat “. If you call lst.set(2, “cow”), then you should push the operation set location 2 to “red” onto the undo stack, and then over-write location 2 with “cow”. You could format the operation like “SET 2 red cat “. Calling lst.undo() pops the top command of the stack and applies it to the list, e.g. the string at index 2 is set to ” red cat ” and the list is in the state it was in before calling set: {“yellow”, “green”, ” red cat “, “orange”}.

In code:

“`cpp // lst == {“yellow”, “green”, ” red cat “, “orange”} lst.set(2, “cow”); // lst == {“yellow”, “green”, “cow”, “orange”} lst.undo(); // lst == {“yellow”, “green”, ” red cat “, “orange”} “`

Undoing remove_at

For remove_at, suppose lst is {“dog”, ” pink cat “, “tree”}. If you call lst.remove_at(1), you should then push the operation insert ” pink cat ” at index 1 onto the stack, and then remove the string at index 1 so it becomes {“dog”, ” pink cat “, “tree”}. You could format the operation as “INSERT 1 pink cat “. If you now call lst.undo(), the command on top of the stack is popped and applied to the list, e.g. the string ” pink cat ” is inserted at index 1, and the list is in the state it was in before calling remove_at: {“dog”, ” pink cat “, “tree”}.

In code:

“`cpp // lst == {“dog”, ” pink cat “, “tree”} lst.remove_at(1); // lst == {“dog”, “tree”} lst.undo(); // lst == {“dog”, ” pink cat “, “tree”} “`

Undoing operator=

For operator=, suppose lst1 is {“dog”, “cat”, “tree”}, and lst2 is {“yellow”, “green”, “red”, “orange”}. If you call lst1 = lst2;, then you should push the command set lst1 to {“dog”, “cat”, “tree”} onto the stack, and then assign lst1 to lst2. Calling lst1.undo() pops the command on top of the stack and applies it to the list, e.g. lst1 is set to the state it was in before calling operator=:

{“dog”, “cat”, “tree”}.

In code:

“`cpp // lst1 == {“dog”, “cat”, “tree”} // lst2 == {“yellow”, “green”, “red”, “orange”} lst1 = lst2; // lst1 == {“yellow”, “green”, “red”, “orange”} // lst2 == {“yellow”, “green”, “red”, “orange”} lst1.undo(); // lst1 == {“dog”, “cat”, “tree”} // lst2 == {“yellow”, “green”, “red”, “orange”} “`

As this shows, when you undo operator=, the entire list of strings is restored in one call to undo().

Important notes:

Self-assignment is when you assign a list to itself, e.g. lst1 = lst1;. In this case, nothing happens to lst1. Both its string data and undo stack are left as-is.

Undoing remove_all

For remove_all, suppose lst is {“dog”, “cat”, “tree”}. If you call lst.remove_all(), then you should push the operation set lst1 to {“dog”, “cat”, “tree”} onto the stack, and then remove all the strings from lst (i.e. its size is 0). Calling lst1.undo() pops the command on top of the stack and applies it to the list, e.g. lst is set to {“dog”, “cat”, “tree”} and the list is in the state it was in before calling remove_all: {“dog”, “cat”, “tree”}.

In code:

“`cpp // lst == {“dog”, “cat”, “tree”} lst.remove_all(); // lst == {} lst.undo(); // lst == {“dog”, “cat”, “tree”} “`

Notice how all the strings are restored in a single call to undo().

It lst is empty, it works like this:

“`cpp

// lst == {} lst.remove_all(); // lst == {} lst.undo(); // lst == {} “`

Undoing Other Methods

undo() should undo all the other methods in Stringlist that are marked “undoable” in the source code comments.

As mentioned above, undo() is not undoable.

Testing Your Code

It’s important to test your code as you go. In a2_test.cpp, write code to test your Stringlist undo method. Compile and run it like this:

“`bash â¯ make a2_test g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g a2_test.cpp -o a2_test

./a2_test … testing output … “`

You should test at least the examples given above, plus every other function that can be undone. Follow the testing style in Stringlist_test.cpp and use asserts or if-statements to automatically test your code.

What to Submit

When you’re done, submit just your Stringlist.h on Canvas. Don’t submit anything else.

Grading

The marker will compile and run your program on Ubuntu Linux using makefile and a command like this:

“`bash

make a2_test g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g a2_test.cpp -o a2_test

./a2_test … testing output …

valgrind ./a2_test … valgrind output … “`

include your Stringlist.h, and it should run without needing

any other #includes in a2_test.cpp (all the #includes your Stringlist need should be in your Stringlist.h.

The marker will also run your Stringlist.h with Stringlist_test.cpp to ensure that all the original Stringlist functionality still works:

“`bash

make Stringlist_test g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g Stringlist_test.cpp -o Stringlist_test

./Stringlist_test … testing output … “`

Note The compilation commands are quite strict! Make sure your program compiles with them before submitting it.

Marking Scheme

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less. Hint: In the Linux command-line you can print all the lines in a file with more than 100 characters with this command (the initial &gt; is the prompt character, so don’t type it):

“`bash awk ‘length &gt; 100’ some_file.cpp “`

If this prints nothing, then the file has no lines over 100 characters long.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace has a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in the course. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

Deductions

a score of 0 if you:

have no statement of originality, or it’s modified in any way.

at least -1 mark if your file has an incorrect name, or you submit it in an incorrect format, etc.; possibly multiple deductions if there are multiple problems

at least -1 mark if you submit a non-working file

if the marker can easily fix your file and make it work, then there is only a small deduction if the marker has to spend a lot of time fixing your file, then there is a larger deduction; if they can’t make it work, then they you will get 0

Hints

The objects you store on the undo stack should contain enough information to undo the operations they correspond to. Your stack could, for example, store Action objects, where Action is a private struct that stores the name of the action and any other information needed for undoing.
