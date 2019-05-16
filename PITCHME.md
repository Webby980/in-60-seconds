## **Mockk**
#### An alternative to Mockito

![](assets/img/mockk.png)

---
@title[Reasons to Use]

@snap[north-west]
### Reasons to Use
@snapend

@snap[west]
@ul[spaced text-black]
- Clean, pleasant to use and less boilerplate
- Now more widely used in the Kotlin community 
- Plenty of features
- E.g. Easy mocking of private functions, constructor mocking, coroutine mocking etc
- Which would potentially be useful for new work
@ulend
@snapend

---
@title[Examples?]

## *Examples?*

#### What does Mockk offer us?

![](assets/img/example.gif)

---?gist=webby980/ec9ee81f56eca4151a1f6fb8dc54d7af&lang=Kotlin&title=A Simple Mockk

@[1-2]

A 'relaxed' mock is a mock that returns some simple value for all functions.
<br>
This allows to skip specifying behavior for each case, while still allow to stub things you need.

Mockk is 'strict' by default, unless specified otherwise

---?gist=webby980/3d1898a1fe6706d7ceecf46ffa2a96c2&lang=Kotlin&title=Mockk Every vs. Mockito Whenever

@[1-3](_Simple 'returns' example_)
@[5-7](_Simple 'answers' example_)

---?gist=webby980/76d28732a5d3e5179efa7a59c5ea6855&lang=Kotlin&title=Mockk Verify Order vs. Mockito Verify Order

@[1-7](_Mockito Verifying order example_)
@[9-13](_Mockk Verifying order example_)

---?gist=webby980/0abc9953e926b5513447c98bfbdd349f&lang=Kotlin&title=Mockk Verify Sequence vs. Mockito Verify Order

@[1-8]
@[11-17](_verifyOrder vs. verifySequence?_)

---?gist=webby980/bf59d670ab1bd81748f543e096ff34e4&lang=Kotlin&title=Mockk Slots vs. Mockito Captors

@[1-9](_Mockito Captors example_)
@[11-19](_Mockk Slots example_)

---?gist=webby980/372e7f0e630fb79e00c9b644e6e6d75a&lang=Kotlin&title=Mockk Chained Calls

@[1-6](_Chained Calls_)
@[8-10](_Verifying Chained Calls_)

---
@title[Conclusion?]

@snap[north-west]
#### Opinions from a Mockito user
@snapend

@snap[south-west]
@ul[spaced text-black]
- Easier to use/less snags than Mockito e.g. chained calls
- More functional approach which is suited to Kotlin
- More human readable e.g. someMock wasNot Called (good use of infix function)
- Slightly less docs but more appearing now it is being widely adopted (great github page/glossary)
- Potentially our de facto mocking framework?
@ulend
@snapend

---
@title[Questions?]

## **Questions?**

![](assets/img/example.gif)
