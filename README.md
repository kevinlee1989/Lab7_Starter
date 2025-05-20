Kevin Lee


1. 
I would fit my automated test within a Github action that runs whenever code is pushed(First option)

Since automated tests should be integrated directly into the development cycle to ensure immediate feedback whenever new features or functions are being pushed. By using the Github action, tests can be automatically triggered whenever someone makes a push or pull request so that it enables the code to catch bugs early, maintain code quality, and ensure that tests are always run. This continuous integration method ensures the project remains stable and reliable at any point of the phase of development.

2. 
No

End-to-end testing (E2E) is designed to test the entire application flow. from the user perspective. It simulates real user interactions in the applications such as clicking buttons and navigating between routers. Checking whether a specific fuction returns the true value is used by the unit test, not E2E testing. 


3.
The difference between the Navigation and Snapshot mode is the way of analyzing the page
Navigation mode analyzes the page as it loads from the start and provides a full performance report including First Contentful Paint, Speed Index and the Time to interactive. Otherwise the Snapshot mode analyzes the page in its current state which will be useful for checking things like accessibility or layout issues.

4.
After seeing the report from the lighthouse I noticed that we could improve several things.
- The first one is the image size which seems to be too large and can be optimized. The report is suggesting a potential savings of 864 KB. 
- The Second one is about adding a meta viewport tag which is important for responsive design and accessibility mainly on mobile devices. 
- The last one is serving images in next-gen formats such as WebP or AVIF instead of PNG or JPEG, I could save 165 KB which result in speeding up image loading.
