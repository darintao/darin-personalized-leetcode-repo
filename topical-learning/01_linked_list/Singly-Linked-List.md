# Singly Linked List

## Introduction

* Each element in the linked list is a separate object
* All the objects are **linked together by the reference field** in each element

## Node Structure

```java
public class SinglyListNode{
	int val;
	SinglyListNode next;
	SinglyListNode(int x) { val = x; }
}
```

* In most cases, the <span style="color: red">**head node**</span> is used to **represents the whole list**

## Operations & Time Complexity

* Access to random element takes <span style="color:red">*O(N)*</span> time to **visit an element by index**
  * If we want to get the $i^{th}$ element, we have to traverse from the head node one by one
* The benefit of the linked list?
  * **insert** and **delete**
  * 





