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

---?gist=webby980/0090a88a048ad918e76034d28348f6ef&lang=Kotlin&title=A Simple Mockk

@[1-2]

A 'relaxed' mock is a mock that returns some simple value for all functions.
<br>
This allows to skip specifying behavior for each case, while still allow to stub things you need.

Mockk is 'strict' by default, unless specified otherwise

---?gist=webby980/9e71b08f390a9c5806e1f3d156c9f2ff&lang=Kotlin&title=Mockk Every vs. Mockito Whenever

@[1-3](_Simple 'returns' example_)
@[5-7](_Simple 'answers' example_)

---?gist=webby980/ec2d90fe3352e7d2a3a2d445af9a7635&lang=Kotlin&title=Mockk Verify Order vs. Mockito Verify Order

@[1-5](_Mockito Verifying order example_)
@[7-11](_Mockk Verifying order example_)

---?gist=webby980/e3006d348b2d35d0b9e1a6283f1c722e&lang=Kotlin&title=Mockk Verify Sequence vs. Mockito Verify Order

@[1-7]
@[10-15](_verifyOrder vs. verifySequence?_)

---?gist=webby980/a33ee14ef999c76ea955fa5a262b0b74&lang=Kotlin&title=Mockk Slots vs. Mockito Captors

@[1-6](_Mockito Captors example_)
@[8-13](_Mockk Slots example_)

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

![](assets/img/question.gif)
