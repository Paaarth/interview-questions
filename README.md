## <a name='toc'>Table of Contents</a>
* [Angular Questions](#AngularQuestions)
* [Node.js Questions](#NodeQuestions) 
* [HTML Questions](#HTMLQuestions)
* [CSS Questions](#CSSQuestions)
* [Git Questions](#GitQuestions)

## [[⬆]](#toc) <a name=AngularQuestions>Angular Questions</a>

#### Q1: What is the difference between Angular's `ngOnInit` and constructor? ⭐⭐
**Answer:**
* The **constructor** is a default method in TypeScript classes that gets called when a class is instantiated.
* **ngOnInit** is an Angular lifecycle hook that runs after Angular has finished initializing all data-bound properties.
* Key difference: Use constructor for basic initialization and dependency injection, use ngOnInit for component-specific initialization logic.

#### Q2: Explain the difference between Angular's `ngIf` and `hidden` property ⭐⭐
**Answer:**
* **ngIf** is a structural directive that completely removes/adds elements from the DOM based on the condition.
* **hidden** is a DOM property that simply toggles visibility using CSS (display: none).
* Key difference: ngIf is better for memory efficiency as it destroys unused components, while hidden maintains them in memory.

## [[⬆]](#toc) <a name=NodeQuestions>Node.js Questions</a>

#### Q1: What is the Event Loop in Node.js? ⭐⭐
**Answer:**
* The **Event Loop** is what allows Node.js to perform non-blocking I/O operations.
* It's a single-threaded loop that processes events and callbacks in different phases (timers, I/O callbacks, idle/prepare, poll, check, close callbacks).
* Key point: It enables Node's asynchronous nature despite JavaScript being single-threaded.

## [[⬆]](#toc) <a name=HTMLQuestions>HTML Questions</a>

#### Q1: What is the purpose of the `DOCTYPE` declaration in HTML? ⭐
**Answer:**
* The `<!DOCTYPE>` declaration tells the web browser which version of HTML the page is written in.
* It must be the very first thing in your HTML document, before the `<html>` tag.
* Key purpose: Ensures the browser renders the page in standards mode rather than quirks mode.

## [[⬆]](#toc) <a name=CSSQuestions>CSS Questions</a>

#### Q1: Explain the CSS Box Model ⭐⭐
**Answer:**
* The CSS Box Model describes the rectangular boxes generated for elements and consists of:
  * Content (the actual content of the box)
  * Padding (space between content and border)
  * Border (edge around padding)
  * Margin (space outside the border)
* Key point: The `box-sizing` property controls whether width/height include padding and border (border-box) or just content (content-box).

## [[⬆]](#toc) <a name=GitQuestions>Git Questions</a>

#### Q1: What is Git fork? What is difference between fork, branch and clone? ⭐⭐
**Answer:**
* A **fork** is a remote, server-side copy of a repository, distinct from the original. A fork isn't a Git concept really, it's more a political/social idea. 
* A **clone** is not a fork; a clone is a local copy of some remote repository. When you clone, you are actually copying the entire source repository, including all the history and branches.
* A **branch** is a mechanism to handle the changes within a single repository in order to eventually merge them with the rest of code. A branch is something that is within a repository. Conceptually, it represents a thread of development.
