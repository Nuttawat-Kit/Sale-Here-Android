# Sale Here - Android Developer Interview Question

Please recreate a View from given screenshots Requirement:

- Your View must contain four tabs
    - recreate the first tab to be the same as `view-home.jpg`
    - recreate the third tab to be the same as `view-achievement.jpg`
    - leave the second and fourth tab blank
- On clicking the `New Goal` button, your View should route to the page that looks the same as `view-goal.jpg`
- Create a notification badge counter on the fourth tab
    - You must use Socket IO to implement this feature, and it must listen for new data from the following endpoint: `wss://35.240.248.118/update`
    - You can use the following endpoint to test updating badges on your View: **http://px-socket-emitter.saleherethailand.com/update**
        - The event name that will be emitted is `new-notification`
        - You do not need to implement a UI for this feature; it is provided to you for testing purposes only. Submission:
- Please submit both your source code.
