### #daysofcode 1/9/20 

**Today's Progress**
- TDD & REST Challenge:
- 2hr call with mentor - unable to get axios working in node. Decided to drop the TDD side and continue as a crude REST app. 
- Add event listeners and handlers for the remaining REST functions.
- Added alert with HTTP status code from the response.
- Converted actions to async so alert only fire after action complete.
- Hosted on Netlify.
- Looked at AWS EC2 hosting. 
- AWS AMI - a template that contains the software configuration (operating system, application server, and applications) required to launch your instance.
- Finished .readme - mentioning the pivot.
- Created gif.
- Added to portfolio site.
- Added a paragraph that displays the method, response code and body.
- Included headers as args when making the requests (where appropriate).
- Updated CV with new skills & knowledge. Added to portfolio.

**Thoughts** 
- We possible could have got the axios tests working using either React (uses web pack) or via mocking or bundling but as time is of the essence am happy to move on. Have still learned a lot about TDD, just unable to have something to show for it at this stage. Will keep the attempt as part of the project and mention the challenges/obstacles/attempts in the readme. Guess this also gives some experience in knowing when to call things and make an executive decision (on a feature for example).
- Back to basics with DOM events so a good refresher.
- Used async from memory = I understand it better nowadays.
- Crude app up and running and hosted on Netlify. Decided to check out AWS hosting for some further experience with the Amazon Web Service ecosystem. Got as far as launching and instance and creating a key pair. Next steps looked pretty complex. Another decision to leave for now.
- Another long day on minimal sleep but loving it.

### #daysofcode 2/9/20 

**Today's Progress**
- TDD & REST Project:
- Refactored the 5 verb functions into a single one that takes arguments = implementing DRY.
- Mentor job prep meetings.
- Job prep.
- Reading on translating business requirement into technical requirements and multithreading concepts.

**Thoughts** 
- Had a play with using git in the terminal - Been using GitGraph since day 1 as I prefer the visuals but good to get comfortable with terminal use if GG isn't available for whatever reason.
- Awesome and thorough day of job prep. Super grateful for the experience and support of my mentor.

### #daysofcode 3/9/20 

**Today's Progress**
- Job prep.
- TDD & REST project DRY refactoring from 158 to 89 lines of code.
- Merged DRY branch back into master using terminal.

**Thoughts** 
- Thorough session tweaking CV & portfolio with mentor.
- Struggling to get the DRY function working. Seems to be firing on load rather than through the event listener and no longer displays the desired info from the response object.
- Had to wrap the second listener parameter inside an anonymous function - works on click now. Not displaying full text though. Fixed.
- Almost halved the file length, cool!
- Delete displays undefined as body, I want to not display that line if undefined. Used a conditional and works as planned. Can possibly refactor the conditional further as some parts do repeat but can't figure it out as there are multiple strings. Leaving for now.
- Gig Graph doesn't show a trace of a new branch splitting off from master and then merging back. Possibly due to some default settings such as squashing, ff and merging that I didn't specify which usually come as standard using GG? Not to worry, it worked.
- Will go back over my old projects and refactor using DRY and SOLID for a bit of practice at some point.

### #daysofcode 6/9/20 

**Today's Progress**
- N/A.

**Thoughts** 
- Reading about Human Computer Interaction (HCI) and cognitive science. Super intrigued by this area as it covers two of my passions (and career paths) of computing and psychology.
- Opted for a cycle today instead of a run. As much as I love running, it does tend to reduce my sleep quality the night of the run which then affects my productivity the next day.

### #daysofcode 16/9/20 

**Today's Progress**
- Code Reviews - Learning what is involved and best practices for receiving them.

### #daysofcode 18/9/20 

**Today's Progress**
- Prepped converting existing functions into smaller components.

**Thoughts** 
- A few of my functions do more than one thing so have been looking at how I can break them down further which also enables unit testing.
- A few of them involved interaction with the database so will start to look at mocking soon. 

### #daysofcode 19/9/20 

**Today's Progress**
- Scrum: The art of doing twice the work in half the time. Getting myself more familiar with the methodology.

**Thoughts** 
- Been recommended to check out Jeff Sutherland to get a better idea of scrum so I bought his book and watched a few vids.
- Fascinating back story to JS (Planning and landing a jet during war, cellular evolution/cancer research etc) - love how he brought in knowledge and experience from other disciplines to solve his challenges. It's almost like sampling and influences in music production except with ideas and concepts.
- Love the 5 scrum values - Openness, Courage, Respect, Focus and Commitment. Cool that this process has the concept of values as part of it. Used a lot in coaching and I also update and work to mine each few months. Another cool parallel with coaching.

### #daysofcode 20/9/20 

**Today's Progress**
- N/A.

**Thoughts** 
- Full day off code. Only had 3 in the last 5 weeks. Deserved breather.

### #daysofcode 21/9/20 

**Today's Progress**
- Testing React Components - looking at the common methods in React Testing Library. Rather than dealing with instances of rendered React components, your tests will work with actual DOM nodes = more maintainable.
- Snapshot Test - generates an HTML-like output so you can see how your component is structured. It’s especially useful if you want to see how your CSS properties are injected according to events.
- data-testid - makes the relationship between the test and the source code more explicit. Add some metadata to the element you are trying to select using an existing API - data- attributes.

**Thoughts** 
- Most of my testing to date has been around functions/functionality but this will also test to make sure the components are rendering(correctly).
- There is a lot going on here compared to simple unit tests but sure once I have a go myself it will make more sense.
- Realised this am that the chrome extensions I installed to remind me to breathe deeper, more often are being ignored (almost annoying me/having the opposite effect) so would like to take the reminder back on board.
- I see Jest has a coverage option that can tell you how much of your project is covered by tests - super cool.
- Had a brief look at testing hooks - another layer to learn.

### #daysofcode 22/9/20 

**Today's Progress**
- Think in React (5 steps) - 1. Break the UI into components 2. Build a static version 3. Minimal representation of state 4. Where should state live? 5. Add inverse data flow.
- Component Lifecycle Methods refresher - Mounting, Updating, Unmounting and Error Handling.

**Thoughts** 
- Going back over some basics today to solidify some React fundamentals.

### #daysofcode 23/9/20 

**Today's Progress**
- Job prep.

### #daysofcode 24/9/20 

**Today's Progress**
- Code review prep.

### #daysofcode 25/9/20 

**Today's Progress**
- Peer Programming prep.

### #daysofcode 26/9/20 

**Today's Progress**
- Planning next phase:
- Highlighting which areas of React to concentrate on next using guides by @dev.jeanrauwers and the React Learning Path 2020. Forms and main hooks to start with.

### #daysofcode 27/9/20 

**Today's Progress**
- N/A.

**Thoughts** 
- Day off from code. Exercise and family time to recharge.

### #daysofcode 28/9/20 

**Today's Progress**
- React Forms:
- Controlled components - form data is handled by a React component. Uncontrolled components - form data is handled by the DOM itself. Input, text area, select and submit.
- Basic Hooks refresher - useState, useEffect, useContext.

**Thoughts** 
- The React Learning Path has given me some structure to my React learning going forward. I'm excited to dive deeper and fully grasp the fundamentals then move onto the more advanced concepts. Setup my RJS google doc in a logical manner.
- Nice to get back to learning after a few weeks of job prep.
- Understanding what life was like pre hooks explains a lot of "older code" I have come across and the motivation behind the main hooks and APIs React have added recently.
