# Practical Interview

## React/Type Script

### Prompt

**Given an existing page that displays a list of events add a button that allows users to delete the event.**

**Expectation**

- Can navigate an existing code base identify event list page component.
- Can add a button to an existing page
- Can assign an action to the button
- Update the service to send appropriate API call

### Prompt

**We need to fix a bug where end date is not being correctly displayed write a test to catch the bug and then fix it.**

**Expectation**
- Can navigate an existing code base identify the end date is being displayed
- Write a test to check that the end date is displayed
- Update the code to fix the missing information

### Prompt

**When a duplicate name error is returned by the backend API we should display a message to the user.**

**Expectation**
- Can navigate an existing code base and identify where the backend API is being called.
- Then can identify existing patterns for error messages.
- Update the code so the error message is displayed.

## Java/Spring

### Prompt

**Given an existing events API add a delete endpoint to delete events by ID**

**Expectation**
- Can navigate an existing code base identify when to add controller
- Design an appropriate endpoint with the required information
- Add functionality to repository to delete entry.

### Prompt

**We need to fix a bug where the user is able to create multiple events with the same name write a test to catch the bug and fix it.**

**Expectation**
- Can navigate an existing code base identify where events are being created
- Write a test that fails if duplicate names are saved
- Update the code to return an error if the name already exists

## Critical Thinking / Story writing

We have a request for these features, how would you break them up into stories? What are some questions you would ask.

### Feature: Allow users to find an event by name

Sample Questions:
- Should the search be case-sensitive?
- Should the search return partial matches?

### Feature: Allow users to find events by creator

Sample Questions:
- Is the creator information being saved?
- Where is the creator information coming from?
- Should the search be case-sensitive?

### Feature: A User should only be able to only delete their own events

Sample Questions:
- How do I know who is using the application?
- Is there an admin who should be able to delete anything?

### Feature: A User should not be able to schedule 2 events at the same location and time.

Sample Questions:
- How should this error be displayed?