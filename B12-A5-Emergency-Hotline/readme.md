1. getElementById("id") gives one element by id. getElementsByClassName("class") gives many by class, querySelector("selector") gives the first match, and querySelectorAll("selector") gives all matches.

2. I create a new element with document.createElement("tag"). Then I put it in the DOM using appendChild() or similar.

3. In event bubbling, when an event happens on a child, it also runs on its parent, then higher parents. It goes upward in order until <body>.

4. Event delegation means adding one event listener on a parent and handling events of its children inside it. It is useful for many elements or dynamic elements.

5. preventDefault() stops the default browser action (like link jump). stopPropagation() stops the event from bubbling to parent elements.
