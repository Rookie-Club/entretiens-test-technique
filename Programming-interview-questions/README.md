# Question d'entretien de programmation

_à l'origne, un article en anglais : [Programming Interview Questions](http://www.ardendertat.com/2012/01/09/programming-interview-questions/) dont ce repos est à la fois une traduction, et le code réalisé en différent langage_


La liste complète de tous mes entretiens de programmation avec des liens vers les billets originaux (NDT: je ferais des fichiers markdown pour chaque). Il y a 28 questions au total, et 28 étant un nombre parfait (comme [Donald Knuth](https://en.wikipedia.org/wiki/Donald_Knuth) l'a mentionné) j'ai décidé que c'était le bon moment pour s'arreter.


1. [Array Pair Sum](/array-pair-sum/)

Étant donné un tableau d'entier, donner toutes les paires dont la somme est la valeur `k`.


2. [Matrix Region Sum](/matrix-region-sum/)

Given a matrix of integers and coordinates of a rectangular region within the matrix, find the sum of numbers falling inside the rectangle. Our program will be called multiple times with different rectangular regions from the same matrix.


3. [Largest Continuous Sum](/largest-continuous-sum/)

Given an array of integers (positive and negative) find the largest continuous sum.


4. [Find Missing Element](/find-missing-element)

There is an array of non-negative integers. A second array is formed by shuffling the elements of the first array and deleting a random element. Given these two arrays, find which element is missing in the second array.


5. [Linked List Remove Nodes](/linked-list-remove-nodes)

Given a linkedlist of integers and an integer value, delete every node of the linkedlist containing that value.


6. [Combine Two Strings](/combine-two-strings)

We are given 3 strings: str1, str2, and str3. Str3 is said to be a shuffle of str1 and str2 if it can be formed by interleaving the characters of str1 and str2 in a way that maintains the left to right ordering of the characters from each string. For example, given str1=”abc” and str2=”def”, str3=”dabecf” is a valid shuffle since it preserves the character ordering of the two strings. So, given these 3 strings write a function that detects whether str3 is a valid shuffle of str1 and str2.


7. [Binary Search Tree Check](/binary-search-tree-check)

Given a binary tree, check whether it’s a binary search tree or not.


8. [Transform Word](/transform-word)

Given a source word, target word and an English dictionary, transform the source word to target by changing/adding/removing 1 character at a time, while all intermediate words being valid English words. Return the transformation chain which has the smallest number of intermediate words.


9. [Convert Array](/convert-array)

Given an array [a1, a2, …, aN, b1, b2, …, bN, c1, c2, …, cN]  convert it to [a1, b1, c1, a2, b2, c2, …, aN, bN, cN] in-place using constant extra space


10. [Kth Largest Element in Array](/kth-largest-element-in-array)

Given an array of integers find the kth element in the sorted order (not the kth distinct element). So, if the array is [3, 1, 2, 1, 4] and k is 3 then the result is 2, because it’s the 3rd element in sorted order (but the 3rd distinct element is 3).


11. [All Permutations of String](/all-permutations-of-string)

Generate all permutations of a given string.


12. [Reverse Words in a String](/reverse-words-in-a-string)

Given an input string, reverse all the words. To clarify, input: “Interviews are awesome!” output: “awesome! are Interviews”. Consider all consecutive non-whitespace characters as individual words. If there are multiple spaces between words reduce them to a single white space. Also remove all leading and trailing whitespaces. So, the output for ”   CS degree”, “CS    degree”, “CS degree   “, or ”   CS   degree   ” are all the same: “degree CS”.


13. [Median of Integer Stream](/median-of-integer-stream)

Given a stream of unsorted integers, find the median element in sorted order at any given time. So, we will be receiving a continuous stream of numbers in some random order and we don’t know the stream length in advance. Write a function that finds the median of the already received numbers efficiently at any time. We will be asked to find the median multiple times. Just to recall, median is the middle element in an odd length sorted array, and in the even case it’s the average of the middle elements.


14. [Check Balanced Parentheses](/check-balanced-parentheses)

Given a string of opening and closing parentheses, check whether it’s balanced. We have 3 types of parentheses: round brackets: (), square brackets: [], and curly brackets: {}. Assume that the string doesn’t contain any other character than these, no spaces words or numbers. Just to remind, balanced parentheses require every opening parenthesis to be closed in the reverse order opened. For example ‘([])’ is balanced but ‘([)]‘ is not.


15. [First Non Repeated Character in String](/first-non-repeated-character-in-string)

Find the first non-repeated (unique) character in a given string.


16. [Anagram Strings](/anagram-strings)

Given two strings, check if they’re anagrams or not. Two strings are anagrams if they are written using the same exact letters, ignoring space, punctuation and capitalization. Each letter should have the same count in both strings. For example, ‘Eleven plus two’ and ‘Twelve plus one’ are meaningful anagrams of each other.


17. [Search Unknown Length Array](/search-unknown-length-array)

Given a sorted array of unknown length and a number to search for, return the index of the number in the array. Accessing an element out of bounds throws exception. If the number occurs multiple times, return the index of any occurrence. If it isn’t present, return -1.


18. [Find Even Occurring Element](/find-even-occurring-element)

Given an integer array, one element occurs even number of times and all others have odd occurrences. Find the element with even occurrences.


19. [Find Next Palindrome Number](/find-next-palindrome-number)

Given a number, find the next smallest palindrome larger than the number. For example if the number is 125, next smallest palindrome is 131.


20. [Tree Level Order Print](/tree-level-order-print)

Given a binary tree of integers, print it in level order. The output will contain space between the numbers in the same level, and new line between different levels.


21. [Tree Reverse Level Order Print](tree-reverse-level-order-print)

This is very similar to the previous post level order print. We again print the tree in level order, but now starting from bottom level to the root.


22. [Find Odd Occurring Element](find-odd-occurring-element)

Given an integer array, one element occurs odd number of times and all others have even occurrences. Find the element with odd occurrences.


23. [Find Word Positions in Text](/find-word-positions-in-text)

Given a text file and a word, find the positions that the word occurs in the file. We’ll be asked to find the positions of many words in the same file.


24. [Find Next Higher Number With Same Digits](/find-next-higher-number-with-same-digits)

Given a number, find the next higher number using only the digits in the given number. For example if the given number is 1234, next higher number with same digits is 1243.


25. [Remove Duplicate Characters in String](/remove-duplicate-characters-in-string)

Remove duplicate characters in a given string keeping only the first occurrences. For example, if the input is ‘tree traversal’ the output will be ‘tre avsl’.


26. [Trim Binary Search Tree](/trim-binary-search-tree)

Given the root of a binary search tree and 2 numbers min and max, trim the tree such that all the numbers in the new tree are between min and max (inclusive). The resulting tree should still be a valid binary search tree.


27. [Squareroot of a Number](/squareroot-of-a-number)

Find the squareroot of a given number rounded down to the nearest integer, without using the sqrt function. For example, squareroot of a number between [9, 15] should return 3, and [16, 24] should be 4.


28. [Longest Compound Word](/longest-compound-word)

Given a sorted list of words, find the longest compound word in the list that is constructed by concatenating the words in the list. For example, if the input list is: [‘cat’, ‘cats’, ‘catsdogcats’, ‘catxdogcatsrat’, ‘dog’, ‘dogcatsdog’, ‘hippopotamuses’, ‘rat’, ‘ratcat’, ‘ratcatdog’, ‘ratcatdogcat’]. Then the longest compound word is ‘ratcatdogcat’ with 12 letters. Note that the longest individual words are ‘catxdogcatsrat’ and ‘hippopotamuses’ with 14 letters, but they’re not fully constructed by other words. Former one has an extra ‘x’ letter, and latter is an individual word by itself not a compound word.

