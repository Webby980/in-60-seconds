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
- Clean, pleasant to use, good documentation and less boilerplate
- Now widely used in the Kotlin community 
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

---?gist=webby980/0995ddcb94f54a3391da10b274794f9b&lang=Kotlin&title=Mockk Every vs. Mockito Whenever

@[1-3](_Simple 'returns' example_)
@[5-11](_Simple 'answers' example_)

---?gist=webby980/76d28732a5d3e5179efa7a59c5ea6855&lang=Kotlin&title=Mockk Verify Order vs. Mockito Verify Order

@[1-5](_Mockito Verifying order example_)
@[7-13](_Mockk Verifying order example_)

---?gist=webby980/63c973214b39b00acfa2c8986655eec6&lang=Kotlin&title=Mockk Verify Sequence vs. Mockito Verify Order

@[1-7]
@[9-15](_verifyOrder vs. verifySequence?_)

---?gist=webby980/bf59d670ab1bd81748f543e096ff34e4&lang=Kotlin&title=Mockk Slots vs. Mockito Captors

@[1-9](_Mockito Captors example_)
@[11-19](_Mockk Slots example_)

---?gist=webby980/372e7f0e630fb79e00c9b644e6e6d75a&lang=Kotlin&title=Mockk Chained Calls

@[1-6](_Chained Calls_)
@[8-10](_Verifying Chained Calls_)

---
@title[Conclusion?]

@snap[north-west]
### What have we leant from this POC?
@snapend

@snap[west]
@ul[spaced text-black]
- Easy to use/less snags than Mockito
- Now widely used in the Kotlin community = better documentation
- Potentially our de facto mocking framework?
@ulend
@snapend

<br>
<br>

@snap[south]
![](assets/img/over.gif)
@snapend
