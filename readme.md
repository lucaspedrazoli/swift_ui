<h1> Basics </h1>
<p>Swift UI is declarative. In comparison with imperative, wich is what we were doing before iOS 13. In an imperative 
we might make a function be called when a button was clicked, and inside the function we would read the value 
and show a label. We regularly modify the way the user interface looks and works based on what is happening. Imperative UI 
causes all sorts of problems, most of which resolve around state, which is another fancy term meaning 
"values we store in our code". We need to track what state our code is in, and make sure our user interface correctly
reflects that state.</p>

<p> In contrast, declarative UI lets us tell iOS about all possible states of our app at once. We might say if we are logged
in show a welcome message but if we are logged out show a login button. We dont need to write code to move between those two
states by hand <p/>

<p> Instead, we let Swift UI move between user interface layouts  for us when the state changes. We already told it what
to show based on whether the user was logged in or out. If we change the authenticationstate SwiftUI will update the UI<p/>
 
