## CI & CD

**Continuous integration** is the practice of introducing changes into a codebase several times a day. Typically, a CI process will look like this: Logically, we start by making any desired changes to the code. Once done, we run Unit Tests on this new code. If these tests complete successfully, we can move to the final step: Integration. This is where we merge the new tested code into the codebase, and optionally create a new build or deploy the code to a staging environment.

**Benefit**: broken code is less likely to reach the main codebase

**Continuous Delivery** takes this a step further. This is essentially the same as CI with one crucial difference: it allows us to deploy to production with a manual step, like the tap of a button.

**Continuous Deployment** is if you want a 100% automated process.  With this in place, nobody needs to touch a button to have a working build deployed – every step is automated!